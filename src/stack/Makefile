TARGET = stack
CC = gcc
CFLAGS = -g -std=c99 -m32

$(TARGET): $(TARGET).c 
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm -rf $(TARGET) *.o *.a *.dylib *.dSYM
