
OBJS = hello.o

PROG1 = hello

CC = g++
DEBUG = -g
CFLAGS = -Wall -c $(DEBUG)
LFLAGS = -Wall $(DEBUG)

all: $(PROG1) 

$(PROG1) : $(OBJS)
	$(CC) $(LFLAGS) -o $@ $(OBJS) 

clean:
	rm -f $(PROG1) *.o

.SUFFIXES: $(SUFFIXES) .cpp

.cpp.o:
	$(CC) $(LFLAGS) -c $<



