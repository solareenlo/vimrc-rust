# vimrc-rust
- My `.vimrc` for Rust

## Usage
```shell
# Install Rust toolchain
# Ref: https://www.rust-lang.org/ja/tools/install
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# Rust fomatter
which rustfmt
# Rust linter
which cargo-clippy
# If it is not installed, execute the following command.
rustup component add rustfmt clippy

# Install Rust LSP Server
rustup component add rls

# Install cargo-edit
cargo install cargo-edit
# Ref: https://emacs-jp.github.io/env/rust
```
