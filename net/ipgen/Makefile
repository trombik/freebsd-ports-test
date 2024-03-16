PORTNAME=	ipgen
DISTVERSION=	1.29
CATEGORIES=	net

MAINTAINER=	y@trombik.org
COMMENT=	Packet traffic generator that uses netmap or XDP
WWW=		https://github.com/iij/ipgen

LICENSE=	MIT

LIB_DEPENDS=	libevent.so:devel/libevent

USES=	gmake perl5
USE_GITHUB=	yes
GH_TUPLE=	iij:ipgen:v${DISTVERSION}

MAKEFILE=	GNUmakefile
ALL_TARGET=	depend all

.include <bsd.port.mk>
