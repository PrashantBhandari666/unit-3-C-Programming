# Basic Concept of C

## Introduction
----------------------------------
C is a general-purpose, procedural computer programming language supporting structured programming, lexical variable scope, and recursion, with a static type system. By design, C provides constructs that map efficiently to typical machine instructions. It has found lasting use in applications previously coded in assembly language. Such applications include operating systems and various application software for computer architectures that range from supercomputers to PLCs and embedded systems.

## History
-----------------------------------
History of C language is interesting to know. C programming language was developed in 1972 by Dennis Ritchie at bell laboratories of AT&T (American Telephone & Telegraph), located in the U.S.A. Dennis Ritchie is known as the founder of the C language. It was developed to overcome the problems of previous languages such as B, BCPL, etc. Initially, C language was developed to be used in UNIX operating system. It inherits many features of previous languages such as B and BCPL.

## Features
------------------------------------
C is the widely used language. It provides many features that are given below.

* Simple
* Machine Independent or Portable
* Mid-level programming language
* structured programming language
* Rich Library
* Memory Management
* Fast Speed
* Pointers
* Recursion
* Extensible

1. ### **Simple:** _C is a simple language in the sense that it provides a structured approach (to break the problem into parts), the rich set of library functions, data types, etc._

2. ### **Machine Independent or Portable:** _Unlike assembly language, c programs can be executed on different machines with some machine specific changes. Therefore, C is a machine independent language._

3. ### **Mid-level programming language:** _Although, C is intended to do low-level programming. It is used to develop system applications such as kernel, driver, etc. It also supports the features of a high-level language. That is why it is known as mid-level language._

4. ### **Structured programming language:** _C is a structured programming language in the sense that we can break the program into parts using functions. So, it is easy to understand and modify. Functions also provide code reusability._

5. ### **Rich Library:** _C provides a lot of inbuilt functions that make the development fast._

6. ### **Memory Management:** _It supports the feature of dynamic memory allocation. In C language, we can free the allocated memory at any time by calling the free() function._

7. ### **Fast Speed:** _The compilation and execution time of C language is fast since there are lesser inbuilt functions and hence the lesser overhead._

8. ### **Pointers:** _C provides the feature of pointers. We can directly interact with the memory by using the pointers. We can use pointers for memory, structures, functions, array, etc._

9. ### **Recursion:** _In C, we can call the function within the function. It provides code reusability for every function. Recursion enables us to use the approach of backtracking._

10. ### **Extensible:** _C language is extensible because it can easily adopt new features._

## Advantages
---------------------------------------
* Powerful and efficient language
* Portable language
* Middle-level language
* Procedural programming language
* Dynamic memory allocation
* System-programming
* Building block for many other programming languages

1. ### **Powerful and efficient language:** _C is a robust language as it contains many data types and operators to give you a vast platform to perform all kinds of operations._

2. ### **Portable language:** _C is very flexible, or we can say machine independent that helps you to run your code on any machine without making any change or just a few changes in the code._

3. ### **Middle-level language:** _C is a middle-level programming language that means it supports high-level programming as well as low-level programming. It supports the use of kernels and drivers in low-level programming and also supports system software applications in the high-level programming language._

4. ### **Procedural programming language:** _C follows a proper procedure for its functions and subroutines. As it uses procedural programming, it becomes easier for C to identify code structure and to solve any problem in a specific series of code. In procedural programming C variables and functions are declared before use._

5. ### **Dynamic memory allocation:** _C provides dynamic memory allocation that means you are free to allocate memory at run time. For example, if you don’t know how much memory is required by objects in your program, you can still run a program in C and assign the memory at the same time._

6. ### **System-programming:** _C follows a system based programming system. It means the programming is done for the hardware devices._

7. ### **Building block for many other programming languages:** _C is considered to be the most fundamental language that needs to be studied if you are beginning with any programming language. Many programming languages such as Python, C++, Java, etc are built with the base of the C language._

