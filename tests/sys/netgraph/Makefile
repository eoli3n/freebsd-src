# $FreeBSD$

PACKAGE=	tests

TESTSDIR=	${TESTSBASE}/sys/netgraph
BINDIR=		${TESTSDIR}

TAP_TESTS_SH+=	ng_macfilter_test

TEST_METADATA.ng_macfilter_test+=	required_user="root"
TEST_METADATA.ng_macfilter_test+=	required_programs="perl"

ATF_TESTS_C+=	basic	\

SRCS.basic=	basic.c util.c

LIBADD+=	netgraph

.include <bsd.test.mk>
