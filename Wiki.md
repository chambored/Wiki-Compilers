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

##phases of compilers

There are six phases of the compiler which are: 1) Lexical Analysis, 2) Syntactic Analysis or Parsing, 3) Semantic Analysis, 
4) Intermediate Code Generation, 5) Code Optimization and 6) Code Generation. Discussion will be made on the first three phases of 
compilers which are: 1) Lexical Analysis, 2) Syntactic Analysis, and 3) Semantic Analysis.

1. Lexical Analysis: Lexical analysis or Lexical analyzer is the initial stage or phase of the compiler. This phase scans the source code
and transforms the input program into a series of a token.
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





## Heading 3

## Heading 4

# Conclusion
