#
# $FreeBSD: head/en_US.ISO8859-1/articles/committers-guide/Makefile 51414 2018-02-11 19:52:22Z wblock $
#
# Article: The FreeBSD Committers Guide

DOC?= article

FORMATS?= html
WITH_ARTICLE_TOC?= YES

INSTALL_COMPRESSED?= gz
INSTALL_ONLY_COMPRESSED?=

SRCS=	article.xml

IMAGES_LIB=	callouts/1.png
IMAGES_LIB+=	callouts/2.png
IMAGES_LIB+=	callouts/3.png
IMAGES_LIB+=	callouts/4.png
IMAGES_LIB+=	callouts/5.png
IMAGES_LIB+=	callouts/6.png

URL_RELPREFIX?=	../../../..
DOC_PREFIX?=	${.CURDIR}/../../..

.include "${DOC_PREFIX}/share/mk/doc.project.mk"
