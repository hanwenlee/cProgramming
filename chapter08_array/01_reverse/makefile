all: reverse

clean:
	rm -f reverse.o reverse
	
reverse: reverse.o
	gcc -o reverse reverse.o
	
reverse.o: reverse.c
	gcc -c reverse.c
