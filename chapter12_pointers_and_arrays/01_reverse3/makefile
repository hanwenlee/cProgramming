all: reverse3

clean:
	rm -f reverse3 *.o

reverse3: reverse3.o
	gcc -o reverse3 reverse3.o

reverse3.o: reverse3.c
	gcc -c reverse3.c