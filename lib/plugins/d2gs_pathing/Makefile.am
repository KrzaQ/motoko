libdir = @libdir@/@PACKAGE@/plugins
lib_LTLIBRARIES = libd2gs_pathing_plugin.la
libd2gs_pathing_plugin_la_SOURCES = d2gs_pathing.c exits.h levels.h mazes.h
libd2gs_pathing_plugin_la_CFLAGS = -g -fvisibility=hidden -m32 -Wall
libd2gs_pathing_plugin_la_CPPFLAGS = -I$(top_srcdir)/src -I$(top_srcdir)/lib/util/include
libd2gs_pathing_plugin_la_LDFLAGS = -release 0.1.0
LDADD = -lpthread -lrt -lm
