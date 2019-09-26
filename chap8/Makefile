ROOT=..
include $(ROOT)/Makefile.define
PROGS = 8_1

all:	$(PROGS)

%:		%.c $(LIBAPUE)
		cc $(CFLAGS) $@.c -o $@ $(LDFLAGS) $(LDLIBS)

clean:
	rm -f $(PROGS) $(MOREPROGS) *.o