## Disadvantages
---------------------------
* Concept of OOPs
* Run-time checking
* Concept of namespace
* Lack of Exception Handling
* Constructor or destructor
* Low level of abstraction

1. ### **Concept of OOPs:** _C is a very vast language, but it does not support the concept of OOPs (Inheritance, Polymorphism, Encapsulation, Abstraction, Data Hiding). C simply follows the procedural programming approach._

2. ### **Run-time checking:** _In the C programming language, the errors or the bugs aren’t detected after each line of code. Instead, the compiler shows all the errors after writing the program. It makes the checking of code very complex in large programs._

3. ### **Concept of namespace:** _C does not implement the concept of namespaces. A namespace is structured as a chain of commands to allow the reuse of names in different contexts. Without namespaces, we cannot declare two variables of the same name._ _But, C programming lacks in this feature, and hence you cannot define a variable with the same name in C._

4. ### **Lack of Exception Handling:** _Exception Handling is one of the most important features of programming languages. While compiling the code, various anomalies and bugs can occur. Exception Handling allows you to catch the error and take appropriate responses. However, C does not exhibit this important feature._

5. ### **Constructor or destructor:** _C does not have any constructor or destructor.__Constructors & Destructors support basic functionality of Object Oriented Programming. Both are member functions that are created as soon as an object of the class is created. You will be studying constructor and destructor in detail later on._

6. ### **Low level of abstraction:** _C is a small and core machine language that has minimum data hiding and exclusive visibility that affects the security of this language._

## Structure of C language
------------------------------------
```c
// This program prints hello world.
// Author - Prashant Bhandari  
#include<stdio.h>
int main()
{
    printf("Hello, World!\n");
    return (0);
}
```

Following is the basic structure of a C program.

|                     |                                                                                                                                   |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------- |
|Documentation        |Consists of comments, some description of the program, programmer name and any other useful points that can be referenced later.   |
|Link                 |Provides instruction to the compiler to link function from the library function.                                                   |
|Definition           |Consists of symbolic constants.                                                                                                    |
|Global declaration   |Consists of function declaration and global variables.                                                                             |
|``main( )``          |Every C program must have a ``main()`` function which is the starting point of the program execution.                              |
|Braces               |Two curly brackets "{...}" are used to group all statements.or Curly braces which shows how much the main() function has its scope.|
|``return(0);``       |At the end of the main function returns value 0.                                                                                   |
|Subprograms          |User defined functions.                                                                                                            |

-----------------------------------------------
_The Documentation section usually contains the collection of comment lines giving the name of the program, author's or programmer's name and few other details. The second part is the link-section which instructs the compiler to connect to the various functions from the system library. The Definition section describes all the symbolic-constants. The global declaration section is used to define those variables that are used globally within the entire program and is used in more than one function. This section also declares all the user-defined functions. Then comes the main(). All C programs must have a main() which contains two parts:_

* Declaration part
* Execution part

_The declaration part is used to declare all variables that will be used within the program. There needs to be at least one statement in the executable part, and these two parts are declared within the opening and closing curly braces of the main(). The execution of the program begins at the opening brace '{' and ends with the closing brace '}'. Also, it has to be noted that all the statements of these two parts need to be terminated with a semi-colon._

_The sub-program section deals with all user-defined functions that are called from the main(). These user-defined functions are declared and usually defined after the main() function._
## Compiling process
----------------------------

![Process](photos/photo.png)

_The compilation is a process of converting the source code into object code. It is done with the help of the compiler. The compiler checks the source code for the syntactical or structural errors, and if the source code is error-free, then it generates the object code._

_The c compilation process converts the source code taken as input into the object code or machine code. The compilation process can be divided into four steps, i.e., Pre-processing, Compiling, Assembling, and Linking._

_The preprocessor takes the source code as an input, and it removes all the comments from the source code. The preprocessor takes the preprocessor directive and interprets it. For example, if ``<stdio.h>``, the directive is available in the program, then the preprocessor interprets the directive and replace this directive with the content of the 'stdio.h' file._

