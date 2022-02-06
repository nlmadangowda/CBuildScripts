CC      = gcc
CFLAGS  = -g
RM      = rm -f

AV = 0.1
OP:=./out
OP:=$(OP)_$(AV)

default: all

all: $(OP)

$(OP): Hello.c
	$(CC) $(CFLAGS) -o $(OP) Hello.c

clean veryclean:
	$(RM) $(OP)
