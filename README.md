# Blink-Tac-Toc
Blink Tac Toe is a playful, strategic 2-player twist on the classic Tic Tac Toe — with emojis instead of Xs and Os, and a clever “vanishing emoji” rule that brings the board to life!


# 🎮 Blink Tac Toe

A fun, strategic twist on the classic Tic Tac Toe game — built for the **Darban.ai Frontend Developer Challenge**. In Blink Tac Toe, emojis replace Xs and Os, and players must outwit each other under the clever **vanishing emoji** rule!

## 🚀 Live Demo

👉 [Click here to play Blink Tac Toe](https://your-live-demo-link.com)

## 🛠️ Tech Stack

- **Framework**: React.js
- **Styling**: CSS (Fully responsive)
- **Deployment**: Vercel / Netlify / GitHub Pages (your choice)

---

## 🎮 How to Play

### 🎯 Objective
Be the first player to align three of your emojis — horizontally, vertically, or diagonally — to win the game!

### 🧩 Game Rules

- **3x3 Grid** like classic Tic Tac Toe.
- Each player selects an **emoji category** before starting:
  - Example: 🐶 Animals, 🍕 Food, ⚽️ Sports
- On each turn, a random emoji from the player's category is assigned.
- Players take turns placing their emoji on any empty cell.

### 🔄 Vanishing Emoji Rule

- Each player can only have **3 emojis on the board** at any time.
- When placing a 4th emoji:
  - The **oldest placed emoji** by that player **vanishes** (FIFO logic).
  - The player **cannot place** the new emoji in the same spot as the vanished one.
- This adds a **dynamic twist** and prevents the board from being fully filled.

### 🏆 Winning Condition

- Align 3 of your own emojis (from the same category) in a row, column, or diagonal.
- The game ends instantly with a **“Player X Wins!”** message.

### 🔁 Game Reset

- A “Play Again” button appears after a win to restart the game.

---

## 📱 Responsive Design

The UI is fully responsive and works seamlessly across desktop and mobile screens.

---

## ❓ Help Section

Includes an easy-to-understand help panel explaining:
- Game objective
- Rules
- Turn indicators
- Emoji selection

---

## 💡 Bonus Features (Optional Enhancements)

- [x] Emoji category selection before game start
- [x] Emoji placement animations
- [ ] Highlight winning line
- [ ] Score tracker for multiple rounds
- [ ] Sound effects or haptic feedback
- [ ] Dark/light theme toggle

---

## 🔍 Vanishing Emoji Logic (How It Works)

- Each player's emoji placements are stored in a queue.
- Once a player places their 4th emoji:
  - The **first placed emoji** is removed from both the queue and the board.
  - The original cell is marked temporarily as unavailable for reuse on the same turn.

---

## ⏳ What I’d Improve With More Time

- Add **single-player mode** with AI opponent.
- Polish the animations for better feedback.
- Add **player name input** and **scorekeeping**.
- Enhance accessibility (keyboard navigation, screen reader support).

---

## 📂 Project Structure (React)

