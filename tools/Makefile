all: screw decrypt

screw: screw.c zencode.c
	gcc -o screw screw.c zencode.c -lz

decrypt: decrypt.c
	gcc -o decrypt decrypt.c zencode.c -lz

clean:
	/bin/rm *.o *.so screw decrypt
