#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([ming_fw], [1.0], [])
AC_CONFIG_SRCDIR([src/main.cpp])
#AC_CONFIG_HEADERS([config.h])
AM_INIT_AUTOMAKE
# Checks for programs.
AC_PROG_CXX
AC_PROG_CC

# Checks for libraries.
AC_PROG_RANLIB
# Checks for libraries. -DBOOST_ASIO_ENABLE_HANDLER_TRACKING
# CXXFLAGS="-std=c++14 -pg -O0 -Isrc -Iinclude -I/usr/include/apr-1 -I/usr/include/c++/5.1.0 -I/usr/include/c++ -Werror -Wno-deprecated-declarations -lboost_program_options -lboost_filesystem -lboost_coroutine -lboost_system -lboost_thread -lpthread -lboost_context -lboost_date_time -lboost_log_setup -lboost_log -lssl -lcrypto -lboost_regex -lcurl -lboost_timer -DBUILD_SSL -lboost_signals -lboost_locale"
CXXFLAGS="-std=c++14 -O2 -Isrc -Iinclude -Isrc/include -Isrc/example -I/usr/include/apr-1 -I/usr/include/c++/5.1.0 -I/usr/include/c++ -I/usr/local/include -I/usr/local/include/cppconn -Werror -Wno-deprecated-declarations -lboost_program_options -lboost_filesystem -lboost_coroutine -lboost_system -lboost_thread -lpthread -lboost_context -lboost_date_time -lboost_log_setup -lboost_log -lssl -lcrypto -lboost_regex -lcurl -lboost_timer -DBUILD_SSL -lboost_signals -lboost_locale -lmysqlcppconn"
SUBDIRS = src src/include
# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_SIZE_T

# Checks for library functions.
AC_CHECK_FUNCS([socket])
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
