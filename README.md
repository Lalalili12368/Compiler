# Compiler Project

## Overview
This project is a simple compiler simulation implemented in Java.  
It demonstrates basic compiler phases such as lexical analysis and syntax analysis.

---

## Files Description

### lexer.java
Performs lexical analysis by converting input code into tokens such as keywords, identifiers, numbers, and operators.

### parser.java
Performs syntax analysis and checks whether the token sequence follows valid grammar rules.

### main.java
Acts as the driver program. It connects lexer and parser and executes the overall compilation process.

---

## Features

This compiler can detect:

- Syntax errors (missing operators, incorrect structure)
- Semantic errors (invalid or undefined expressions)
- Extra or mismatched brackets
- Invalid tokens and expressions
- Improper operator usage

---

## How It Works

1. Input code is taken by the main program
2. Lexer breaks it into tokens
3. Parser checks grammar and structure
4. Errors are detected and reported if found

---

## Purpose
The purpose of this project is to understand how a compiler processes code step by step and how errors are detected during compilation.

---

## Author
Dharitree / 0182310012101066
 
