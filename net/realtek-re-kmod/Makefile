# Created by: Alex Dupre <ale@FreeBSD.org>

PORTNAME=	re
DISTVERSION=	v196.04
PORTREVISION=	4
CATEGORIES=	net
MASTER_SITES=	LOCAL/ale
PKGNAMEPREFIX=	realtek-
PKGNAMESUFFIX=	-kmod
DISTNAME=	rtl_bsd_drv_${DISTVERSION}

MAINTAINER=	ale@FreeBSD.org
COMMENT=	Kernel driver for Realtek PCIe Ethernet Controllers

LICENSE=	BSD4CLAUSE

USES=		kmod tar:tgz uidfix

PLIST_FILES=	${KMODDIR}/if_re.ko

.include <bsd.port.mk>
