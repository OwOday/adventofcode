AS=as
LD=ld

all: assemble

assemble: day1.s
	as -g day1.s -o day1.o
	ld day1.o -o day1

run: assemble
	day1
