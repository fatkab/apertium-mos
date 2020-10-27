AC_PREREQ(2.52)

AC_INIT([Apertium Mossi], [0.1.0], [khanna.tanmai@gmail.com], [apertium-mos], [http://wiki.apertium.org/wiki/Apertium-mos])
AM_INIT_AUTOMAKE
AC_PROG_AWK

PKG_CHECK_MODULES(APERTIUM, apertium >= 3.6.1)
PKG_CHECK_MODULES(LTTOOLBOX, lttoolbox >= 3.5.1)
PKG_CHECK_MODULES(CG3, cg3 >= 1.3.1)

AP_MKINCLUDE

AC_OUTPUT([Makefile apertium-mos.pc])
