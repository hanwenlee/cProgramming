all: deal

clean:
	rm -f deal.o deal
	
deal: deal.o
	gcc -o deal deal.o
	
deal.o: deal.c
	gcc -c deal.c
