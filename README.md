# rust-cli-calculator
# Rust CLI Calculator

A simple command-line calculator written in Rust.

This project was built as part of my journey learning Rust. Rather than relying on external crates or complex abstractions, the focus is on understanding Rust fundamentals such as modules, functions, user input, pattern matching, error handling, and basic project structure.

---

## Features

- ➕ Addition
- ➖ Subtraction

---

## Project Structure

```
calculator/
├── src/
│   ├── main.rs          # Program entry point
│   └── functions.rs     # Calculator functions and input handling
├── Cargo.toml
└── README.md
```

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/calculator.git
cd calculator
```

### Build

```bash
cargo build
```

### Run

```bash
cargo run
```

---

## Example

```
Choose your operation!

1. Addition
2. Subtraction
3. Exit

> 1

Please enter two numbers

10
20

The sum is 30
```

---

## Concepts Practiced

- Functions
- Modules
- Variable declarations
- User input
- Parsing strings into numbers
- Match expressions
- Return values
- Error handling with `.expect()`
- Basic Rust project organization

---

## Future Improvements

- Multiplication
- Division
- Modulus
- Exponentiation
- Better error handling without panics
- Continuous operation until Exit is selected
- Unit tests
- Colored terminal output
- Input retry on invalid values

---

## Built With

- Rust
- Cargo

---

## Author

**Ayush Yadav**

Learning Rust one project at a time.