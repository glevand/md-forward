## configure.ac -- Process this file with autoconf to produce configure

AC_INIT([md-forward],
    [m4_esyscmd_s([./version.sh])],
    [Geoff Levand <geoff@infradead.org>],
    [md-forward],
    [https://github.com/glevand/md-forward])

AC_USE_SYSTEM_EXTENSIONS
AC_CONFIG_MACRO_DIR([m4])
AC_PREFIX_DEFAULT([/usr/local])
AC_PROG_INSTALL

AM_INIT_AUTOMAKE
AC_GNU_SOURCE

AM_SILENT_RULES([yes])

AC_SUBST([DESTDIR])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([Makefile])

AC_OUTPUT
