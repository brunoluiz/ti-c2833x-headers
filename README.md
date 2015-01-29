TI 2833x Header Files (Linux Compatible)
========================================

The default TI header files were built for Windows and, as Windows is not case-sensitive, the file name format doesn't care. However, case-sensitive systems (Linux) will throw errors at compilation because of the file name format. The files of this repository fix this problem.

How to use it:
--------------

At CCS, go to Project Settings > Build > C2000 Compiler > Include Options. There you need to include the path for "include" folders.
