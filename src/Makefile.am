AUTOMAKE_OPTIONS = subdir-objects
ACLOCAL_AMFLAGS = $(ACLOCAL_FLAGS)

bin_PROGRAMS = helloWorld
helloWorld_SOURCES = main.cpp
helloWorld_LDADD = libHelloWorld.la

lib_LTLIBRARIES = libHelloWorld.la
libHelloWorld_la_LDFLAGS = -version-info 0:0:0
libHelloWorld_la_SOURCES = helloWorld.cpp helloWorld.h
