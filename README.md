[![dependency status](https://deps.rs/repo/github/iSaNsOT/RuSht/status.svg)](https://deps.rs/repo/github/iSaNsOT/RuSht)

# RuShT

This is a basic shell made with Rust.

## Features
- [x] Basic shell functionality
- [x] Command execution
- [x] Built-in commands (cd, exit)
- [x] Actual directory indicator (ex: /home/user>)
- [x] Background process execution ``&``-> Could be improved
- [x] Posibility to check the background processes (``jobs`` command)
- [x] Posibility to kill the background processes (``kill <pid>`` command)
- [x] Pipe support
- [x] Colours 🌈
- [ ] Tab completion
- [ ] ; implementation
- [ ] || and && implementation
- [ ] Input/output redirection
- [ ] Signal handling
- [ ] Environment variable support
- [x] Command history
- [x] Arrow functions (Up / Down for history) (Right / Left for command editing)
- [ ] Error handling
- [ ] Aliases
- [ ] Scripting support

## Usage
Build the solution (executable) with:
```sh
cargo build
```
  
It's also possible to build and run directly with:
```sh
cargo run
```

To quit:
```sh
exit
```
