bin_PROGRAMS = scuff-avescatter

scuff_avescatter_SOURCES = 		\
 scuff-avescatter.cc         	\
 scuff-avescatter.h		\
 NeqScattering.cc        	\
 CreateSNEQData.cc

scuff_avescatter_LDADD = $(top_builddir)/libs/libscuff/libscuff.la

AM_CPPFLAGS = -I$(top_srcdir)/libs/libscuff      \
              -I$(top_srcdir)/libs/libIncField   \
              -I$(top_srcdir)/libs/libMatProp    \
              -I$(top_srcdir)/libs/libMDInterp   \
              -I$(top_srcdir)/libs/libhmat       \
              -I$(top_srcdir)/libs/libSGJC       \
              -I$(top_srcdir)/libs/libSubstrate  \
              -I$(top_srcdir)/libs/libTriInt     \
              -I$(top_srcdir)/libs/libhrutil
