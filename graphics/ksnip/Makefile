PORTNAME=	ksnip
DISTVERSIONPREFIX=	v
DISTVERSION=	1.9.0
PORTREVISION=	1
CATEGORIES=	graphics kde

MAINTAINER=	kde@FreeBSD.org
COMMENT=	Screenshot and annotation tool

LICENSE=	GPLv2
LICENSE_FILE=	${WRKSRC}/LICENSE.txt

LIB_DEPENDS=	libkColorPicker.so:graphics/kcolorpicker \
		libkImageAnnotator.so:graphics/kimageannotator

USES=		cmake compiler:c++11-lang kde:5 qt:5 xorg
USE_GITHUB=	yes
USE_KDE=	ecm_build
USE_QT=		concurrent core dbus gui network printsupport svg testlib \
		widgets x11extras xml \
		buildtools_build linguisttools_build qmake_build
USE_XORG=	x11 xcb

PORTSCOUT=	limit:^[0-9]

.include <bsd.port.mk>
