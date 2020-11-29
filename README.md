# rust-minigrep

This command line tool was implemented by following the official Rust tutorial:
https://doc.rust-lang.org/book/ch12-00-an-io-project.html

Install Rust and Cargo:

    curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh

Add the following line to your `~/.bashrc` or `~/.zshrc`:

    export PATH="$HOME/.cargo/bin:$PATH"

Run project:

    cargo run <query> <filename>

Run unit tests:

    cargo test

Just compile:

    cargo build

Check code without producing an executable:

    cargo check

Building for release:

    cargo build --release

Open bundled documentation:

    cargo doc --open
