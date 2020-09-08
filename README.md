# QUINE
This project consists of making you discover Kleene's recursion theorem !

## RESUME
A quine is a computer program (a kind of metaprogram) whose output and source code are identical.
For this project, i did coded three different programs, each having different
properties. Each of the programs are both coded in C, Assembler, and C++
respectively rendered in a folder named C, ASM and C++.

## BEHAVIOUR
### The first program
+ Is named __Colleen__.
+ When running, the program must display an output on the standard output
  identical to the source code of the file used to compile this same program.

### The second program
+ Is named __Grace__.
+ When executed, the program writes to a file named Grace_kid.c / Grace_kid.s / Grace_kid.cpp
  the source code of the file used to compile this same program.
+ The program will launch when a macro is called.

### The third program
+ Is named __Sully__.
+ When it is executed, the program writes to a file named Sully_X.c / Sully_X.s.
  The X will then be an integer given in the source. Once the file is created, the program
  compile this file then run the new program (which will have the name of its source file).
+ The program is stopped according to the name of the file: if the integer X is 0,
  the resulting program is not executed.
+ An integer is therefore present in the source of your program and will have to evolve
  by decrementing each time a source file is created since the execution of the
  program.

## AUTHOR
+ Gilles Bourgeois
