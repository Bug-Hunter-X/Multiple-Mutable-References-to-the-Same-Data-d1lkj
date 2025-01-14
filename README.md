# Multiple Mutable References in Rust

This repository demonstrates a common error in Rust: attempting to create multiple mutable references to the same piece of data.  Rust's borrow checker prevents this to ensure data integrity and avoid race conditions. The example shows how to fix this using techniques like cloning or using different parts of data.

## Running the Code

1. Clone the repository.
2. Navigate to the directory.
3. Run `rustc bug.rs` and `rustc bugSolution.rs` to compile.
4. Execute `./bug` to see the compiler error, and `./bugSolution` to see the corrected code in action.