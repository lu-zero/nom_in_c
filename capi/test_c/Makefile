CC=gcc
CFLAGS=-Wall -I..
LIBS=-L../target/debug -lembed_capi

all:
	$(CC) $(CFLAGS) -o main main.c $(LIBS)

clean:
	rm -f main
