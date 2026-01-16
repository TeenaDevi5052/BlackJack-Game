# 🃏 Blackjack Game in Python

A simple command-line Blackjack game written in Python.  
Play against the computer dealer, test your luck, and see if you can hit 21!

---

## 🎮 Features
- Card dealing with realistic values (Ace = 11 or 1, face cards = 10).
- Automatic handling of Blackjack (Ace + 10 = 21).
- Computer dealer logic (draws until reaching 17 or higher).
- Interactive gameplay with user input (`y` to draw another card, `n` to stand).
- Clear win/lose/draw messages with fun emojis 😃😢.

---

## 🖥️ How to Play
1. Run the script in your terminal:
   ```bash
   python blackjack.py
## Example GamePlay
Do you want to play the game?(yes or no): yes

Your Cards [11, 10]
Current Score: 21
Computer Cards [9, 7]
Computer Score: 16

Your final hand is [11, 10], final score is 21
Computer final hand is [9, 7, 10], final score is 26
You Win 😃!
