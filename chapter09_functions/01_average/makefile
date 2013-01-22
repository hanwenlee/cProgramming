all: average

clean:
	rm -f average *.o

average: average.o
	gcc -o average average.o

average.o: average.c
	gcc -c average.c
