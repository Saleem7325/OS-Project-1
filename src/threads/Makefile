TARGET = threads
CC = gcc
CFLAGS = -g -std=c99 -pthread 

$(TARGET): $(TARGET).c 
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm -rf $(TARGET) *.o *.a *.dylib *.dSYM
