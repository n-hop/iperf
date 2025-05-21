noinst_PROGRAMS		= mic mis iperf_bats_client iperf_bats_server		# Build, but don't install

AM_CPPFLAGS		= -I$(top_srcdir)/src

mic_SOURCES		= mic.c
mic_CFLAGS		= -g
mic_LDADD		= ../src/libiperf.la
mic_LDFLAGS		= -g

mis_SOURCES		= mis.c
mis_CFLAGS		= -g
mis_LDADD		= ../src/libiperf.la
mis_LDFLAGS		= -g


iperf_bats_client_SOURCES	= iperf_bats_client.c
iperf_bats_client_CFLAGS	= -g
iperf_bats_client_LDADD		= ../src/libiperf.la
iperf_bats_client_LDFLAGS	= -g

iperf_bats_server_SOURCES	= iperf_bats_server.c
iperf_bats_server_CFLAGS	= -g
iperf_bats_server_LDADD		= ../src/libiperf.la
iperf_bats_server_LDFLAGS	= -g
