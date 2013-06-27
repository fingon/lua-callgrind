lua-callgrind
=============

Minimalist utility library to produce Valgrind's callgrind-like logging out
of Lua.

Check http://jan.kneschke.de/2007/11/14/profiling-lua-with-kcachegrind/ for
background. The usage has changed somewhat since..

Simple usage:

> lua -lcallgrind foo.lua
> kcachegrind lua-callgrind.txt


