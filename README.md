ZeroReserve
===========

Friend 2 Friend Payment and Bitcoin exchange

Prerequisite for building is a successful RetroShare build and sqlite3.

To build, checkout the sources to the plugins directory of Retroshare and build with

$ qmake && make clean && make

To install on Windows, drop the resulting DLL into the
%APPDATA%\Retroshare\extensions directory.

To install on Linux, drop the resulting shared object into
~/.retroshare/extensions


This is experimental software. Use at your own risk. At this stage, leave TestNet
on. Don't enable real currencies.
