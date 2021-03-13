This is an x86-64 bomb for self-study students. 

A "binary bomb" is a Linux executable C program that consists of six
"phases." Each phase expects the student to enter a particular string
on stdin.  If the student enters the expected string, then that phase
is "defused."  Otherwise the bomb "explodes" by printing "BOOM!!!".
The goal for the students is to defuse as many phases as possible.

In order to defuse the bomb, students must use a debugger, typically
gdb or ddd, to disassemble the binary and/or single-step through the
machine code in each phase. The idea is to understand at least partly
what the code does, and then use this knowledge to infer the
defusing string.  It's great to learn to use a debugger tool, such as
gdb, as well as objdump and readelf tools.

