# C Language 📜

---
## 📖 Introduction

C is a powerful and flexible procedural programming language, created in 1972 by Dennis M. Ritchie at Bell Labs. It was initially designed to develop the UNIX operating system on a DEC PDP-11 computer.

In 1978, Brian Kernighan and Dennis Ritchie produced the first publicly available description of C, now known as the K&R standard.

The UNIX operating system, the C compiler, and essentially all UNIX application programs have been written in C. C has now become a widely used professional language for various reasons:
-   Easy to learn
-   Structured language
-   It produces efficient programs
-   It can handle low-level activities
-   It can be compiled on a variety of computer platforms

## 📜 History of C Language

The history of C is a cornerstone in the evolution of computer science. Its development laid the groundwork for many modern programming technologies.

### Early Roots and Creation
The journey began with `ALGOL` in 1960, which introduced structured programming. This was followed by `BCPL` (Basic Combined Programming Language) in 1967. These languages paved the way for Ken Thompson's `B` language at Bell Labs.

In the early 1970s, **Dennis Ritchie**, also at Bell Labs, developed **C** as a successor to B. The primary goal was to create a language to re-implement the UNIX operating system. C was designed to be simple, efficient, and portable, making it suitable for both system and application development.

### Standardization and Evolution
As C's popularity grew, the need for a standard became clear.

-   **K&R C (1978):** Brian Kernighan and Dennis Ritchie published "The C Programming Language." This book served as an informal specification for the language, and this version became known as "K&R C".

-   **ANSI C & ISO C:** To create a more formal standard, the American National Standards Institute (ANSI) and the International Organization for Standardization (ISO) began work, leading to a series of official versions:
    -   **C89/C90:** The first official standard, which introduced many new features and became the baseline for C compilers for many years.
    -   **C99 (1999):** Added features like inline functions, new data types (e.g., `long long int`), and C++-style single-line comments (`//`).
    -   **C11 (2011):** Introduced multi-threading support, anonymous structures, and improved Unicode support.
    -   **C17/C18 (2018):** The current standard, which primarily consists of technical corrections and clarifications for C11, without adding new features.
    -   **C23 (Upcoming):** The next major revision, expected to introduce several new keywords and features.

### Lasting Influence
C's design principles, syntax, and control structures have profoundly influenced a vast number of other languages, including **C++, Java, C#, Python, and JavaScript**. Its combination of low-level memory access and high-level abstractions has cemented its place as a foundational language in both academia and industry.

## �‍👩‍👧‍👦 Audience

This tutorial is designed for software programmers with a need to understand the C programming language starting from scratch. This C tutorial will give you enough understanding on C programming language from where you can take yourself to a higher level of expertise.

## 📋 Prerequisites

Before proceeding with this tutorial, you should have a basic understanding of Computer Programming terminologies. A basic understanding of any of the programming languages will help you in understanding the C programming concepts and move fast on the learning track.

## 💡 Facts about C

-   C was invented to write an operating system called UNIX.
-   C is a successor of B language which was introduced around the early 1970s.
-   The language was formalized in 1988 by the American National Standard Institute (ANSI).
-   The UNIX OS was totally written in C.
-   Today C is the most widely used and popular System Programming Language.
-   Most of the state-of-the-art software have been implemented using C.
-   Today's most popular Linux OS and RDBMS MySQL have been written in C.

## 🤔 Why Use C Language?

C was initially used for system development work, particularly the programs that make-up the operating system. C was adopted as a system development language because it produces code that runs nearly as fast as the code written in assembly language.

C covers all the basic concepts of programming. It's a base or mother programming language to learn object-oriented programming like C++, Java, .Net, etc. Many modern programming languages such as C++, Java, and Python have borrowed syntax and concepts from C.

It provides fine-grained control over hardware, making it highly efficient. As a result, C is commonly used to develop system-level programs, like designing Operating Systems, OS kernels, etc., and also used to develop applications like Text Editors, Compilers, Network Drivers, etc.

C programs are portable; hence they can run on different platforms without significant modifications.

## ✨ Features of C Programming Language

The C language was created by Dennis Ritchie and Ken Thompson in 1972 with the main goal of reimplementing the Unix kernel. It continues to be extremely popular due to its powerful features, including low-level memory access, portability, and cross-platform support.

Here is an overview of some of the significant features of C language:

### 1. Procedural and Structured Language
C is described as a procedure-oriented and structured programming language. It is procedural because a C program is a series of instructions that explain the procedure of solving a given problem. In C, the logic of a process can be expressed in a structured or modular form with the use of function calls.

### 2. General-Purpose Language
The C language hasn't been developed with a specific area of application as a target. From system programming to photo editing software, the C programming language is used in various applications like Operating Systems, databases, device drivers, etc.

### 3. Fast Programming Language
C is a compiler-based language which makes the compilation and execution of codes faster. The source code is translated into hardware-specific machine code. Being statically typed also makes it faster compared to dynamically typed languages.

