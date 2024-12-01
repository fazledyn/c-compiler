# c-compiler
This is a custom compiler written for a subset of C language.


# About
CSE310: Compiler Sessional Project


# A few things about the compiler
- Flex & Bison have been used to develop the compiler
- The compiler generates assembly code for 8086 architecture as IR
- In the assembly code, peephole optimization is done to reduce instructions such as:
  ```asm
  mov  ax, a
  mov  a, ax
  ```
- EMU8086 is used as the emulator to run the generated code
