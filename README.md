# Project README

## Overview
This project is a C application that demonstrates the usage of an ObjectNotation library to parse, access, and manipulate data stored in a file. The application includes features such as reading, writing, and accessing data within a structured format.

## Features
- Parsing of data from a specified file using ObjectNotation.
- Accessing specific entries within the parsed data structure.
- Printing the entire data structure.
- Writing the modified data structure back to a file.

## Project Structure
The project consists of the following files and directories:

### Prerequisites
- C/C++ Compiler (GCC, Clang)
- Make utility
- Standard development tools

## Build & Run
To build and run the project, follow these steps:

1. **Navigate to the project directory:**
   ```sh
   cd <Project>
   ```

2. **Build for Linux:**
   ```sh
   make -f Makefile.linux all
   ```
   To execute the built application:
   ```sh
   make -f Makefile.linux exe
   ```

3. **Build and run for Windows (using Wine):**
   ```sh
   make -f Makefile.wine do
   ```

4. **Build for WebAssembly:**
   ```sh
   make -f Makefile.web all
   ```
   To execute the built WebAssembly application:
   ```sh
   wasmtime build/Main.wasm
   ```

5. **Build and run for Wine (specifically):**
   ```sh
   make -f Makefile.wine do
   ```

6. **Clean the build directory:**
   ```sh
   make -f Makefile.linux clean
   ```

By following these steps, you can successfully build and run the project on different platforms using the provided makefiles.