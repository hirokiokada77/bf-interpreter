# bf-repl

This is a Rust implementation of a read–eval–print loop (REPL) for the
Brainfuck programming language.

## Usage

- `mem`: Display a snapshot of the memory around the data pointer.
- `show <addr>`: Display the value of the cell at the specified memory
  address.
- `jump <addr>`: Move the data pointer to the specified memory address.
- `set <value>`: Set the value of the current cell to the specified byte
  (0–255).
- `exit`: Terminate the REPL session.
