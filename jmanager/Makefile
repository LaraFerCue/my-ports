# $FreeBSD$

PORTNAME=	jmanager
DISTVERSION=	0.1a
CATEGORIES=	sysutils python

MAINTAINER=	larafercue@gmail.com
COMMENT=	A python based jail manager with ansible integration

USE_GITHUB=	yes
GH_ACCOUNT=	LaraFerCue
GH_TAGNAME=	5931441

USES=		python:-3.6
USE_PYTHON=	distutils autoplist

RUN_DEPENDS=	ansible-3.6:sysutils/ansible \
		${PYTHON_SITELIBDIR}/yaml:devel/py-yaml \
		${PYTHON_SITELIBDIR}/paramiko:security/paramiko

.include <bsd.port.mk>
