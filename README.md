

# C

## THE C PROGRAMMING LANGUAGE
### Second Edition

by Brian W. Kernighan and Dennis M. Ritchie

#### Contents

**Chapter 1. A Tutorial Introduction**
- Getting Started
- Variables and Arithmetic Expressions
- The For Statement 
- Symbolic Constants 
- Character Input and Output 
- Arrays 
- Functions 
- Arguments-Call by Value 
- Character Arrays 
- External Variables and Scope

**Chapter 2. Types, Operators, and Expressions**
- Variable Names
- Data Types and Sizes 
- Constants 
- Declarations 
- Arithmetic Operators 
- Relational and Logical Operators 
- Type Conversions 
- Increment and Decrement Operators 
- Bitwise Operators 
- Assignment Operators and Expressions 
- Conditional Expressions 
- Precedence and Order of Evaluation 

**Chapter 3. Control Flow**
- Statements and Blocks 
- If-Else 
- Else-If 
- Switch 
- Loops-While and For 
- Loops-Do-while 
- Break and Continue 
- Goto and Labels

**Chapter 4. Functions and Program Structure**
- Basics of Functions 
- Functions Returning Non-integers 
- External Variables 
- Scope Rules 
- Header Files 
- Static Variables 
- Register Variables 
- Block Structure 
- Initialization 
- Recursion 
- The C Preprocessor

**Chapter 5. Pointers and Arrays**
- Pointers and Addresses 
- Pointers and Function Arguments 
- Pointers and Arrays 
- Address Arithmetic 
- Character Pointers and Functions 
- Pointer Arrays; Pointers to Pointers 
- Multi-dimensional Arrays 
- Initialization of Pointer Arrays 
- Pointers vs. Multi-dimensional Arrays 
- Command-line Arguments 
- Pointers to Functions 
- Complicated Declarations

**Chapter 6. Structures**
- Basics of Structures 
- Structures and Functions 
- Arrays of Structures 
- Pointers to Structures 
- Self-referential Structures 
- Table Lookup 
- Typedef 
- Unions 
- Bit-fields 

**Chapter 7. Input and Output**
- Standard Input and Output
- Formatted Output-Printf
- Variable-length Argument Lists
- Formatted lnput-Scanf
- File Access
- Error Handling-Stderr and Exit
- Line Input and Output
- Miscellaneous Functions

**Chapter 8 The UNIX System Interface**
- File Descriptors
- Low Level 1/O-Read and Write
- Open, Creat, Close, Unlink
- Random Access-Lseek
- Example- An Implementation of Fopen and Getc
- Example- Listing Directories
- Example- A Storage Allocator

**Appendix A. Reference Manual**
-  Introduction
-  Lexical Conventions
-  Syntax Notation
-  Meaning of Identifiers
-  Objects and Lvalues
-  Conversions
-  Expressions
-  Declarations
-  Statements
-  External Declarations
-  Scope and Linkage
-  Preprocessing
-  Grammar

**Appendix B. Standard Library**
- Input and Output: <stdio.h>
- Character Class Tests: <ctype.h>
- String Functions: <string.h>
- Mathematical Functions: <math.h>
- Utility Functions: <stdlib.h>
- Diagnostics: <assert.h>
- Variable Argument Lists: <stdarg.h>
- Non-local Jumps: <setjmp.h>
- Signals: <signal.h>
- Date and Time Functions: <time.h>
- Implementation-defined Limits: <limits.h> and <float.h>

#

***

**High vs Low Level Programming**

- High level programming languages are easier to learn and use, but they are slower and less efficient than low level languages
- High level languages are more portable than low level languages
- Python, Java, C#, C++, and JavaScript are examples of high level languages
- Assembly language, machine language, and C are examples of low level languages

**Compiler vs Interpreter**

Interpreter | Compiler
-- | --
Translates program one statement at a time | Scans the entire program and translates it as a whole into machine code.
Interpreters usually take less amount of time to analyze the source code. However, the overall execution time is comparatively slower than compilers | Compilers usually take a large amount of time to analyze the source code. However, the overall execution time is comparatively faster than interpreters.
No Object Code is generated, hence are memory efficient | Generates Object Code which further requires linking, hence requires more memory.
Programming languages like JavaScript, Python, Ruby use interpreters | Programming languages like C, C++, Java use compilers.

#

![img](https://github.com/c0st/C/blob/main/Drawables/working.png)
