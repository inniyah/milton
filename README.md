Milton
======

Milton is a paint package. You know MS Paint? Like that.

How to Compile (Windows x64)
============================

1. Open a Windows shell. cd to Milton's directory
2. `getstuff.bat` to clone dependencies
3. `scripts\vcvars.bat` to get Visual Studio's tools into the PATH. (Assumes VS is installed in the default dir.)
4. `gen_and_build.bat` to do run the meta-programming pass and then compile.
4. Open build\Milton.sln in VS 2013

To-Do
=====

* Bugs

* Application
    * Better platform input abstraction
    * Panning
    * Opacity early-reject.
    * Eraser
    * Progressive rendering
    * Threaded canvas update.
    * Queue commands & handle multiple view changes.
    * Picker cache
    * Gamma correct blending
    * Undo/redo

* Platforms
    * Move to SDL.

