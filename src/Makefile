
.PHONY:all
CFLAGS = -O2 -Wall
CFLAGS+= -D__ROCK5A__

all: fan-control

clean:
	$(RM) fan-control *.o

fan-control: fan-control.o
	$(CC) $(CFLAGS) $^ -o $@

%.o : %.c
	$(CC) $(CFLAGS) -c $< -o $@
