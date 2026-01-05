# Custom Language Compiler

This repository contains a **compiler for a custom-designed programming language**, developed as part of the *Formal Languages and Compilers* course.

The compiler translates programs written in the custom language into **JVM-compatible bytecode**, generated using **Jasmin**.

The project covers the complete compilation pipeline, from lexical analysis to code generation.

---

## Project Overview

The compiler implements the following phases:

- **Lexical analysis (Lexer)**
- **Syntax analysis (Parser)**
- **Semantic analysis**
- **Intermediate representation and evaluation**
- **Code generation for the JVM**

The final output is a `.j` file compatible with **Jasmin**, which can be assembled into Java bytecode and executed on the Java Virtual Machine.

---

## Language Features

The source language was designed specifically for this project and includes:

- Variables and basic data types
- Expressions and control flow constructs
- Function or procedure definitions (if applicable)
- Static semantic checks

The language design prioritizes clarity and suitability for compiler construction rather than expressiveness.

---

## Code Generation

The backend generates **Jasmin assembly code**, which is then assembled into JVM bytecode.

This approach makes the compilation process explicit and educational, exposing:
- Stack-based execution model
- JVM instruction set
- Low-level control flow and data manipulation

---

## Technologies Used

- **Java**
- **Jasmin assembler**
- Lexer and parser generators (if applicable)
- JVM bytecode

---
