## Process this file with Automake to create Makefile.in

INCLUDES = @INCLUDES@ -I$(top_srcdir) -I$(top_srcdir)/lib
DEFS = @DEFS@ -DSTATEDIR=\"$(localstatedir)/\"

AM_CFLAGS = $(PICFLAGS)
AM_LDFLAGS = $(PILDFLAGS)

sbin_PROGRAMS = watchquagga

watchquagga_SOURCES = watchquagga.c
watchquagga_LDADD = ../lib/libzebra.la @LIBCAP@