### 4. Portable
C programs are machine-independent, meaning you can compile and run the same code on various machines with none or minimal machine-specific changes.

### 5. Extensible
C is an extensible language. It allows adding new features, functionalities, and operations to an existing C program.

### 6. Standard Libraries
Most C compilers are bundled with an extensive set of libraries with several built-in functions (OS-specific utilities, string manipulation, mathematical functions, etc.). You can also create user-defined functions and add them to libraries.

### 7. Pointers
One of the unique features of C is its ability to manipulate the internal memory of the computer using pointers. Pointers allow direct interaction with memory, external hardware devices, interrupts, etc.

### 8. Mid-Level Programming Language
C provides low-level access to memory while offering high-level features like modularity. It bridges the gap between low-level and high-level languages.

### 9. Rich Set of Built-in Operators
C has a rich set of built-in operators (arithmetic, comparison, binary, pointer-related) used for writing complex or simplified programs.

### 10. Recursion
C supports recursion, where a function can call itself multiple times until a condition is true. This provides code reusability and backtracking functionality.

### 11. User-defined Data Types
Beyond basic types (`int`, `float`, `char`), C allows defining structures (`struct`), unions (`union`), and enumerated types (`enum`), making it very powerful.

### 12. Preprocessor Directives
C uses preprocessor directives like `#include` and `#define` to handle tasks such as importing libraries and defining macros before compilation.

### 13. File Handling
C handles file I/O through libraries and streams (`stdin`, `stdout`, `stderr`), allowing read/write operations on disk files.

## 👍 Advantages of C Language

-   **Efficiency and speed:** C is known for being high-performing and efficient. It can let you work with memory at a low level, as well as allow direct access to hardware.
-   **Portable:** C programs can be compiled and executed on different platforms with minimal or no modifications.
-   **Close to Hardware:** C allows direct manipulation of hardware through the use of pointers and low-level operations.
-   **Standard Libraries:** C comes with a large standard library which helps developers write code more efficiently.
-   **Structured Programming:** C helps to organize code into modular and easy-to-understand structures.
-   **Procedural Language:** C follows a procedural paradigm that is often simpler and more straightforward.
-   **Versatility:** C language is a versatile programming language and it can be used for various types of software.

## 👎 Drawbacks of C Language

-   **Manual Memory Management:** Developers have to take care of allocating and deallocating memory explicitly.
-   **No Object-Oriented Feature:** C language does not support OOP features like classes and inheritance.
-   **No Garbage Collection:** Developers need to allocate and deallocate memory manually, which can be error-prone.
-   **No Exception Handling:** C language does not provide any library for handling exceptions.

## ️ Applications of C Programming

-   **System Programming:** Operating systems, firmware, language translators.
-   **Embedded Systems:** Microcontrollers, industrial controllers.
-   **Compiler and Interpreters:** Language compilers and interpreters.
-   **Database Systems:** DBMS and RDBMS engines (e.g., MySQL).
-   **Networking Software:** Protocols, routers, and network utilities.
-   **Game Development:** Games and game engines.
-   **Scientific and Mathematical Applications:** Simulations, numerical analysis.
-   **Text Editor and IDEs:** Vim, Emacs.

## 🚀 Getting Started with C Programming

To learn C effectively, we need to understand its structure first. A typical structure of a C program includes several parts:

### 1. Include Header Files
Include necessary header files that contain declarations of functions, constants, and macros.

-   `stdio.h`: Provides input and output functions like `printf` and `scanf`.
-   `stdlib.h`: Contains functions involving memory allocation, `rand` function, etc.
-   `math.h`: Includes mathematical functions like `sqrt`, `sin`, `cos`.
-   `string.h`: Includes functions for manipulating strings.
-   `ctype.h`: Functions for testing and mapping characters.
-   `stdbool.h`: Defines the boolean data type.
-   `time.h`: Functions for working with date and time.
-   `limits.h`: Defines various implementation-specific limits on integer types.

### 2. Macros and Constants
Define any macros or constants that will be used throughout the program.

```c
#include <stdio.h>
#define PI 3.14159

int main() {
   float radius = 5.0;
   float area = PI * radius * radius;

   printf("Area of the circle: %f\n", area);
   return 0;
}
```

### 3. Global Declarations
Declare global variables and functions that will be used across different parts of the program.

```c
#include <stdio.h>

// Global variable declaration
int globalVariable;

int main() 
{
   // Rest of the program
   return 0;
}
```

### 4. Main Function
Every C program must have a `main` function. It is the entry point of the program.

### 5. Functions
Define other functions as needed.

```c
#include <stdio.h>

// Global function declaration
void samplefunction();

int main() {
   // Programming statements
   return 0;
}

// Global function definition
void samplefunction () {
   // Function programming statements implementation
}
```

