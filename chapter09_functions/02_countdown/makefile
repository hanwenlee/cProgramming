all: countdown

clean:
	rm -f countdown *.o

countdown: countdown.o
	gcc -o countdown countdown.o

countdown.o: countdown.c
	gcc -c countdown.c
