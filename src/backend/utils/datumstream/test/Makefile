subdir=src/backend/utils/datumstream
top_builddir=../../../../..
include $(top_builddir)/src/Makefile.global

TARGETS=datumstreamblock

include $(top_srcdir)/src/backend/mock.mk

datumstreamblock.t: \
	$(MOCK_DIR)/backend/access/hash/hash_mock.o \
	$(MOCK_DIR)/backend/utils/fmgr/fmgr_mock.o
