# -Design-and-Implementation-of-a-Compiler-for-a-C-like-Programming-Language
This project aims to design and implement a compiler for a simplified version of a C-like programming language. The compiler will convert source code written in this language into executable machine code.
Compiler Design

    Language Specification:
        Define the grammar of the C-like language using CFG/BNF notation.
        Describe supported features and limitations.

    Conversion to Automata:
        Use JFLAP to convert the language's grammar into a finite automaton.
        Document the conversion process and any optimizations applied.

    Lexical Analysis:
        Implement a lexer to convert a sequence of characters into tokens.

    Syntax Analysis:
        Develop a parser to construct a parse tree or an abstract syntax tree (AST) from tokens.

    Semantic Analysis:
        Perform type checking and ensure semantic correctness.

    Intermediate Code Generation:
        Generate an intermediate representation of the AST.

    Code Optimization:
        Optimize the intermediate code to improve performance.

    Code Generation:
        Translate the optimized intermediate code into assembly or machine-like code.
