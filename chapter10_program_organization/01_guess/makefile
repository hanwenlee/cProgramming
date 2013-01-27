all: guess

clean:
	rm guess *.o
	
guess: guess.o
	gcc -o guess guess.o

guess.o: guess.c
	gcc -c guess.c