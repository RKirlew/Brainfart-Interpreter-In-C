# Brainfart-Interpreter-In-C
Brainfart is a toy language made by me. It was inspired by Brainf*ck,however Brainfart is somewhat simplified. This was made by a very
tired individual who also cries in the shower,forgive me.


# Brainfart Programming Language

## Introduction

**Brainfart** is a simplified version of the Brainf*ck programming language. It was created as a fun and personal project, inspired by the complexity and challenge of Brainf*ck. **Brainfart** aims to be an easier and less intimidating implementation, while still providing a unique experience for low-level programming.

This implementation of **Brainfart** supports basic operations such as memory manipulation (`>`, `<`, `+`, `-`), I/O operations (`.`, `,`), and some additional commands (`*`, `:`, `^`).

---

## Features

- **Memory Manipulation**:
  - `>`: Increment the memory pointer.
  - `<`: Decrement the memory pointer.
  - `+`: Increment the value at the current memory pointer.
  - `-`: Decrement the value at the current memory pointer.

- **Input/Output**:
  - `.`: Output the ASCII value of the current memory pointer.
  - `,`: Accept input and store it in the current memory pointer.

- **Special Commands**:
  - `*`: Increment the value by 10.
  - `:`: Decrement the value by 10.
  - `^`: Square the value at the current memory pointer.

- **Looping**:
  - `[` and `]`: Loop until the memory at the current pointer is 0.

---

## Code Example

```c

*******++.>*^+.>*^*--.>*^*--.>*^*+.>.>*^:---.>*^*+.>*^*++++.>*^*--.>*^.>***+++. // Prints "Hello World!"
  
