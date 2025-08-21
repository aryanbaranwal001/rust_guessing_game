# Rust Guessing Game

A simple number guessing game implemented in Rust as part of the [Rust Programming Language Book](https://doc.rust-lang.org/book/) tutorial.

## Description

This is a command-line guessing game where the computer generates a random number between 1 and 100, and the player tries to guess it. The game provides feedback after each guess, telling the player whether their guess is too high, too low, or correct.

## How to Play

1. Clone the repo and `cd` into `rust_guessing_game`
2. Run the game using `cargo run`
3. The game will prompt you to enter a guess
4. Type a number between 1 and 100 and press Enter
5. The game will tell you if your guess is:
   - **Too small** - try a higher number
   - **Too big** - try a lower number
   - **Correct** - you win!
6. Keep guessing until you find the correct number


## Project Structure

```
rust_guessing_game/
├── src/
│   └── main.rs          # Main game logic
├── Cargo.toml           # Project configuration and dependencies
├── Cargo.lock           # Dependency lock file
└── README.md            # This file
```

## About

This project is from Chapter 2 of [The Rust Programming Language Book](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html) and serves as an introduction to common Rust programming concepts.