_The following are the phases through which our program passes before being transformed into an executable form:_

* Preprocessor
* Compiler
* Assembler
* Linker

### **Preprocessor**
_The source code is the code which is written in a text editor and the source code file is given an extension ".c". This source code is first passed to the preprocessor, and then the preprocessor expands this code. After expanding the code, the expanded code is passed to the compiler._

### **Compiler**
_The code which is expanded by the preprocessor is passed to the compiler. The compiler converts this code into assembly code. Or we can say that the C compiler converts the pre-processed code into assembly code._

### **Assembler**
_The assembly code is converted into object code by using an assembler. The name of the object file generated by the assembler is the same as the source file. The extension of the object file in DOS is '.obj,' and in UNIX, the extension is 'o'. If the name of the source file is 'hello.c', then the name of the object file would be 'hello.obj'._

### **Linker**
_Mainly, all the programs written in C use library functions. These library functions are pre-compiled, and the object code of these library files is stored with '.lib' (or '.a') extension. The main working of the linker is to combine the object code of library files with the object code of our program. Sometimes the situation arises when our program refers to the functions defined in other files; then linker plays a very important role in this. It links the object code of these files to our program. Therefore, we conclude that the job of the linker is to link the object code of our program with the object code of the library files and other files. The output of the linker is the executable file. The name of the executable file is the same as the source file but differs only in their extensions. In DOS, the extension of the executable file is '.exe', and in UNIX, the executable file can be named as 'a.out'. For example, if we are using ``printf()`` function in a program, then the linker adds its associated code in an output file._

## C - Preprocessors Directives and Header Files
------------------------------------------
### **C - Preprocessors Directives**
_Preprocessor directives are the special instructions which are executed before code passes through the compilation process._

_Every C programs are checked for the preprocessor statements before compiling and if any preprocessor statements are used in the program then they are processed first and then preprocessed program is handed over to the compiler for further compilation._

