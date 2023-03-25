#STACK, QUEUES - LIFO, FIFO

Stack and queue data structures in C


***The Monty language***
*Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

Monty byte code files

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument:*


###Compile:	
```bash
./build.sh

OR

gcc -Wall -Werror -Wextra -pedantic *.c -o monty
```

###USAGE:
```bash
./monty <file>
cat -e bytecodes/000.m
```

###FORT TESTING WITH BYTECODES:
```bash
./monty test_files/FILENAME.m

Example:
./monty test_files/000.m
```

*©Lilian and Wilson*
