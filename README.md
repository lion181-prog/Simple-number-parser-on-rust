# Simple Number Parser (Rust)

A lightweight command-line utility built with Rust that demonstrates how to read a string of numbers from standard input, parse them into integers, and store them in separate variables.

## How It Works

The program captures user input, splits the string based on whitespace, and converts each substring into an `i32` integer. The resulting values are then mapped to specific variables for display.

### Execution Flow:
1. Run the project using `cargo run`.
2. The program pauses for input.
3. User enters: `10 20 30`
4. The program outputs:
   ```text
   i=10
   j=20
   k=30
