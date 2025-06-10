# README for ASM Compiler

## Overview

The ASM Compiler is a project designed to compile a custom programming language into assembly code. This compiler consists of several components, including a lexer, parser, and code generator, which work together to transform high-level language constructs into low-level assembly instructions.

## Project Structure

- **src/**: Contains the source code for the compiler.
  - **main.asm**: Entry point of the compiler that initializes the compilation process by invoking the lexer and parser.
  - **lexer.asm**: Implements the lexer that breaks the source code into tokens, defining rules for recognizing various language elements.
  - **parser.asm**: Contains the parser that analyzes tokens from the lexer and constructs a syntax tree, ensuring the program's structure is correct.
  - **codegen.asm**: Responsible for generating assembly code from the syntax tree, converting high-level constructs into assembly instructions.
  - **utils.asm**: Includes utility functions used across other modules, such as string and number manipulation.

- **docs/**: Documentation for the project.
  - **README.md**: Provides installation and usage instructions for the compiler.

- **examples/**: Contains example programs written in the custom language.
  - **hello_world.lvc**: A sample program that can be used to test the compiler.

- **README.md**: General information about the project, including its goals and main features.

## Installation

To install the ASM Compiler, clone the repository and assemble the source files using an assembler compatible with your system.

## Usage

To compile a program written in the custom language, run the compiler with the source file as an argument. The output will be an assembly file that can be executed on your system.

## Contributing

Contributions to the ASM Compiler are welcome. Please submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.