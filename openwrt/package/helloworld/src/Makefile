main: main.o
	$(CC) $(LDFLAGS) main.o -o helloworld

main.o: main.c
	$(CC) $(CFLAGS) -c main.c

clean:
	rm *.o helloworld