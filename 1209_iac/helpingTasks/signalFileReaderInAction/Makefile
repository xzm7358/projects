#############################################################################
# Makefile for building: bin/signalFileReaderInAction
# Generated by qmake (2.01a) (Qt 4.8.3) on: Thu Jun 6 10:46:14 2013
# Project:  signalFileReaderInAction.pro
# Template: app
# Command: /usr/bin/qmake -o Makefile signalFileReaderInAction.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DQT_WEBKIT -DQT_DLL -DQWT_DLL -DQT_DEBUG -DQT_NO_DEBUG -DQT_SVG_LIB -DQT_GUI_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -O2 -Wall -W -D_REENTRANT $(DEFINES)
CXXFLAGS      = -pipe -w -O2 -Wall -W -D_REENTRANT $(DEFINES)
INCPATH       = -I/usr/share/qt4/mkspecs/linux-g++ -I. -I/usr/include/qt4/QtCore -I/usr/include/qt4/QtGui -I/usr/include/qt4/QtSvg -I/usr/include/qt4 -I/usr/include/qt4/qwt -I/usr/include/qwt -Isrc -Irelease/moc -Irelease/ui
LINK          = g++
LFLAGS        = -Wl,-O1
LIBS          = $(SUBLIBS)  -L/usr/lib/i386-linux-gnu -L/usr/lib -lqwt -lQtSvg -lQtGui -lQtCore -lpthread 
AR            = ar cqs
RANLIB        = 
QMAKE         = /usr/bin/qmake
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = strip
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = release/obj/

####### Files

SOURCES       = main.cpp \
		mainWindow.cpp \
		../signalFileReader/signalFileReader.cpp release/moc/moc_mainWindow.cpp
OBJECTS       = release/obj/main.o \
		release/obj/mainWindow.o \
		release/obj/signalFileReader.o \
		release/obj/moc_mainWindow.o
DIST          = /usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/common/gcc-base.conf \
		/usr/share/qt4/mkspecs/common/gcc-base-unix.conf \
		/usr/share/qt4/mkspecs/common/g++-base.conf \
		/usr/share/qt4/mkspecs/common/g++-unix.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		signalFileReaderInAction.pro
QMAKE_TARGET  = signalFileReaderInAction
DESTDIR       = bin/
TARGET        = bin/signalFileReaderInAction

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile $(TARGET)

$(TARGET): release/ui/ui_mainWindow.h $(OBJECTS)  
	@$(CHK_DIR_EXISTS) bin/ || $(MKDIR) bin/ 
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: signalFileReaderInAction.pro  /usr/share/qt4/mkspecs/linux-g++/qmake.conf /usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/common/gcc-base.conf \
		/usr/share/qt4/mkspecs/common/gcc-base-unix.conf \
		/usr/share/qt4/mkspecs/common/g++-base.conf \
		/usr/share/qt4/mkspecs/common/g++-unix.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/lib/i386-linux-gnu/libQtSvg.prl \
		/usr/lib/i386-linux-gnu/libQtGui.prl \
		/usr/lib/i386-linux-gnu/libQtCore.prl
	$(QMAKE) -o Makefile signalFileReaderInAction.pro
/usr/share/qt4/mkspecs/common/unix.conf:
/usr/share/qt4/mkspecs/common/linux.conf:
/usr/share/qt4/mkspecs/common/gcc-base.conf:
/usr/share/qt4/mkspecs/common/gcc-base-unix.conf:
/usr/share/qt4/mkspecs/common/g++-base.conf:
/usr/share/qt4/mkspecs/common/g++-unix.conf:
/usr/share/qt4/mkspecs/qconfig.pri:
/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri:
/usr/share/qt4/mkspecs/features/qt_functions.prf:
/usr/share/qt4/mkspecs/features/qt_config.prf:
/usr/share/qt4/mkspecs/features/exclusive_builds.prf:
/usr/share/qt4/mkspecs/features/default_pre.prf:
/usr/share/qt4/mkspecs/features/release.prf:
/usr/share/qt4/mkspecs/features/default_post.prf:
/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf:
/usr/share/qt4/mkspecs/features/warn_on.prf:
/usr/share/qt4/mkspecs/features/qt.prf:
/usr/share/qt4/mkspecs/features/unix/thread.prf:
/usr/share/qt4/mkspecs/features/moc.prf:
/usr/share/qt4/mkspecs/features/resources.prf:
/usr/share/qt4/mkspecs/features/uic.prf:
/usr/share/qt4/mkspecs/features/yacc.prf:
/usr/share/qt4/mkspecs/features/lex.prf:
/usr/lib/i386-linux-gnu/libQtSvg.prl:
/usr/lib/i386-linux-gnu/libQtGui.prl:
/usr/lib/i386-linux-gnu/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -o Makefile signalFileReaderInAction.pro

dist: 
	@$(CHK_DIR_EXISTS) release/obj/signalFileReaderInAction1.0.0 || $(MKDIR) release/obj/signalFileReaderInAction1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) release/obj/signalFileReaderInAction1.0.0/ && $(COPY_FILE) --parents mainWindow.h ../signalFileReader/signalFileReader.h release/obj/signalFileReaderInAction1.0.0/ && $(COPY_FILE) --parents main.cpp mainWindow.cpp ../signalFileReader/signalFileReader.cpp release/obj/signalFileReaderInAction1.0.0/ && $(COPY_FILE) --parents mainWindow.ui release/obj/signalFileReaderInAction1.0.0/ && (cd `dirname release/obj/signalFileReaderInAction1.0.0` && $(TAR) signalFileReaderInAction1.0.0.tar signalFileReaderInAction1.0.0 && $(COMPRESS) signalFileReaderInAction1.0.0.tar) && $(MOVE) `dirname release/obj/signalFileReaderInAction1.0.0`/signalFileReaderInAction1.0.0.tar.gz . && $(DEL_FILE) -r release/obj/signalFileReaderInAction1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


check: first

mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all: release/moc/moc_mainWindow.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) release/moc/moc_mainWindow.cpp
release/moc/moc_mainWindow.cpp: release/ui/ui_mainWindow.h \
		../signalFileReader/signalFileReader.h \
		../signalFileReader/containers/arrays.h \
		mainWindow.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) mainWindow.h -o release/moc/moc_mainWindow.cpp

compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: release/ui/qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) release/ui/qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all: release/ui/ui_mainWindow.h
compiler_uic_clean:
	-$(DEL_FILE) release/ui/ui_mainWindow.h
release/ui/ui_mainWindow.h: mainWindow.ui
	/usr/bin/uic-qt4 mainWindow.ui -o release/ui/ui_mainWindow.h

compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean compiler_uic_clean 

####### Compile

release/obj/main.o: main.cpp mainWindow.h \
		release/ui/ui_mainWindow.h \
		../signalFileReader/signalFileReader.h \
		../signalFileReader/containers/arrays.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o release/obj/main.o main.cpp

release/obj/mainWindow.o: mainWindow.cpp mainWindow.h \
		release/ui/ui_mainWindow.h \
		../signalFileReader/signalFileReader.h \
		../signalFileReader/containers/arrays.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o release/obj/mainWindow.o mainWindow.cpp

release/obj/signalFileReader.o: ../signalFileReader/signalFileReader.cpp ../signalFileReader/signalFileReader.h \
		../signalFileReader/containers/arrays.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o release/obj/signalFileReader.o ../signalFileReader/signalFileReader.cpp

release/obj/moc_mainWindow.o: release/moc/moc_mainWindow.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o release/obj/moc_mainWindow.o release/moc/moc_mainWindow.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

