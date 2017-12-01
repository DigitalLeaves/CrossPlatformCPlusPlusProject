# Process this file with autoconf to produce a configure script.
AC_PREREQ([2.69])
AC_INIT([helloWorld], [1.0], [contact@digitalleaves.com])
AM_INIT_AUTOMAKE
AC_CONFIG_SRCDIR([src/main.cpp])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIRS([m4])

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC

# Checks for libraries.
LT_INIT
AC_ENABLE_SHARED
AC_DISABLE_STATIC
AC_PROG_LIBTOOL(libtool)

# Checks for typedefs, structures, and compiler characteristics.
AC_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_SIZE_T

# Output Makefile files.
AC_CONFIG_FILES([Makefile src/Makefile doc/Makefile examples/Makefile man/Makefile scripts/Makefile])
AC_OUTPUT

