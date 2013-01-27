all:viewmemory

clean:
	rm -f viewmemory *.o

viewmemory: viewmemory.o
	gcc -o viewmemory viewmemory.o

viewmemory.o: viewmemory.c
	gcc -c viewmemory.c
