# Joe Maloney <jmaloney@ixsystems.com>
# $FreeBSD$

PORTNAME=	trueos-server
PORTVERSION=	%%CHGVERSION%%
CATEGORIES=	misc
MASTER_SITES=
DISTFILES=

MAINTAINER=	jmaloney@ixsystems.com
COMMENT=	TrueOS Server

RUN_DEPENDS=	${LOCALBASE}/bin/pc-updatemanager:sysutils/pc-updatemanager \
		${LOCALBASE}/sbin/pc-sysinstall:sysutils/pc-sysinstall \
		${LOCALBASE}/bin/pc-su:sysutils/pcbsd-utils \
		${LOCALBASE}/share/pcbsd/scripts/functions.sh:sysutils/trueos-libsh \
		${LOCALBASE}/bin/lpreserver:sysutils/life-preserver \
		${LOCALBASE}/sbin/beadm:sysutils/beadm \
		${LOCALBASE}/bin/sudo:security/sudo \
		${LOCALBASE}/bin/bash:shells/bash \
		${LOCALBASE}/bin/zsh:shells/zsh \
		${LOCALBASE}/bin/rsync:net/rsync \
		${LOCALBASE}/bin/screen:sysutils/screen \
		${LOCALBASE}/bin/tmux:sysutils/tmux \
		${LOCALBASE}/bin/nano:editors/nano \
		${LOCALBASE}/bin/zfs-stats:sysutils/zfs-stats \
		ataidle>=0:sysutils/ataidle \
		openntpd>=0:net/openntpd

CONFLICTS=      pcbsd-utils*

NO_BUILD=	yes

do-install:
	${DO_NADA}

USE_GITHUB=     yes
GH_ACCOUNT=     trueos
GH_PROJECT=     trueos-server
GH_TAGNAME=     %%GHTAG%%

.include <bsd.port.mk>
