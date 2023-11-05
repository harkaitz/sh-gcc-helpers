PROJECT=sh-gcc-helpers
VERSION=1.0.0
PREFIX=/usr/local
all:
clean:
install:

## -- BLOCK:license --
install: install-license
install-license: 
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp LICENSE  $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/gcc-h-wrap       $(DESTDIR)$(PREFIX)/bin
	cp bin/gcc-h-test-code  $(DESTDIR)$(PREFIX)/bin
	cp bin/gcc-h-query      $(DESTDIR)$(PREFIX)/bin
	cp bin/gcc-h-test-cross $(DESTDIR)$(PREFIX)/bin
	cp bin/gcc-h-flycheck   $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
