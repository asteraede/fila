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
# generic Makefile for framework fila executable fila
########################################################################
# Depends: rostra;nadir;crono

#
# target
#
fila_exe_EXETARGET = fila

########################################################################

#
# user c++ flags
#
fila_exe_USRCXXFLAGS += \
${fila_USRCXXFLAGS} \

#
# user defines
#
fila_exe_USRDEFINES += \
${fila_USRDEFINES} \
-DDEFAULT_LOGGING_LEVELS_ERROR \
-DXOS_CONSOLE_MAIN_MAIN \

#
# user includes
#
fila_exe_USRINCLUDES += \
${fila_USRINCLUDES} \

#
# user libdirs
#
fila_exe_USRLIBDIRS += \
${fila_USRLIBDIRS} \

########################################################################

#
# executable .c sources
#
#fila_exe_EXE_C_SOURCES += \
#${FILA_SRC}/xos/app/console/fila/main.c \

#
# executable .cc sources
#
#fila_exe_EXE_CC_SOURCES += \
#${FILA_SRC}/xos/app/console/fila/main.cc \

#
# executable .cxx sources
#
#fila_exe_EXE_CXX_SOURCES += \
#${FILA_SRC}/xos/app/console/fila/main.cxx \

#
# executable .cpp sources
#
fila_exe_EXE_CPP_SOURCES += \
${FILA_SRC}/xos/app/console/fila/main_opt.cpp \
${FILA_SRC}/xos/app/console/fila/main.cpp \

#
# executable .m sources
#
#fila_exe_EXE_M_SOURCES += \
#${FILA_SRC}/xos/app/console/fila/main.m \

#
# executable .mm sources
#
#fila_exe_EXE_MM_SOURCES += \
#${FILA_SRC}/xos/app/console/fila/main.mm \


########################################################################

#
# executable libraries
#
fila_exe_LIBS += \
${fila_LIBS}

