
CC = wla-6510
CFLAGS = -o
LD = wlalink
LDFLAGS = -vs

SFILES = main.s
OFILES = main.o

all: $(OFILES) makefile
	$(LD) $(LDFLAGS) linkfile linked.rom

main.o: main.s
	$(CC) $(CFLAGS) main.s main.o


$(OFILES): $(HFILES)


clean:
	rm -f $(OFILES) core *~ linked.rom *.sym

