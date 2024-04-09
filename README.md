# go-interpreter
This project serves as a tree-walking interpreter for a C-like programming language.

The language includes variable bindings, integers, booleans, and arithmetic expressions.
Additionally, the language provides build-in functions, first-class, closures, and higher order functions.
Built-in data structures includes string data structure, array data structure, and a hash data structure.

The interpreter consists of five major parts:
    - a Lexer
    - a Parser
    - an Abstract Syntax Tree (AST)
    - an Interval Object System
    - an Evaluator