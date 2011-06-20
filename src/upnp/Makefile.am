AM_CFLAGS = -I$(top_srcdir) $(HOST_CXXFLAGS) $(DEBUG_CXXFLAGS)

noinst_LIBRARIES = libupnpc.a

libupnpc_a_SOURCES = connecthostport.c igd_desc_parse.c minisoap.c	\
                     miniupnpc.c miniwget.c minixml.c			\
                     portlistingparse.c receivedata.c upnpcommands.c	\
                     upnperrors.c upnpreplyparse.c minissdpc.c

libupnpc_a_CPPFLAGS = $(GLOBAL_CPPFLAGS) $(HOST_CPPFLAGS) $(DEBUG_CPPFLAGS) 

noinst_HEADERS = connecthostport.h igd_desc_parse.h minissdpc.h		\
                 miniupnpctypes.h minixml.h receivedata.h upnperrors.h	\
                 declspec.h minisoap.h miniupnpc.h miniwget.h		\
                 portlistingparse.h upnpcommands.h upnpreplyparse.h	\
                 codelength.h

