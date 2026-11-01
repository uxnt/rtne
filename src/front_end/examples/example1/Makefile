RICE := rice
CLANG := clang

.PHONY: build

build:
	${TBOX} ./a.rice ./a.o
	${CLANG} ./b.c -c -o ./b.o
	${CLANG} ./a.o ./b.o -o ./example.exe
