CC=g++
CFLAGS=-std=c++11
LFLAGS= -lglut -lGL

target=triangle

triangle: triangle.o
	$(CC) $(CFLAGS) $^ -o $@ $(LFLAGS)

triangle.o: triangle.cpp
	$(CC) $(CFLAGS) $^ -c

clean:
	rm triangle.o triangle
