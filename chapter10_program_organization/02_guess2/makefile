all: guess2

clean:
	rm guess2 *.o
	
guess2: guess2.o
	gcc -o guess2 guess2.o

guess2.o: guess2.c
	gcc -c guess2.c