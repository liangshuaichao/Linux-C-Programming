#############################################################################
# Makefile for building: client
# Generated by qmake (2.01a) (Qt 4.4.0) on: ?? ?? 25 11:18:12 2008
# Project:  client.pro
# Template: app
# Command: /usr/bin/qmake -unix -o Makefile client.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DQT_NO_DEBUG -DQT_GUI_LIB -DQT_NETWORK_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -O2 -Wall -W -D_REENTRANT $(DEFINES)
CXXFLAGS      = -pipe -O2 -Wall -W -D_REENTRANT $(DEFINES)
INCPATH       = -I/usr/share/qt4/mkspecs/linux-g++ -I. -I/usr/include/qt4/QtCore -I/usr/include/qt4/QtCore -I/usr/include/qt4/QtNetwork -I/usr/include/qt4/QtNetwork -I/usr/include/qt4/QtGui -I/usr/include/qt4/QtGui -I/usr/include/qt4 -I. -I. -I.
LINK          = g++
LFLAGS        = -Wl,--no-undefined
LIBS          = $(SUBLIBS)  -L/usr/lib -lQtGui -lQtNetwork -lQtCore -lpthread
AR            = ar cqs
RANLIB        = 
QMAKE         = /usr/bin/qmake
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -sf
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = ./

####### Files

SOURCES       = chat.cpp \
		login.cpp \
		main.cpp \
		privchat.cpp moc_chat.cpp \
		moc_login.cpp \
		moc_privchat.cpp
OBJECTS       = chat.o \
		login.o \
		main.o \
		privchat.o \
		moc_chat.o \
		moc_login.o \
		moc_privchat.o
DIST          = /usr/share/qt4/mkspecs/common/g++.conf \
		/usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		client.pro
QMAKE_TARGET  = client
DESTDIR       = 
TARGET        = client

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

$(TARGET): ui_chat.h ui_login.h ui_privchat.h $(OBJECTS)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: client.pro  /usr/share/qt4/mkspecs/linux-g++/qmake.conf /usr/share/qt4/mkspecs/common/g++.conf \
		/usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/lib/libQtGui.prl \
		/usr/lib/libQtNetwork.prl \
		/usr/lib/libQtCore.prl
	$(QMAKE) -unix -o Makefile client.pro
/usr/share/qt4/mkspecs/common/g++.conf:
/usr/share/qt4/mkspecs/common/unix.conf:
/usr/share/qt4/mkspecs/common/linux.conf:
/usr/share/qt4/mkspecs/qconfig.pri:
/usr/share/qt4/mkspecs/features/qt_functions.prf:
/usr/share/qt4/mkspecs/features/qt_config.prf:
/usr/share/qt4/mkspecs/features/exclusive_builds.prf:
/usr/share/qt4/mkspecs/features/default_pre.prf:
/usr/share/qt4/mkspecs/features/release.prf:
/usr/share/qt4/mkspecs/features/default_post.prf:
/usr/share/qt4/mkspecs/features/warn_on.prf:
/usr/share/qt4/mkspecs/features/qt.prf:
/usr/share/qt4/mkspecs/features/unix/thread.prf:
/usr/share/qt4/mkspecs/features/moc.prf:
/usr/share/qt4/mkspecs/features/resources.prf:
/usr/share/qt4/mkspecs/features/uic.prf:
/usr/share/qt4/mkspecs/features/yacc.prf:
/usr/share/qt4/mkspecs/features/lex.prf:
/usr/lib/libQtGui.prl:
/usr/lib/libQtNetwork.prl:
/usr/lib/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -unix -o Makefile client.pro

dist: 
	@$(CHK_DIR_EXISTS) .tmp/client1.0.0 || $(MKDIR) .tmp/client1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .tmp/client1.0.0/ && $(COPY_FILE) --parents chat.h login.h privchat.h .tmp/client1.0.0/ && $(COPY_FILE) --parents chat.cpp login.cpp main.cpp privchat.cpp .tmp/client1.0.0/ && $(COPY_FILE) --parents chat.ui login.ui privchat.ui .tmp/client1.0.0/ && (cd `dirname .tmp/client1.0.0` && $(TAR) client1.0.0.tar client1.0.0 && $(COMPRESS) client1.0.0.tar) && $(MOVE) `dirname .tmp/client1.0.0`/client1.0.0.tar.gz . && $(DEL_FILE) -r .tmp/client1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all: moc_chat.cpp moc_login.cpp moc_privchat.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) moc_chat.cpp moc_login.cpp moc_privchat.cpp
moc_chat.cpp: ui_chat.h \
		privchat.h \
		ui_privchat.h \
		chat.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) chat.h -o moc_chat.cpp

moc_login.cpp: ui_login.h \
		login.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) login.h -o moc_login.cpp

moc_privchat.cpp: ui_privchat.h \
		privchat.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) privchat.h -o moc_privchat.cpp

compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all: ui_chat.h ui_login.h ui_privchat.h
compiler_uic_clean:
	-$(DEL_FILE) ui_chat.h ui_login.h ui_privchat.h
ui_chat.h: chat.ui
	/usr/bin/uic-qt4 chat.ui -o ui_chat.h

ui_login.h: login.ui
	/usr/bin/uic-qt4 login.ui -o ui_login.h

ui_privchat.h: privchat.ui
	/usr/bin/uic-qt4 privchat.ui -o ui_privchat.h

compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean compiler_uic_clean 

####### Compile

chat.o: chat.cpp chat.h \
		ui_chat.h \
		privchat.h \
		ui_privchat.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o chat.o chat.cpp

login.o: login.cpp login.h \
		ui_login.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o login.o login.cpp

main.o: main.cpp login.h \
		ui_login.h \
		chat.h \
		ui_chat.h \
		privchat.h \
		ui_privchat.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o main.o main.cpp

privchat.o: privchat.cpp privchat.h \
		ui_privchat.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o privchat.o privchat.cpp

moc_chat.o: moc_chat.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_chat.o moc_chat.cpp

moc_login.o: moc_login.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_login.o moc_login.cpp

moc_privchat.o: moc_privchat.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_privchat.o moc_privchat.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

