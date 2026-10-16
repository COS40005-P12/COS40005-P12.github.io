# User Manuals

User manuals providing information about how to use different parts of the project.

## Building

To build the book, you must first install the `mdbook` executable.

The simplest way to install it is to run `cargo install mdbook`

Make sure Cargo's binary directory is in your path!

To do this on linux, put this in your shell's auto-execute file (.bashrc, .zshrc): `export PATH="$HOME/.cargo/bin:$PATH"`

Run `mdbook help` to learn how to use it.

Refer to the [mdBook Book](https://rust-lang.github.io/mdBook/index.html) for more detailed usage information.

While you have `mdbook serve` running, adding a new entry to [SUMMARY.md](src/SUMMARY.md) will create the file automatically.
