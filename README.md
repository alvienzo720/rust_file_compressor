# Rust File Compressor

This is a simple Rust program that compresses a source file into a target file using the Gzip compression algorithm provided by the `flate2` crate.

## Prerequisites

Before using this program, you need to have Rust and Cargo installed on your system. If you don't have them, you can install Rust and Cargo from [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install).

## Usage

To use the Rust File Compressor, follow these steps:

1. Clone or download the repository to your local machine.
2. Open a terminal and navigate to the project directory.
3. Run the following command to build the program:

   ```shell
   cargo build --release

 ```shell
cargo run --release -- <source_file> <target_file>


