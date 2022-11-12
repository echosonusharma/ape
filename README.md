# Ape programing language and interpreter

For the book [writing an interpreter in go](https://interpreterbook.com/) by thorsten ball.

## Type of Interpreter

It's an interpreter that parse the source code, build an abstract syntax tree (AST) out of it and then evaluate this tree. This type of interpreter is sometimes called "tree walking" interpreter, because it “walks” the AST and interprets it.

### Things it will have

- lexer
- parser
- tree representation
- evaluator

### Language features

- C-like syntax
- variable bindings
- integers and booleans
- arithmetic expressions
- built-in functions
- first-class and higher-order functions
- closures
- a string data structure
- an array data structure
- a hash data structure
