

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

**What are the Features of C Language?**

- Simple and Efficient
- Fast
- Availability of only the essential and required features
- Portability
- Extensibility
- Function-Rich Libraries
- Dynamic Memory Management
- Modularity With Structured Language
- Mid-Level Programming Language
- Pointers
- Recursion


**Basic Structure of C Program**

Section | Description
-- | --
Documentation | Consists of the description of the program, programmer's name, and creation date. These are generally written in the form of comments
Link | All header files are included in this section which contains different functions from the libraries. A copy of these header files is inserted into your code before compilation
Definition | Includes preprocessor directive, which contains symbolic constants
Global Declaration | Includes declaration of global variables, function declarations, static global variables, and functions
Main() | Function	For every C program, the execution starts from the main() function. It is mandatory to include a main() function in every C program
Subprograms | Includes all user-defined functions (functions the user provides). They can contain the inbuilt functions, and the function definitions declared in the Global Declaration section. These are called in the main() function

**Execution of C Program**

```
// file name - simple.c

#include <stdio.h>

int main(){    
    printf("Hello C Language");    
    return 0;   
}  
```

1) C program (source code) is sent to preprocessor first. The preprocessor is responsible to convert preprocessor directives into their respective values. The preprocessor generates an expanded source code.

2) Expanded source code is sent to compiler which compiles the code and converts it into assembly code.

3) The assembly code is sent to assembler which assembles the code and converts it into object code. Now a simple.obj file is generated.

4) The object code is sent to linker which links it to the library such as header files. Then it is converted into executable code. A simple.exe file is generated.

5) The executable code is sent to loader which loads it into memory and then it is executed. After execution, output is sent to console.

![img](https://github.com/c0st/C/blob/main/Drawables/Programflow.png)

**Rules for naming a variable**

- A variable name can only have letters, digits and underscore
- The first letter of a variable should be either a letter or an underscore
- There is no rule on how long a variable name (identifier) can be
- You should always try to give meaningful names to variables

**Keywords and Identifiers in C**

- Keywords are the reserved words in C language. They have special meaning and cannot be used as a constant or variable or any other identifier names. Keywords are not case sensitive.

- Identifiers are user-defined names to represent a variable, function, array, or any other user-defined item. An identifier name can be a combination of letters, digits, and underscores. An identifier name must not start with a digit. Keywords cannot be used as identifiers.

[List of all keywords in C](https://www.programiz.com/c-programming/list-all-keywords-c-language)

**Data Types in C**

![img](https://github.com/c0st/C/blob/main/Drawables/Datatypes.jpg)