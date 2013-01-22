all: prime

clean:
	rm -f prime *.o

average: prime.o
	gcc -o prime prime.o

average.o: prime.c
	gcc -c prime.c
