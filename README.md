# kuna
First try in compiler design &amp; a simple programming language.

# Documentation

# Development

## Thoughts
- Implemented in C#
  - First as an interpreted language - it will run slowly
  - Then as a compiled language - without optimization
    - Compiled into ARM assembly for Apple M1
- Language specifications
  - Statically-typed language
  - Compiler loads program from file
    - Option to interpret or compile the program
  - Compiler does error reporting with line and column number

## Architecture

### Stages
- Lexical Analysis
- Syntax Analysis
- Semantic Analysis
- Intermediate Code Generation (maybe)
- Code Optimization (later)
- Code Generation

### Some Ideas about Classes
- Lexxer (stage 1-3)
- Interpreter
- Compiler
