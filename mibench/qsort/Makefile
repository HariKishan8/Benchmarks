FILE2 = qsort_large.c

all: qsort_large

qsort_large: qsort_large.c Makefile
	gcc -static qsort_large.c -O3 -o qsort_large -lm

clean:
	rm -rf qsort_large output*
