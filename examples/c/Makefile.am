
LIBVTC_CFLAGS = -g3 -I../../lib -Wall
LIBVTC_LDLAGS = -L../../lib -lcvtapi ${JANSSON_LIBS}

noinst_bin_PROGRAMS = scan url url_dist ip_report domain_report comments search file_dist
noinst_bindir = $(abs_top_builddir)/example_progs

scan_SOURCES = scan.c
scan_CFLAGS = $(AM_CFLAGS) $(LIBVTC_CFLAGS)
scan_LDFLAGS = $(LIBVTC_LDLAGS) 

url_SOURCES = url.c
url_CFLAGS = $(AM_CFLAGS) $(LIBVTC_CFLAGS)
url_LDFLAGS = $(LIBVTC_LDLAGS)

file_dist_SOURCES = file_dist.c
file_dist_CFLAGS = $(AM_CFLAGS) $(LIBVTC_CFLAGS)
file_dist_LDFLAGS = $(LIBVTC_LDLAGS)

url_dist_SOURCES = url_dist.c
url_dist_CFLAGS = $(AM_CFLAGS) $(LIBVTC_CFLAGS)
url_dist_LDFLAGS = $(LIBVTC_LDLAGS)

ip_report_SOURCES = ip.c
ip_report_CFLAGS = $(AM_CFLAGS) $(LIBVTC_CFLAGS)
ip_report_LDFLAGS = $(LIBVTC_LDLAGS)

domain_report_SOURCES = domain_report.c
domain_report_CFLAGS = $(AM_CFLAGS) $(LIBVTC_CFLAGS)
domain_report_LDFLAGS = $(LIBVTC_LDLAGS)

comments_SOURCES = comments.c
comments_CFLAGS = $(AM_CFLAGS) $(LIBVTC_CFLAGS)
comments_LDFLAGS = $(LIBVTC_LDLAGS)

search_SOURCES = search.c
search_CFLAGS = $(AM_CFLAGS) $(LIBVTC_CFLAGS)
search_LDFLAGS = $(LIBVTC_LDLAGS)
