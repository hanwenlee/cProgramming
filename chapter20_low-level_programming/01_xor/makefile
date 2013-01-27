all: xor

clean:
	rm -f xor *.o

xor: xor.o
	gcc -o xor xor.o

xor.o: xor.c
	gcc -c xor.c