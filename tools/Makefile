
CFLAGS = -Wall -ggdb -O2 -I../kernel/include

all: fru-dump fmc-mem fru-dump-acq

all clean:
	$(MAKE) -C libipmi $@

# placeholders, so ../Makefile is happy
modules install modules_install:
