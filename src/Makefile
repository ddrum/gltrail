#############################################################################
# Makefile for building: ../bin/gltrail
# Generated by qmake (2.01a) (Qt 4.3.2) on: Mon Mar 17 15:20:17 2008
# Project:  src.pro
# Template: app
# Command: /usr/bin/qmake -unix -o Makefile src.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DQT_SHARED -DQT_OPENGL_LIB -DQT_GUI_LIB -DQT_NETWORK_LIB -DQT_CORE_LIB
CFLAGS        = -pipe -g -D_REENTRANT -Wall -W $(DEFINES)
CXXFLAGS      = -pipe -g -D_REENTRANT -Wall -W $(DEFINES)
INCPATH       = -I/usr/share/qt4/mkspecs/linux-g++ -I. -I/usr/include/qt4/QtCore -I/usr/include/qt4/QtCore -I/usr/include/qt4/QtNetwork -I/usr/include/qt4/QtNetwork -I/usr/include/qt4/QtGui -I/usr/include/qt4/QtGui -I/usr/include/qt4/QtOpenGL -I/usr/include/qt4/QtOpenGL -I/usr/include/qt4 -I/usr/X11R6/include -I. -I.
LINK          = g++
LFLAGS        = 
LIBS          = $(SUBLIBS)  -L/usr/lib -L/usr/X11R6/lib -lQtOpenGL -lQtGui -lQtNetwork -lQtCore -lGLU -lGL -lpthread
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

SOURCES       = main.cpp \
		activity.cpp \
		element.cpp \
		textured_element.cpp \
		window.cpp \
		glwidget.cpp \
		background_updater.cpp \
		input.cpp \
		inputs/ssh.cpp \
		inputs/digg.cpp \
		inputs/twitter.cpp moc_window.cpp \
		moc_glwidget.cpp \
		moc_background_updater.cpp \
		moc_ssh.cpp \
		moc_digg.cpp \
		moc_twitter.cpp
OBJECTS       = main.o \
		activity.o \
		element.o \
		textured_element.o \
		window.o \
		glwidget.o \
		background_updater.o \
		input.o \
		ssh.o \
		digg.o \
		twitter.o \
		moc_window.o \
		moc_glwidget.o \
		moc_background_updater.o \
		moc_ssh.o \
		moc_digg.o \
		moc_twitter.o
DIST          = /usr/share/qt4/mkspecs/common/g++.conf \
		/usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/debug.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/opengl.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		src.pro
QMAKE_TARGET  = gltrail
DESTDIR       = ../bin/
TARGET        = ../bin/gltrail

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

$(TARGET):  $(OBJECTS)  
	@$(CHK_DIR_EXISTS) ../bin/ || $(MKDIR) ../bin/ 
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: src.pro  /usr/share/qt4/mkspecs/linux-g++/qmake.conf /usr/share/qt4/mkspecs/common/g++.conf \
		/usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/debug.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/opengl.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf
	$(QMAKE) -unix -o Makefile src.pro
/usr/share/qt4/mkspecs/common/g++.conf:
/usr/share/qt4/mkspecs/common/unix.conf:
/usr/share/qt4/mkspecs/common/linux.conf:
/usr/share/qt4/mkspecs/qconfig.pri:
/usr/share/qt4/mkspecs/features/qt_functions.prf:
/usr/share/qt4/mkspecs/features/qt_config.prf:
/usr/share/qt4/mkspecs/features/exclusive_builds.prf:
/usr/share/qt4/mkspecs/features/default_pre.prf:
/usr/share/qt4/mkspecs/features/debug.prf:
/usr/share/qt4/mkspecs/features/default_post.prf:
/usr/share/qt4/mkspecs/features/qt.prf:
/usr/share/qt4/mkspecs/features/unix/opengl.prf:
/usr/share/qt4/mkspecs/features/moc.prf:
/usr/share/qt4/mkspecs/features/unix/thread.prf:
/usr/share/qt4/mkspecs/features/warn_on.prf:
/usr/share/qt4/mkspecs/features/resources.prf:
/usr/share/qt4/mkspecs/features/uic.prf:
/usr/share/qt4/mkspecs/features/yacc.prf:
/usr/share/qt4/mkspecs/features/lex.prf:
qmake:  FORCE
	@$(QMAKE) -unix -o Makefile src.pro

