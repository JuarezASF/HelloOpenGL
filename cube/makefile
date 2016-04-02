CC=g++
CFLAGS=-std=c++11
LFLAGS= -lglut -lGL -lGLU -lm

target=cube

cube: cube.o
	$(CC) $(CFLAGS) $^ -o $@ $(LFLAGS)

cube.o: cube.cpp
	$(CC) $(CFLAGS) $^ -c

clean:
	rm cube cube.o

