
# Lexical Analyzer in C++

## Description

This is a simple lexical analyzer (lexer) implemented in C++ that reads an input file (`front.in`), categorizes characters into tokens (such as identifiers, integer literals, operators, and punctuation), and prints the corresponding token type and lexeme for each recognized token. The lexer can identify common programming symbols such as assignment operators, arithmetic operators, parentheses, and numbers.

## Features

- Reads an input file character by character.
- Identifies and categorizes the following tokens:
  - Identifiers (e.g., variable names).
  - Integer literals (e.g., `10`, `20`).
  - Arithmetic operators (e.g., `+`, `-`, `*`, `/`).
  - Parentheses (e.g., `(`, `)`).
  - Assignment operator (e.g., `=`).
- Prints each token type and its corresponding lexeme.
- Skips over whitespace and processes the file until the end.

## Token Types

The program supports the following token types:
- `INT_LIT`: Integer literal (e.g., `10`).
- `IDENT`: Identifier (e.g., `x`).
- `ASSIGN_OP`: Assignment operator (`=`).
- `ADD_OP`: Addition operator (`+`).
- `SUB_OP`: Subtraction operator (`-`).
- `MULT_OP`: Multiplication operator (`*`).
- `DIV_OP`: Division operator (`/`).
- `LEFT_PAREN`: Left parenthesis (`(`).
- `RIGHT_PAREN`: Right parenthesis (`)`).
- `END_OF_FILE`: End of file marker.
