# Introduction

## History of the compiler

What is the history of compiler development? It was during 1951, that Grace Hopper wrote the first compiler program which 
turned the language statements into 0's and 1's for the computer to comprehend. This particular programming technique lead
to faster programming where as previously a programmer had to do work by hand. What was the first compiled coded language?
It was during 1952 which Autocode, as the first compiled programming language which could be translated directly into
machine code through a program called a compiler. It can be noted what was used before the compiler was the assembly language 
for every processor the first language is assembly language which was derived from machine code; which the instruction set was 
designed first then the hardware to implement it; then the assembler, then compilers. After World War II, Grace Hopper
had worked on the first commercial computer called the UNIVAC. During 1953 Hopper invented the high level programming language A-O
that used words and expressions to program the UNIVAC. Hopper also created the first modern day compiler which coined the
phrase BUG.

## What A Compiler Is
A Compiler is a computer program that processes code that has been written and converts it into another programming language. Usually it is used to translate a high level programming language into machine code to allow the computer to run the code. It does this via the six phases found below. Despite this being the most common use for a compiler they can also be used to convert between any languages a compiler exists to compile between, this can be helpful to convert certain things between different operating systems, or languages. 
# Process 
The process of compiling is explored below but involves intaking the code from a higher level language, and running the three processes listed below. It will then generate an intermediate code which must represent the original code without losing any information, while also being independent of any operating system or format. For java this is called the Java Bytecode, while for .NET languages it is called Common Intermediate Language, and is used for all languages in that family. These intermediate languages are so named because they are typically not written by humans, but are also not the final destination machine code. Rather they are a middle point that is easier to process and optimize than either end of the process. Once this code has been generated it will sometimes be analyzed and optimized automatically by the compiler in order to improve program performance. Once this process is complete the compiler will do further cpu specific optimizations and then finally convert the code to the output code, typically a given device's machine code, which it will then be able to run.

## phases of compilers

There are six phases of the compiler which are: 1) Lexical Analysis, 2) Syntactic Analysis or Parsing, 3) Semantic Analysis, 
4) Intermediate Code Generation, 5) Code Optimization and 6) Code Generation. Discussion will be made on the first three phases of 
compilers which are: 1) Lexical Analysis, 2) Syntactic Analysis, and 3) Semantic Analysis.

1. Lexical Analysis: Lexical analysis or Lexical analyzer is the initial stage or phase of the compiler. This phase scans the source code
and transforms the input program into a series of a tokens.
A token is basically the arrangement of characters that defines a unit of information in the source code.

Roles and Responsibilities of Lexical Analyzer
•	It is accountable for terminating the comments and white spaces from the source program.
•	It helps in identifying the tokens.
•	Categorization of lexical units.

2. Syntax Analysis:
In the compilation procedure, the Syntax analysis is the second stage. Here the provided input string is scanned for the validation of the structure of the standard grammar. Basically, in the second phase, it analyses the syntactical structure and inspects if the given input is correct or not in terms of programming syntax.
 
It accepts tokens as input and provides a parse tree as output. It is also known as parsing in a compiler.
Roles and Responsibilities of Syntax Analyzer
•	Note syntax errors.
•	Helps in building a parse tree.
•	Acquire tokens from the lexical analyzer.
•	Scan the syntax errors, if any.

3. Semantic Analysis: In the process of compilation, semantic analysis is the third phase. It scans whether the parse tree follows the guidelines of language. It also helps in keeping track of identifiers and expressions. In simple words, we can say that a semantic analyzer defines the validity of the parse tree, and the annotated syntax tree comes as an output.
Roles and Responsibilities of Semantic Analyzer:
•	Saving collected data to symbol tables or syntax trees.
•	It notifies semantic errors.
•	Scanning for semantic errors.

https://byjus.com/gate/phases-of-complier-notes/                reference to above

![phases of compiler](https://www.tutorialspoint.com/compiler_design/images/compiler_phases.jpg)







## Heading 4

# Conclusion
