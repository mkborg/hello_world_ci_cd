.PHONY: all

all: hello_world
hello_world:
	gcc -o hello_world hello_world.c


.PHONY: check

check: check-hello_world
.PHONY: check-hello_world
check-hello_world: hello_world
	./hello_world


.PHONY: clean

clean: clean-hello_world
.PHONY: clean-hello_world
clean-hello_world:
	-rm -vf hello_world
