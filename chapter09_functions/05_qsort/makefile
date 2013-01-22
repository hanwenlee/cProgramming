all: qsort

clean:
	rm -f qsort *.o

qsort: qsort.o
	gcc -o qsort qsort.o

qsort.o: qsort.c
	gcc -c qsort.c
