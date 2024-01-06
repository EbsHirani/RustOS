# Rust OS

## Run Commands- 
```console
foo@bar:~$ rustup override set nightly
foo@bar:~$ rustup component add rust-src --toolchain nightly-x86_64-unknown-linux-gnu
foo@bar:~$ cargo install bootimage
foo@bar:~$ rustup component add llvm-tools-preview
foo@bar:~$ cargo run
```