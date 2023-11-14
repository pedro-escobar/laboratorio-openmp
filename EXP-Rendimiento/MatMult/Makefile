GCC = gcc
oT = -fopenmp -O3 

CFLAGS = -lm 

oL= Otime.c

BINDIR = ../BIN/
PROGS = $(BINDIR)MM1c $(BINDIR)MM1f

all: MM1c MM1f

clean:
	$(RM) $(PROGS)

MM1c:
	$(GCC) $(oT) $(oL) $@.c -o $(BINDIR)$@ $(CFLAGS)

MM1f:
	$(GCC) $(oT) $(oL) $@.c -o $(BINDIR)$@ $(CFLAGS)