.POSIX:
.SUFFIXES:
.PHONY: all clean install check
all:
PROJECT=clipzip
VERSION=1.0.0
PREFIX=/usr/local

all:
clean:
install:
check:
## -- BLOCK:license --
install: install-license
install-license: 
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp COPYING $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/clipzip          $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
