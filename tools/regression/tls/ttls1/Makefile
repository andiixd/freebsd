# $FreeBSD$

PROG=	ttls1
LDFLAGS+= -L../libxx -lxx -Wl,--rpath=${.OBJDIR}/../libxx
LDFLAGS+= -L../libyy -lyy -Wl,--rpath=${.OBJDIR}/../libyy
NO_MAN=
DEBUG_FLAGS= -g

.include <bsd.prog.mk>
