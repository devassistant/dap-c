#This line defines the name of the output tarball
AC_INIT([CDevelopmentTool],[0.0])
dnl
AC_CONFIG_AUX_DIR([build-aux])
dnl
#this line defines what compilation flags will be used
AM_INIT_AUTOMAKE([subdir-objects -Wall])
dnl
# DEFINE YOUR OWN HEADERS CHECK - DO NOT DELETE THIS LINE
#this line defines what libraries should be used during building
AC_CHECK_LIB([pthread],[pthread_create])
AC_CHECK_LIB([pthread],[pthread_join])
dnl
# DEFINE YOUR OWN LIBRARY CHECK - DO NOT DELETE THIS LINE
AC_PROG_CC
dnl
AC_CONFIG_MACRO_DIR([m4])
dnl
#This line defines where Makefiles are stored for projects and sources
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
