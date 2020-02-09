.PHONY : all clean
all : crx2rnx rnx2crx

crx2rnx : src/crx2rnx.c
	gcc -o crx2rnx src/crx2rnx.c

rnx2crx : src/rnx2crx.c
	gcc -o rnx2crx src/rnx2crx.c

clean :
	@rm -f src/*.o 
	@rm -f crx2rnx rnx2crx