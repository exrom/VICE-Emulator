AM_CPPFLAGS = \
	@VICE_CPPFLAGS@ \
	@ARCH_INCLUDES@ \
	-I$(top_builddir)/src \
	-I$(top_srcdir)/src \
	-I$(top_srcdir)/src/drive \
	-I$(top_srcdir)/src/printerdrv \
	-I$(top_srcdir)/src/sid \
	-I$(top_srcdir)/src/tape \
	-I$(top_srcdir)/src/vicii \
	-I$(top_srcdir)/src/video \
	-I$(top_srcdir)/src/raster \
	-I$(top_srcdir)/src/samplerdrv \
	-I$(top_srcdir)/src/userport \
	-I$(top_srcdir)/src/lib/p64 \
	-I$(top_srcdir)/src/joyport \
	-I$(top_srcdir)/src/c64 \
	-I$(top_srcdir)/src/rs232drv \
	-I$(top_srcdir)/src/tapeport \
	-I$(top_srcdir)/src/datasette \
	-I$(top_srcdir)/src/core/rtc

AM_CFLAGS = @VICE_CFLAGS@ @INLINE_UNIT_GROWTH@

AM_CXXFLAGS = @VICE_CXXFLAGS@

AM_LDFLAGS = @VICE_LDFLAGS@


noinst_LIBRARIES = libc64dtv.a libc64dtvstubs.a

libc64dtvstubs_a_SOURCES = \
	c64dtv-stubs.c

libc64dtv_a_SOURCES = \
	c64dtvmemsnapshot.h \
	c64dtvmemsnapshot.c \
	c64dtvmem.h \
	c64dtvmem.c \
	c64dtvmemrom.c \
	c64dtvblitter.c \
	c64dtvblitter.h \
	c64dtvcpu.c \
	c64dtvcpu.h \
	c64dtvdma.c \
	c64dtvdma.h \
	c64dtvflash.c \
	c64dtvflash.h \
	c64dtv-cmdline-options.c \
	c64dtv-cmdline-options.h \
	c64dtv-resources.c \
	c64dtv-resources.h \
	c64dtv-snapshot.c \
	c64dtv-snapshot.h \
	c64dtv.c \
	c64dtv.h \
	c64dtvcia1.c \
	c64dtvcia2.c \
	c64dtviec.c \
	c64dtvmeminit.c \
	c64dtvmeminit.h \
	c64dtvmodel.c \
	c64dtvmodel.h \
	c64dtvpla.c \
	c64dtvprinter.c \
	c64dtvsound.c \
	debugcart.c \
	debugcart.h \
	flash-trap.c \
	flash-trap.h \
	hummeradc.c \
	hummeradc.h
