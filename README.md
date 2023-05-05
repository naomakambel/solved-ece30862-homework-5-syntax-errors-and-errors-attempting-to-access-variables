Download Link: https://assignmentchef.com/product/solved-ece30862-homework-5-syntax-errors-and-errors-attempting-to-access-variables
<br>
Fix the C++ program so that it compiles and runs. There are two kinds of errors: syntax errors and errors attempting to access variables that cannot be accessed. For the syntax errors you will need to add some characters to lines. For the access protection errors create getter and setter functions that allow the accesses to be legal. This homework will be most useful if you attempt to fix the access protection errors without compiling, by understanding what private, protected and public means, and what “: public class”, “: protected class” and “: private class” mean when inheriting.

<strong>HW5b:</strong>

Examine the provided program.  Draw the VFTs for the classes and for each function call in main.cpp, show which VFT entry is used.  I have given an example for the first one below.  Note any strange behavior and explain it in terms of the VFTs.   You may do your drawings by hand and scan or photograph the sheet to turn in.  <strong>Note that this program shows the dangers of using C-style casts.  You should never, ever, do something like this in a program you write.</strong>

Make a different copy of main.cpp called mainStaticCast.cpp and mainDynamicCast.cpp and turn the Cstyle casts into static_cast and dynamic_cast, respectively.  Observer the behavior.   Explain briefly any runtime or compile time errors.  Turn in your explanations.

<strong>What to turn in.</strong>  You should have a HW5 directory with HW5a and HW5b sub-directories.  Rename the HW5 directory your userid, and then turn in the zipped HW5 directory.  Do not turn in the a.out or other executable files.   Your vft drawing  for HW5b should be a .pdf, either a scan of a hand drawn figure or exported from Word, Keynote, Pages, Powerpoint, etc.