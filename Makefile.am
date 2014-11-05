
ACLOCAL_AMFLAGS = -I m4

SUBDIRS = 				\
	libasn1parser libasn1fix	\
	libasn1print libasn1compiler	\
	skeletons examples \
	doc asn1c

docsdir = $(datadir)/doc/asn1c
pkgconfigdir = $(libdir)/pkgconfig

docs_DATA = README.md FAQ COPYING ChangeLog BUGS TODO
pkgconfig_DATA = asn1c.pc

EXTRA_DIST = asn1c.spec.in asn1c.pc.in README.md FAQ BUGS MANIFEST tests/
CLEANFILES = asn1c.spec
