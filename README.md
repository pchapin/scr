
The Scr Screen Handling Library
===============================

This folder contains the Scr library. See the Scr documentation for more information about the
nature and scope of this project. Here are a few issues to keep in mind.

1. Scr is intended to be compiled as C++98 (as required by Open Watcom).

1. It is intended for Scr to be compiled with Visual C++ on Windows, with Open Watcom on (16
   bit) DOS, Windows, and OS/2, and with Code::Blocks or Makefiles (with gcc) on Linux.

2. This folder contains a VC++ solution file, Open Watcom build control files for WMAKE, a
   Makefile for GNU Make, and a Code::Blocks project file.

3. The Scr library is documented using doxygen.

When adding or removing modules from this library you should:

+ Edit the Visual Studio project file to reflect the change.
+ Edit master.mif to reflect the change.
+ Edit scr.cds to reflect the change.
+ Edit the Code::Blocks project file to reflect the change.

If you wish to contact me regarding this library, and I welcome comments, bug reports,
contributions, etc.

Peter Chapin  
chapinp@proton.me  
