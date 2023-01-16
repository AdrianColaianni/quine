# Quine

These are a collection of [quine](https://en.wikipedia.org/wiki/Quine_\(computing\)) programs I've written.

- quine.rs
    - This is a rust version, which can be compiled with `rustc quine.rs`
- quine.c
    - This is a 64 bit C quine, which can be compiled with `gcc -w quine.c`
- quine32.c
    - This is a 32 bit C quine, which can be compiled with `gcc -m32 -w quine32.c`
    - This program is 12 characters shorter than the 64 bit version, due to the ability to use an int to store a character pointer.  This isn't possible in 64 bit because the addressable memory space exceeds the limit of integers.
- quine.sh
    - Quine written in shell script.  Tested in bash & zsh
    - I personally had the most fun with this one
