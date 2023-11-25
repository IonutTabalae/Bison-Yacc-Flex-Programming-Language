# Bison-Yacc-Flex Programming Language: A Custom Compiler Construction Project

## Overview
This project is a **custom programming language** developed using **Bison**, **Yacc**, and **(F)lex**. The language has a syntax similar to C and supports a variety of data types including int, float, char, bool, and string. It allows for complex operations and function definitions, and includes control structures such as if-else, while, and for loops. The language also supports arrays and matrices for int, float, and char data types, and allows for the definition of new types with the 'newType' keyword. Additionally, it can handle variable declaration, initialization, and assignment, and includes error handling for these operations.

## Features
- **Data Types**: Supports int, float, char, bool, and string data types.
- **Functions**: Allows defining functions with different parameter types.
- **Operations**: Supports arithmetic and logical operations.
- **Control Structures**: Includes control structures such as if-else, while, and for loops.
- **Arrays**: Supports arrays for int, float, and char data types.
- **Custom Types**: Allows defining new types with the 'newType' keyword.
- **Variable Management**: The language can handle variable declaration, initialization, and assignment. It also supports constant variables.
- **Error Handling**: The language includes error handling for variable declaration and assignment.

## Technologies
This project is implemented using several technologies:

- **Bison**: A parser generator that is part of the GNU Project. Bison reads a specification of a context-free language, warns about any parsing ambiguities, and generates a parser (either in C, C++, or Java) which reads sequences of tokens and decides whether the sequence conforms to the syntax specified by the grammar. [Official Documentation](https://www.gnu.org/software/bison/manual/bison.html)

- **Yacc (Yet Another Compiler-Compiler)**: A computer program for the Unix operating system developed by AT&T. It is a Look Ahead Left-to-Right (LALR) parser generator, generating a parser, the part of a compiler that tries to make syntactic sense of the source code, specifically a LALR parser, based on an analytic grammar written in a notation similar to Backus-Naur Form (BNF).

- **(F)lex**: A tool for generating scanners: programs which recognized lexical patterns in text. (F)lex reads the given input files, or its standard input if no file names are given, for a description of a scanner to generate. [Official Documentation](https://ftp.gnu.org/old-gnu/Manuals/flex-2.5.4/html_mono/flex.html)

## Example Usage
Here are some snippets of how to use this programming language:

- **Variable Declaration and Initialization**:
  ```c
  int a = 2;
  int a1 = a;
  int a2=a1;
  int matrice[50][50];
  float vector[100];
  float a0;
  char x;
  bool t;
  string test="Acesta este un string";

- **Function Definition**:
  ```c
  int functie1(char c, int v)
  int functie11(int a, int b)
  int functie2(float xy, float yz)

- **Custom Type Definition**:
  ```c
  newType MyType
  {
    const int abcd=2;
  };
  
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
