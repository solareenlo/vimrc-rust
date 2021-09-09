# vimrc-rust
- My `.vimrc` for Rust

## Usage
```shell
# Install Rust toolchain
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
# Ref: https://www.rust-lang.org/ja/tools/install

# or update rustup
rustup update

# Rust fomatter
which rustfmt
# Rust linter
which cargo-clippy
# If it is not installed, execute the following command.
rustup component add rustfmt clippy
# Ref: https://emacs-jp.github.io/env/rust

# Install Rust LSP Server
rustup component add rls rust-analysis rust-src
# Ref: https://github.com/rust-lang/rls

# Install cargo-edit
cargo install cargo-edit
# Ref: https://emacs-jp.github.io/env/rust
```

## References
- [Rust開発環境構築](https://zenn.dev/m3y/articles/df5a52452cfdbe7cd5eb)
- [Rustプログラミングのための環境構築](https://emacs-jp.github.io/env/rust)
- [rust-lang/rls](https://github.com/rust-lang/rls)
- [Implementations Language Servers](https://microsoft.github.io/language-server-protocol/implementors/servers/)
