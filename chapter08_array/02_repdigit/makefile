all: repdigit

clean:
	rm -f repdigit.o repdigit
	
repdigit: repdigit.o
	gcc -o repdigit repdigit.o
	
repdigit.o: repdigit.c
	gcc -c repdigit.c