## ❓ FAQs on C Programming

There are some very Frequently Asked Questions (FAQ) about C, this section tries to answer them briefly.

### Is C Programming still relevant today?
C programming came into being in 1972. After more than 5 decades, C is still one of the most popular languages that ranks consistently in the top three. Since C can directly interact with the hardware, it is primarily used in low-level applications such as building operating systems, device drivers, embedded systems, networking etc.

Therefore, C programming skills are very much in demand, in this age also. One's career prospects will definitely be brighter if they have a good proficiency in C programming.

### What are the applications of C Programming?
As a general-purpose language, C is capable of building virtually any kind of software. However, it shines in scenarios requiring direct hardware manipulation, such as creating device drivers, compilers, and system utilities.

It is a top choice for embedded systems and networking software. Because C compiles directly to machine code, it offers superior performance compared to interpreted languages like Python or Java, making it ideal for game development. Its versatility makes it a valuable tool for a wide range of development tasks.

### Is C Programming difficult to learn for beginners?
C is often recommended as a starting point for beginners due to its straightforward syntax. There are numerous online tutorials available to help you get started.

While basic concepts are easy to grasp, mastering advanced features like pointers and memory management can be challenging. However, overcoming these challenges builds a robust understanding of how computers work, making it much easier to learn other programming languages later.

### What are the advantages of learning C Programming?
Learning C offers several key benefits:

-   **Performance:** Since C is compiled directly to machine code, it executes very quickly, offering higher efficiency than interpreted languages like Python or Java. This is critical for game development and embedded systems.
-   **Versatility:** It is a general-purpose language suitable for a wide array of software projects.
-   **Portability:** C code is highly portable. With compilers available for almost every operating system, you can run your code on different platforms with minimal modifications.
-   **Middle-Level Capabilities:** C bridges the gap between high-level and low-level languages, offering high-level abstractions while still allowing direct memory manipulation.
-   **Foundation for Learning:** Mastering C provides a deep understanding of computing concepts, making it significantly easier to pick up other languages.

### What are the key features of C Programming that make it unique?
C programming language has a lot of important features that make it a unique language.

-   **Compiled language:** Unlike many of the modern languages, C is a compiled language. The compiler builds a machine level code that is directly executed by the processor. Hence, it provides a better performance.
-   **Pointer mechanism:** C has the ability to directly access the computer's memory through its pointer mechanism. This leads to its ability to control the hardware a feature that is useful in developing system utilities and embedded systems.
-   **Functions:** You can develop an application in a structured and modular manner with the help of functions. The mechanism of calling functions can be easily plugged into one another.
-   **Extensible:** C has the feature of defining a new data type by combining any of the built-in types. You can thus simulate real-life data structures with C code.
-   **Library functions:** C software is bundled with a large library of utility functions and macros. There are library functions for IO operations, string handling, mathematical and statistical functions, time related functions etc.

### What are the differences between C and other programming languages?
Every programming language has its own characteristic features and difference with others. Here are some of the key points of difference between C and other languages:

-   C is a compiled language, whereas programming languages like Python, Java and JavaScript are interpreted languages.
-   C is a statically typed language. On the other hand, Python and JavaScript are dynamically typed languages.
-   C is an imperative and procedural language. It doesn't support classes and objects. Modern languages are primarily object-oriented.
-   C doesn't have an automatic garbage collection mechanism, which is provided by many other languages like Java and Python.

### How can learning C Programming benefit my career?
A reasonable proficiency in C can be of a lot of advantage for anybody who wants to build a career in software development. C being a general-purpose language, you can use it in different practice projects. C is an open-source language. You can also contribute to open source software development project, that will give you lot of exposure.

A C programmer can pursue a successful career in embedded system development and gaming field. C language acts as a gateway to the software development field, as you can diversify into other programming technologies.

## 💻 C Compiler

We provided an easy, user-friendly, and fast C online compiler, where you can write, save, run, and share your C programs. Click on this link to open it: [C Online Compiler](https://www.tutorialspoint.com/compile_c_online.php).

## 🚀 Hello World in C

Just to give you a little excitement about C programming, here is a small, conventional "Hello, World!" program.

```c
#include <stdio.h>

int main() {

   /* my first program in C */
   printf("Hello, World! \n");
   
   return 0;
}
```

## � Table of Contents

*(This section will be updated as new topics are added.)*

-   [Topic 1: Getting Started](./01-Getting-Started/README.md)
-   [Topic 2: Variables and Data Types](./02-Variables-Data-Types/README.md)
-   [Topic 3: Control Flow](./03-Control-Flow/README.md)
-   [Topic 4: Functions](./04-Functions/README.md)
-   [Topic 5: Pointers and Memory](./05-Pointers-Memory/README.md)

## 🔗 Resources

-   [Resource 1](link-to-resource)
-   [Resource 2](link-to-resource)