# Introduction

Compilers have played a pivotal role in the progress of computing since their inception in the early 1950s.
While serving as a bridge between humans and computers, they enable the use of higher-level languages that 
are more comprehensible and user-friendly than low-level machine code. This page takes you through the history 
of compiler development, beginning with Grace Hopper's groundbreaking work on the first compiler. 
We will also discuss the differences between compiled and interpreted languages, as well as the various 
phases and types of compilers that are prevalent today.

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

## Process 
The process of compiling is explored below but involves intaking the code from a higher level language, and running the three processes listed below. It will then generate an intermediate code which must represent the original code without losing any information, while also being independent of any operating system or format. For java this is called the Java Bytecode, while for .NET languages it is called Common Intermediate Language, and is used for all languages in that family. These intermediate languages are so named because they are typically not written by humans, but are also not the final destination machine code. Rather they are a middle point that is easier to process and optimize than either end of the process. Once this code has been generated it will sometimes be analyzed and optimized automatically by the compiler in order to improve program performance. Once this process is complete the compiler will do further cpu specific optimizations and then finally convert the code to the output code, typically a given device's machine code, which it will then be able to run.

## Phases of Compilers

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







## Types of Compilers 
After acknowledging the Phases of Compiler design we can begin to understand the process of a Compiler pass. Single Pass is one type of Compiler pass and Two/Multi-Pass is another type. Furthermore, a Compiler pass is the crossing of a Compiler throughout a complete program. 
Single Pass or the One Pass compiler is a specific type of Compiler that is passed through the section of all compilation units only one time. It may be beneficial to note that this Compiler pass is smaller and quicker than the Multi-Pass Compiler but is also deemed to be less-efficient when compared to the Multi-Pass Compiler. Obvious to its name, the Single Pass Compiler operates only once from the lexical analyzer to the code generator and then returns for the following read. Because the Single Pass Compiler is so limiting to expression, it is not ideal for optimal solutions. 
Two Pass Compilers or Multi-Pass Compilers are a type of Compiler that processes the source code of a program multiple times. In the first pass the compiler reads the code, scans it and takes out the tokens to then save the result into an output file. In the second pass the compiler reads that same output file created by the first pass in order to build the syntactic tree and implement the syntactical analysis that can then produce a file that includes the syntactical tree in the output file. In the third pass the compiler reads the output file from the second pass and checks that the tree is correct. The semantic analysis phase’s output is the annotated tree syntax and this pass is continual until the output is produced ideally. In comparison to a Single Pass Compiler, a Multi-Pass Compiler is slower due to the multiple number of passes it has a longer execution time however it is more widely versed and can scan every part of a program.

## Compiled vs Interpreted Languages
Compiled and interpreted languages are two different approaches to running computer programs, with each offering its own set of advantages and disadvantages.

In a compiled language, the source code is written by the programmer and is transformed into an executable program by a compiler. The compiler then translates the high-level code into low-level machine code or bytecode, which is then executed by the computer's hardware or a virtual machine. Examples of compiled languages are C, C++, and Java (which is compiled into bytecode and runs on the Java Virtual Machine(JVM).

Use cases:

    - High-performance applications, like games, operating systems, and embedded systems
    - Programs that require efficient memory management and close interaction with the hardware
    - Applications that need a high level of security and intellectual property protection

Advantages:

    - Faster execution: Compiled code runs faster because it's already translated into machine code or bytecode.
    - Better optimization: Compilers can optimize the code during compilation, potentially leading to better performance.
    - Enhanced security: Compiled code is more difficult to reverse-engineer, helping protect the intellectual property of the software.

Disadvantages:

    - Longer build times: Compilation can be time-consuming, especially for large projects.
    - Less portable: Compiled code may need to be recompiled for different platforms, which can create additional work.
    - Debugging can be more difficult: Errors may be harder to trace back to the original source code since they occur in the compiled version.

In an interpreted language, the source code is executed line by line by an interpreter, which translates each line into machine code and runs it immediately. This approach doesn't require the separate compilation step that compiled languages do. Examples of interpreted languages include Python, Ruby, and JavaScript.

Use cases:

    - Rapid application development and prototyping
    - Scripting and automation tasks
    - Web development and server-side programming

Advantages:

    - Faster development: Interpreted languages allow for quicker development and iteration, as there's no need to compile the code before running it.
    - Better portability: The same code can run on different platforms without recompilation, as long as the interpreter is available.
    - Easier debugging: Errors are reported during runtime, making it simpler to trace them back to the source code.

Disadvantages:

    - Slower execution: Interpreted code generally runs slower than compiled code due to the overhead of interpreting each line during runtime.
    - Less optimization: Interpreters typically don't optimize the code, which may result in lower performance.
    - Weaker security: Interpreted code is easier to reverse-engineer, making it less secure than compiled code.

Compiled languages generally offer better performance and security, making them suitable for high-performance applications and situations where intellectual property protection is crucial. Interpreted languages, on the other hand, facilitate rapid development and prototyping, with better portability and easier debugging, making them ideal for scripting, automation, and web development tasks.

# Conclusion

The development of compilers has significantly influenced the advancement of computing technology.
 From the pioneering work of Grace Hopper on the first compiler to the sophisticated compilers that 
 underpin modern programming languages, the field of compiler development has persistently evolved to 
 keep pace with the dynamic world of computing. Nowadays, the choice between compiled and interpreted 
 languages allows programmers to strike a balance between performance and rapid development, catering to 
 the specific needs of their projects. As we forge ahead in the realm of technology, compilers will undoubtedly
 maintain their vital role in shaping the future of computing.
