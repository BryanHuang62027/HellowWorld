#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

#AC_PREREQ([2.68])
AC_INIT([HellowWorld],[1.0.2],[icpdas])
AC_CONFIG_AUX_DIR([autoconf])
AC_PREFIX_DEFAULT([/opt/xxx])
#AC_CONFIG_SRCDIR([proc/main.c])
AC_CONFIG_HEADERS([config.h])
AM_INIT_AUTOMAKE([-Wall -Werror])
AC_CONFIG_MACRO_DIR([m4])

# Checks for programs.
AC_PROG_CC
AC_PROG_CXX
AM_PROG_CC_C_O
AM_PROG_AR

# Checks for libraries.
#LT_PREREQ([xx])
LT_INIT
#LT_INIT([disable-shared])

# Checks for header files.
AC_CHECK_HEADERS([stdlib.h])


# Checks for library functions.


#------------------------------------------------------------------------------
# AC_ARG_WITH & AM_CONDITIONAL sample
#------------------------------------------------------------------------------



#------------------

AC_CONFIG_FILES([Makefile
		bin/Makefile])
AC_OUTPUT
