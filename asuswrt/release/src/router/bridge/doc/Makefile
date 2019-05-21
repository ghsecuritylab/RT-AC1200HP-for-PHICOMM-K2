
DESTDIR=
KERNEL_HEADERS=-I/home/wenxuejin/GPL_RT-AC1200HP_3.0.0.4.380.8457/asuswrt/release/src-ra-mt7620/linux/linux-2.6.36.x/include

INSTALL=install -s

prefix=
exec_prefix=${prefix}
bindir=${exec_prefix}/bin
sbindir=${exec_prefix}/sbin
mandir=${prefix}/man

SUBDIRS=libbridge brctl

all:

clean:

install:
	mkdir -p $(DESTDIR)$(mandir)/man8
	install -m 644 brctl.8 $(DESTDIR)$(mandir)/man8
