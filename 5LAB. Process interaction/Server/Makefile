CC = gcc

CFLAGS = -c -Wall
all: server

server: server.o fun.o
	$(CC) server.o fun.o -o server

server.o: server.c
	$(CC) $(CFLAGS) server.c

fun.o: fun.c
	$(CC) $(CFLAGS) fun.c

clean:
	rm -rf *.o server
