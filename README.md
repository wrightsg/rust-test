# Rust testing ground

Repository for Rust related tests and code snippets.

# Documentation

* Official homepage: https://www.rust-lang.org/en-US/
* The Rust Programming Language (2nd edition): https://doc.rust-lang.org/book/second-edition/

# Setup

Setting up various Rust related tools.

## Compiler

Setting up the compiler.

### Windows (MSYS2)

To install the 64-bit toolchain

````
pacman -Su mingw64/mingw-w64_64-rust 
````

## IDE

Setting up an IDE.

### IntelliJ Rust plugin (Windows, MSYS2)

There exists an IntelliJ plugin for Rust, see https://intellij-rust.github.io/. The plugin is compatible with any IntelliJ based IDE, e.g. PyCharm.

1. Download and install PyCharm (community edition) from https://www.jetbrains.com/pycharm/
2. Install the Rust plugin: Plugins > Browse Repositories > Seach for "Rust"; install the plugin and restart PyCharm
3. Create new project: New Project > Rust > Toolchain location: C:\msys64\mingw64\bin, Standard library location: C:\msys64\mingw64\lib

# Compiling and executing

Compiling Rust code.

## Windows (MSYS2)

````
rustc hello_world.rs
./hello_world.exe
````