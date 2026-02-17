# ✊ Rock Paper Scissor — Python Implementation

A command-line implementation of the classic Rock Paper Scissor game built using Python.  
This project demonstrates conditional logic, loops, user interaction, and random number generation.



## 📌 Overview

This is a terminal-based Rock Paper Scissor game where:

- The user selects Rock, Paper, or Scissor.
- The computer randomly generates its choice.
- The winner is determined using conditional logic.
- The player can continue playing until they choose to exit.

The game runs inside a continuous loop and terminates only when the user decides to quit.



## 🎯 Problem Statement

Build an interactive Python program that simulates the Rock Paper Scissor game by handling user input, generating random computer choices, and determining the winner using rule-based logic.



## 🚀 Features

- Interactive CLI-based gameplay
- Emoji representation for visual clarity (✊ 🖐 ✌)
- Random computer choice using `random.randint()`
- Continuous gameplay loop
- Win, Lose, and Draw detection
- Option to replay or exit



## 🧠 Core Logic Design

1. Store possible choices in a list:
   - 0 → Rock (✊)
   - 1 → Paper (🖐)
   - 2 → Scissor (✌)

2. Take numeric input from user.
3. Generate random number between 0 and 2 for computer.
4. Compare user choice and computer choice.
5. Apply rule-based condition checks:
   - Rock beats Scissor
   - Scissor beats Paper
   - Paper beats Rock
6. Ask user whether to continue or exit.



## 🛠️ Tech Stack

- **Language:** Python 3
- **Library Used:** Built-in `random` module
- **Interface:** Command Line (CLI)






