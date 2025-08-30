.PHONY: all
all: 01_hello_world 01_hello_world_fix 02_temperature

.PHONY: 01_hello_world
01_hello_world: 01_hello_world.c
	gcc -o 01_hello_world 01_hello_world.c

.PHONY: 01_hello_world_fix
01_hello_world_fix: 01_hello_world_fixed.c
	gcc -o 01_hello_world_fixed 01_hello_world_fixed.c

.PHONY: 02_temperature
02_temperature: 02_temperature.c
	gcc -o 02_temperature 02_temperature.c

.PHONY: clean
clean:
	rm -f 01_hello_world 01_hello_world_fixed 02_temperature


