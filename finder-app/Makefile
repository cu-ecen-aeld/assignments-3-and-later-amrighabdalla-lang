CC := $(CROSS_COMPILE)gcc
CFLAGS := -Wall -Wextra -Werror
TARGET := writer
SRC := writer.c

.PHONY: all clean

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) $(SRC) -o $(TARGET)

clean:
	rm -f $(TARGET)
