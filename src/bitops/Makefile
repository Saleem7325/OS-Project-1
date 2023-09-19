TARGET = bitops 
CC = gcc
CFLAGS = -g -std=c99 

$(TARGET): bitops.c 
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm -rf $(TARGET) *.o *.a *.dylib *.dSYM
