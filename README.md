# asm-compiler

## Overview

The asm-compiler project is a compiler designed for a custom programming language. It consists of several components that work together to transform high-level code into assembly language.

## Project Structure

```
asm-compiler
├── src
│   ├── main.asm        # Entry point of the compiler, initializes the compilation process.
│   ├── lexer.asm       # Lexer that tokenizes the source code.
│   ├── parser.asm      # Parser that analyzes tokens and builds a syntax tree.
│   ├── codegen.asm     # Code generator that converts the syntax tree into assembly code.
│   └── utils.asm       # Utility functions for string and number manipulation.
├── docs
│   └── README.md       # Documentation for installation and usage.
├── examples
│   └── hello_world.lvc # Example program in the custom language for testing.
└── README.md           # General information about the project.
```

## Features

- **Lexer**: Breaks down source code into tokens based on defined rules.
- **Parser**: Validates the structure of the code and constructs a syntax tree.
- **Code Generation**: Converts the syntax tree into assembly language instructions.
- **Utilities**: Provides helper functions for various tasks within the compiler.

## Installation

To install the asm-compiler, clone the repository and assemble the source files using an assembler compatible with your system.

## Usage

To compile a program written in the custom language, run the compiler with the source file as an argument. The output will be an assembly file that can be executed on the target platform.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.