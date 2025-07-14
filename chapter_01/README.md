# Chapter 1

## Summary
- Install the latest stable version of Rust using `rustup`
- Update to a newer Rust version
- Open locally installed documentation
- Write and run a “Hello, world!” program using rustc directly
- Create and run a new project using the conventions of Cargo

## rustc Recap
- Use `rustc file.rs` to compile the file


## Cargo Recap
- We can create a project using `cargo new`.
- We can build a project using `cargo build`.
- We can build and run a project in one step using `cargo run`.
- We can build a project without producing a binary to check for errors using `cargo check`.
- Instead of saving the result of the build in the same directory as our code, Cargo stores it in the target/debug directory.
- For release version, run `cargo build --release`