dist: 
	@$(CHK_DIR_EXISTS) .tmp/gltrail1.0.0 || $(MKDIR) .tmp/gltrail1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .tmp/gltrail1.0.0/ && $(COPY_FILE) --parents input.h element.h textured_element.h activity.h relation.h window.h glwidget.h background_updater.h inputs/ssh.h inputs/digg.h inputs/twitter.h .tmp/gltrail1.0.0/ && $(COPY_FILE) --parents main.cpp activity.cpp element.cpp textured_element.cpp window.cpp glwidget.cpp background_updater.cpp input.cpp inputs/ssh.cpp inputs/digg.cpp inputs/twitter.cpp .tmp/gltrail1.0.0/ && (cd `dirname .tmp/gltrail1.0.0` && $(TAR) gltrail1.0.0.tar gltrail1.0.0 && $(COMPRESS) gltrail1.0.0.tar) && $(MOVE) `dirname .tmp/gltrail1.0.0`/gltrail1.0.0.tar.gz . && $(DEL_FILE) -r .tmp/gltrail1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all: moc_window.cpp moc_glwidget.cpp moc_background_updater.cpp moc_ssh.cpp moc_digg.cpp moc_twitter.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) moc_window.cpp moc_glwidget.cpp moc_background_updater.cpp moc_ssh.cpp moc_digg.cpp moc_twitter.cpp
moc_window.cpp: glwidget.h \
		input.h \
		window.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) window.h -o moc_window.cpp

moc_glwidget.cpp: input.h \
		glwidget.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) glwidget.h -o moc_glwidget.cpp

moc_background_updater.cpp: element.h \
		input.h \
		glwidget.h \
		activity.h \
		relation.h \
		background_updater.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) background_updater.h -o moc_background_updater.cpp

moc_ssh.cpp: input.h \
		inputs/ssh.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) inputs/ssh.h -o moc_ssh.cpp

moc_digg.cpp: input.h \
		inputs/digg.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) inputs/digg.h -o moc_digg.cpp

moc_twitter.cpp: input.h \
		inputs/twitter.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) inputs/twitter.h -o moc_twitter.cpp

compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all:
compiler_uic_clean:
compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean 

####### Compile

main.o: main.cpp window.h \
		glwidget.h \
		input.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o main.o main.cpp

activity.o: activity.cpp activity.h \
		glwidget.h \
		input.h \
		element.h \
		relation.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o activity.o activity.cpp

element.o: element.cpp element.h \
		input.h \
		glwidget.h \
		activity.h \
		relation.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o element.o element.cpp

textured_element.o: textured_element.cpp textured_element.h \
		element.h \
		input.h \
		glwidget.h \
		activity.h \
		relation.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o textured_element.o textured_element.cpp

window.o: window.cpp window.h \
		glwidget.h \
		input.h \
		inputs/ssh.h \
		inputs/digg.h \
		inputs/twitter.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o window.o window.cpp

glwidget.o: glwidget.cpp glwidget.h \
		input.h \
		element.h \
		activity.h \
		relation.h \
		background_updater.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o glwidget.o glwidget.cpp

background_updater.o: background_updater.cpp background_updater.h \
		element.h \
		input.h \
		glwidget.h \
		activity.h \
		relation.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o background_updater.o background_updater.cpp

input.o: input.cpp input.h \
		glwidget.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o input.o input.cpp

ssh.o: inputs/ssh.cpp inputs/ssh.h \
		input.h \
		glwidget.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ssh.o inputs/ssh.cpp

digg.o: inputs/digg.cpp inputs/digg.h \
		input.h \
		glwidget.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o digg.o inputs/digg.cpp

twitter.o: inputs/twitter.cpp inputs/twitter.h \
		input.h \
		glwidget.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o twitter.o inputs/twitter.cpp

moc_window.o: moc_window.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_window.o moc_window.cpp

moc_glwidget.o: moc_glwidget.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_glwidget.o moc_glwidget.cpp

moc_background_updater.o: moc_background_updater.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_background_updater.o moc_background_updater.cpp

moc_ssh.o: moc_ssh.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_ssh.o moc_ssh.cpp

moc_digg.o: moc_digg.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_digg.o moc_digg.cpp

moc_twitter.o: moc_twitter.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_twitter.o moc_twitter.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

