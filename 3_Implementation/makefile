all: pd

pdm:main.o calculaor.o
	gcc -Wall -o pd main.o calculator.o

main.o:main.c
	gcc -c -Wall main.c

calculator.o:calculator.c
	gcc -c -Wall calculator.c
