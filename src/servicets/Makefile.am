AM_CPPFLAGS = \
	@PYTHON_CPPFLAGS@ \
	-include Python.h

AM_CXXFLAGS = \
	-Wall \
	-fno-exceptions \
	@ENIGMA2_CFLAGS@ \
	@PTHREAD_CFLAGS@

plugindir = $(libdir)/enigma2/python/Plugins/Extensions/VlcPlayer

plugin_LTLIBRARIES = servicets.la

servicets_la_SOURCES = \
	servicets.cpp \
	servicets.h

servicets_la_LDFLAGS = \
	-avoid-version \
	-module \
	-shared
