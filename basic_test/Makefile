
FLAGS=\
	-Wall \
	-std=c++11
INCLUDE=\
	-I/usr/include/opencv4/
LIBS=\
	`pkg-config opencv4 --cflags --libs`

all:
	g++ $(FLAGS) $(INCLUDE) -o bin/main main.cpp $(LIBS)
