object = rbtree.o test.o
bin:$(object)
	gcc -o  $@ $(object)
rbtree.o:rbtree.c
	gcc -c -o $@ $<
test.o:test.c
	gcc -c -o $@ $<
clean:
	rm -f *.o