_Since every preprocessor statements are processed first and this is the reason for calling them preprocessor directives. It begins with hash (#) symbol and do not require semicolon at the end._

_One of the most important preprocessor directive is #include which is used for including header file._ 

|Directive    |                            Description                              |
|-------------|:-------------------------------------------------------------------:|
|``#define``  |Substitutes a preprocessor macro.                                    |
|``#include`` |Inserts a particular header from another file.                       |
|``#undef``   |Undefines a preprocessor macro.                                      |
|``#ifdef``   |Returns true if this macro is defined.                               |
|``#ifndef``  |Returns true if this macro is not defined.                           |
|``#if``      |Tests if a compile time condition is true                            |
|``#else``    |The alternative for #if.                                             |
|``#elif``    |``#else`` and ``#if`` in one statement.                              |
|``#endif``   |Ends preprocessor conditional.                                       |
|``#error``   |Prints error message on stderr.                                      |
|``#pragma``  |Issues special commands to the compiler, using a standardized method.|

### **Header Files**

_A header file is a file with extension .h which contains C function declarations and macro definitions to be shared between several source files. There are two types of header files: the files that the programmer writes and the files that comes with your compiler._

_You request to use a header file in your program by including it with the C preprocessing directive #include, like you have seen inclusion of stdio.h header file, which comes along with your compiler._

_Including a header file is equal to copying the content of the header file but we do not do it because it will be error-prone and it is not a good idea to copy the content of a header file in the source files, especially if we have multiple source files in a program._

_A simple practice in C or C++ programs is that we keep all the constants, macros, system wide global variables, and function prototypes in the header files and include that header file wherever it is required._

#### **Include Syntax:**

_Both the user and the system header files are included using the preprocessing directive #include. It has the following two forms:_


```c 
#include <file>
```
_This form is used for system header files. It searches for a file named 'file' in a standard list of system directories. You can prepend directories to this list with the -I option while compiling your source code._

```c
#include "file"
```
_This form is used for header files of your own program. It searches for a file named 'file' in the directory containing the current file. You can prepend directories to this list with the -I option while compiling your source code._

## Library Functions
--------------------------------------

C Standard library functions or simply C Library functions are inbuilt functions in C programming.The C library functions are provided by the system and stored in the library. The C library function is also called an inbuilt function in C programming.

The prototype and data definitions of these functions are present in their respective header files. To use these functions we need to include the header file in our program. 

For example: ``printf()``, ``scanf()``, ``sqrt()`` etc.

>If you want to use the ``printf()`` function, the header file ``<stdio.h>`` should be included.

### **Advantages of Using C library functions**

#### **They work**

_One of the most important reasons you should use library functions is simply because they work. These functions have gone through multiple rigorous testing and are easy to use._

#### **The functions are optimized for performance**

_Since, the functions are "standard library" functions, a dedicated group of developers constantly make them better. In the process, they are able to create the most efficient code optimized for maximum performance._

#### **It saves considerable development time**

_Since the general functions like printing to a screen, calculating the square root, and many more are already written. You shouldn't worry about creating them once again._

#### **The functions are portable**

_With ever-changing real-world needs, your application is expected to work every time, everywhere. And, these library functions help you in that they do the same thing on every computer._

### **Library Functions in Different Header Files**

|               |                                     |
|---------------|-------------------------------------|
|``<assert.h>``	|Program assertion functions          |
|``<ctype.h>``	|Character type functions             |
|``<locale.h>``	|Localization functions               |
|``<math.h>``	|Mathematics functions                |
|``<setjmp.h>``	|Jump functions                       |
|``<signal.h>``	|Signal handling functions            |
|``<stdarg.h>``	|Variable arguments handling functions|
|``<stdio.h>``	|Standard Input/Output functions      |
|``<stdlib.h>``	|Standard Utility functions           |
|``<string.h>``	|String handling functions            |
|``<time.h>``	|Date time functions                  |

## Character Set
----------------------------------------------------------------------
Like every other language, 'C' also has its own character set. A program is a set of instructions that, when executed, generate an output. The data that is processed by a program consists of various characters and symbols. The output generated is also a combination of characters and symbols.

A character set in 'C' is divided into,

* Alphabets
* Digits
* White spaces (blank spaces)
* Special characters


### **Alphabets**
_C language supports all the alphabets from the English language. Lower and upper case letters together support 52 alphabets._

* Lower Case Letters - a to z
* Upper Case Letters - A to Z

### **Digits**
_C language supports 10 digits which are used to construct numerical values in C language._

Digits - 0, 1, 2, 3, 4, 5, 6, 7, 8, 9

### **White spaces**
* Blank space
* New line
* Carriage return
* Horizontal tab

### **Special Characters**
_C language supports a rich set of special symbols that include symbols to perform mathematical operations, to check conditions and other special symbols._

Special Symbols :- ~ @ # $ % ^ & * ( ) _ - + = { } [ ] ; : ' " / ? . > , < \ | etc

## Comments
---------------------------------------------------------
A well-documented program is a good practice as a programmer. It makes a program more readable and error finding become easier. One important part of good documentation is Comments.

* In computer programming, a comment is a programmer-readable explanation or annotation in the source code of a computer program.
* Comments are statements that are not executed by the compiler and interpreter. 

In C there are two types of comments :

* Single line comment
* Multi-line comment

### **Single line comment**
_Single line comments are represented by double slash ``//``._
```c
// single line comment
```

### **Multi-line comment**
_Multi-Line comments are represented by slash asterisk ``/* ... */``. It can occupy many lines of code, but it can't be nested._
```c
/*Comment starts
continues
continues
.
.
.
Comment ends*/
```
## Tokens and its types
----------------------------------------------------------
Token is the smallest unit in a 'C' program. It is each and every word and punctuation that you come across in your C program. The compiler breaks a program into the smallest possible units (tokens) and proceeds to the various stages of the compilation. A token is the smallest element of a program that is meaningful to the compiler.

Tokens can be classified as follows:  

* Keywords
* Identifiers
* Constants
* Strings
* Special Symbols
* Operators

### **Keywords**

_Keywords are predefined, reserved words in C and each of which is associated with specific features. These words help us to use the functionality of C language. They have special meaning to the compilers.C language supports 32 keywords.For eg:-auto ,double ,int, struct, break, else, long, switch, case, enum, register, typedef, char, extern, return, union etc._

### **Identifiers**
_An identifier is nothing but a name assigned to an element in a program.Each program element in C programming is known as an identifier. They are used for naming of variables, functions, array etc. These are user-defined names which consist of alphabets, number, underscore ‘ _ ’.Identifier’s name should not be same or same as keywords. Keywords are not used as identifiers._

### **Constants**
_Constants are also like normal variables. But, the only difference is, their values can not be modified by the program once they are defined. Constants refer to fixed values. They are also called literals. Constants may belong to any of the data type._

### **Strings**
_A string is an array of characters ended with a null character(\0). This null character indicates that string has ended. Strings are always enclosed with double quotes(“ “)._

_Let us see how to declare String in C language :_

 ```C 
 char string[20] = {‘s’,’t’,’u’,’d’,’y’, ‘\0’};
 ```
 ```C
 char string[20] = “demo”;
 ```
 ```C
 char string [] = “demo”;
 ```
### **Special Symbols** 
_The following special symbols are used in C having some special meaning and thus, cannot be used for some other purpose.For eg:[] () {} , ; * = # etc_

### **Operators**
_Operators are symbols that trigger an action when applied to C variables and other objects. The data items on which operators act upon are called operands. Depending on the number of operands that an operator can act upon, operators can be classified as follows:_ 
 

* **Unary Operators:** _Those operators that require only a single operand to act upon are known as unary operators.For Example increment and decrement operators_

* **Binary Operators:** _Those operators that require two operands to act upon are called binary operators._

## Data types in C
--------------------------------------
Data types specify how we enter data into our programs and what type of data we enter. C language has some predefined set of data types to handle various kinds of data that we can use in our program. These datatypes have different storage capacities.

Each variable in C has an associated data type. Each data type requires different amounts of memory and has some specific operations which can be performed over it.

C language supports 2 different type of data types:

### **Primary data types:**
These are fundamental data types in C namely integer(``int``), floating point(``float``), character(``char``) and ``void``.

* **``char``:** _The most basic data type in C. It stores a single character and requires a single byte of memory in almost all compilers._
* **``int``:** _As the name suggests, an int variable is used to store an integer._
* **``float``:** _It is used to store decimal numbers (numbers with floating point value) with single precision._
* **``double``:** _It is used to store decimal numbers (numbers with floating point value) with double precision._ 

### **Derived data types:**
Derived data types are nothing but primary datatypes but a little twisted or grouped together like array, stucture, union and pointers.

## Escape Sequences
---------------------------------------
In C programming language, there are 256 numbers of characters in character set. The entire character set is divided into 2 parts i.e. the ASCII characters set and the extended ASCII characters set. But apart from that, some other characters are also there which are not the part of any characters set, known as Escape characters. An escape sequence in C language is a sequence of characters that doesn't represent itself when used inside string literal or character.

|Escape Sequence|      Meaning        |
|---------------|---------------------|
|``\a``         |   Alarm or Beep     |
| ``\b``        |   Backspace         |
| ``\f``        |   Form Feed         |
| ``\n``        |   New Line          |
| ``\r``        |   Carriage Return   |
| ``\t``        |   Tab (Horizontal)  |
| ``\v``        |   Vertical Tab      |
| ``\\``        |   Backslash         |
| ``\'``        |   Single Quote      |
| ``\"``        |   Double Quote      |
| ``\?``        |   Question Mark     |
| ``\nnn``      |   octal number      |
| ``\xhh``      |   hexadecimal number|
| ``\0``        |   Null              |
