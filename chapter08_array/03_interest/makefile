all: interest

clean:
	rm -f interest.o interest
	
interest: interest.o
	gcc -o interest interest.o
	
interest.o: interest.c
	gcc -c interest.c
