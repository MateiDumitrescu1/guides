# Windows
## Guides
https://code.visualstudio.com/docs/languages/rust - very good

## Instalation
1. install the Rust Analyzer VSCODE extension
2. install Rust from https://rustup.rs/

## Debugging setup
1. install the VSCODE C++ extensions
2. go to settings in VSCODE -> search "allow breakpoints" and turn the setting on
3. set a breakpoint in a Rust file
4. in the command bar, type debug and rust-analyzer:debug comes up. run this, and it should start debugging

## Checks
```bash
cargo --version
cargo new test # creates a project called test
# run the src/main.rs file, see the console output
cargo run # run the project without building, see the console output
cargo build
.\target\debug\test.exe # run the .exe file created
cargo build --release
.\target\release\test.exe # run the .exe file created
```