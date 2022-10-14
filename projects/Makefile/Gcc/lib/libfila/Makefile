########################################################################
# Copyright (c) 1988-2022 $organization$
#
# This software is provided by the author and contributors ``as is''
# and any express or implied warranties, including, but not limited to,
# the implied warranties of merchantability and fitness for a particular
# purpose are disclaimed. In no event shall the author or contributors
# be liable for any direct, indirect, incidental, special, exemplary,
# or consequential damages (including, but not limited to, procurement
# of substitute goods or services; loss of use, data, or profits; or
# business interruption) however caused and on any theory of liability,
# whether in contract, strict liability, or tort (including negligence
# or otherwise) arising in any way out of the use of this software,
# even if advised of the possibility of such damage.
#
#   File: Makefile
#
# Author: $author$
#   Date: 10/14/2022
#
# generic Makefile for framework fila library libfila
########################################################################
# Depends: rostra;nadir;crono

#
# target
#
libfila_LIBTARGET = libfila.${LIBEXT}

########################################################################

#
# user c++ flags
#
libfila_USRCXXFLAGS += \
${fila_USRCXXFLAGS} \

#
# user defines
#
libfila_USRDEFINES += \
${fila_USRDEFINES} \
-DDEFAULT_LOGGING_LEVELS_ERROR \
-DXOS_LIB_FILA_VERSION_BUILD_DATE=10/14/2022 #${shell tdate} \

#
# user includes
#
libfila_USRINCLUDES += \
${fila_USRINCLUDES} \

#
# user libdirs
#
libfila_USRLIBDIRS += \
${fila_USRLIBDIRS} \

########################################################################

#
# library .c sources
#
#libfila_LIB_C_SOURCES += \
#${FILA_SRC}/xos/lib/fila/version.c \

#
# library .cc sources
#
#libfila_LIB_CC_SOURCES += \
#${FILA_SRC}/xos/lib/fila/version.cc \

#
# library .cxx sources
#
#libfila_LIB_CXX_SOURCES += \
#${FILA_SRC}/xos/lib/fila/version.cxx \

#
# library .cpp sources
#
libfila_LIB_CPP_SOURCES += \
${FILA_SRC}/xos/lib/fila/version.cpp \

#
# library .m sources
#
#libfila_LIB_M_SOURCES += \
#${FILA_SRC}/xos/lib/fila/version.m \

#
# library .mm sources
#
#libfila_LIB_MM_SOURCES += \
#${FILA_SRC}/xos/lib/fila/version.mm \


########################################################################


