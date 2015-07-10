AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic
include_HEADERS = helloworld.h

lib_LTLIBRARIES = libhelloworld.la
libhelloworld_la_SOURCES  = helloworldlib.c
libhelloworld_la_LDFLAGS= -version-info 1:0:0

bin_PROGRAMS = helloworld
helloworld_SOURCES = helloworld.c
helloworld_LDADD = .libs/libhelloworld.la
