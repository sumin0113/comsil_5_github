cc = gcc
target = sogang
objects = main.o student.o professor.o

$(target): $(object)
	$(cc) -o $(target) $(objects)

$(objects): sogang.h

.PHONY: clean
clean:
	rm -f $(target) $(objects)
