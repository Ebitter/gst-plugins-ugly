if USE_A52DEC
A52DEC_DIR = a52dec
else
A52DEC_DIR =
endif

if USE_AMRNB
 AMRNB_DIR = amrnb
else
 AMRNB_DIR =
endif

if USE_AMRWB
 AMRWB_DIR = amrwbdec
else
 AMRWB_DIR =
endif

if USE_CDIO
CDIO_DIR = cdio
else
CDIO_DIR = 
endif

if USE_DVDREAD
 DVDREAD_DIR = dvdread
else
 DVDREAD_DIR =
endif

if USE_MPEG2DEC
MPEG2DEC_DIR = mpeg2dec
else
MPEG2DEC_DIR =
endif

if USE_SIDPLAY
SIDPLAY_DIR = sidplay
else
SIDPLAY_DIR =
endif

if USE_X264
X264_DIR=x264
else
X264_DIR=
endif

SUBDIRS = \
	$(A52DEC_DIR) \
	$(AMRNB_DIR) \
	$(AMRWB_DIR) \
	$(CDIO_DIR) \
	$(DVDREAD_DIR) \
	$(MPEG2DEC_DIR) \
	$(SIDPLAY_DIR) \
	$(X264_DIR)

DIST_SUBDIRS = \
	a52dec \
	amrnb \
	amrwbdec \
	cdio \
	dvdread \
	mpeg2dec \
	sidplay \
	x264

include $(top_srcdir)/common/parallel-subdirs.mak
