# rust-development
Notes while learning Rust and it's development practices

## Resources
* [Rust Programming Language Site](https://www.rust-lang.org/)
* [Documentation](https://www.rust-lang.org/learn)
  * [Rust Programming Language Book](https://doc.rust-lang.org/book/)
  * [Rust Reference](https://doc.rust-lang.org/reference/index.html)
  * [Rustonomicon](https://doc.rust-lang.org/nomicon/index.html)
  * [The Cargo Book](https://doc.rust-lang.org/cargo/index.html)
* [User Forum](https://users.rust-lang.org/)
* [crates.io Rust package registry](crates.io)
* [Jetbrains Rust Plugin](https://plugins.jetbrains.com/plugin/8182-rust)
  * *Boo! No Debugger - Requires CLion*

## Dev Setup
* While I do like to manage my installs with Homebrew, it seems like most folks are just running the downloadable installation script, per [Install Rust](https://www.rust-lang.org/tools/install).
  * `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
  * get a login shell
  * Install Rustfmt (code formatter) `rustup component add rustfmt`
  * Install Clippy (code linter) `rustup component add clippy`
