# Number-Guessing-Game
A beginner-friendly Python number guessing game featuring two different implementations.

# 🎯 Guess The Number Game

A simple and fun command-line game where you try to guess a secret number between **1 and 100**.  
This project includes two versions of the game:

✅ One **without using any library** for random number generation  
✅ One **using the built-in `random` module** for true random behavior

---

## 🚀 Features

- Interactive gameplay
- User-friendly input validation
- Play again option included 🎮
- Lightweight and beginner-friendly
- Two different approaches to number-generation

---

## 🧩 Project Structure
Guess-The-Number-Game/
│
├─ version1_no_random/
│ └─ guess.py
│
├─ version2_with_random/
│ └─ guess.py
│
└─ README.md

---

## 🕹️ How to Play

1️⃣ Run the game in your terminal  
2️⃣ Enter a number between **1 and 100**  
3️⃣ The program will tell you if your guess is:
- 🔼 Too high
- 🔽 Too low
- ✅ Correct

4️⃣ You can choose to play again!

---

## 💡 Version 1 — Without Using Random Library

This version simulates randomness using a changing `object()` memory ID.

📌 Run:
```bash
python version1_no_random/guess.py
