AM_CPPFLAGS = -DSYSCONFDIR=\"${sysconfdir}\" -DLOCALSTATEDIR=\"${localstatedir}\" 
CFLAGS += -W -Wall -Wno-unused-parameter -fno-strict-aliasing -I. -I../src -I../include

lib_LIBRARIES = librlog.a

librlog_a_SOURCES = librlog.c common.c
librlog_a_CFLAGS = $(EV_CPPFLAGS)

MAINTAINERCLEANFILES = Makefile.in
