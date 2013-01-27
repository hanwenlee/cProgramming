all: poker

clean:
	rm poker *.o
	
poker: poker.o
	gcc -o poker poker.o

poker.o: poker.c
	gcc -c poker.c