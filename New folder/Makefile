all: compile link

compile:
	g++ -I"include" -c main.cpp

link:
	g++ main.o -o Main -L"lib" -mwindows -lglut32 -lopengl32 -lglu32