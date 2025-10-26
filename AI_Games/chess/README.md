# ♟️ Chess Game

A simple chess game implemented in Python using the Pygame library. It features a basic AI that calculates the optimal move by peeking **DEPTH** moves ahead. The AI assesses positions and scores only.

![Chess Game Demo](demo.gif)

---

## 📖 Introduction

This is a basic implementation of a chess game with a graphical user interface. The game allows two players to make moves on a standard chessboard. Additionally, there is an AI opponent that uses **negamax algorithm** and **alpha-beta pruning** for move selection.

---

## ✨ Features

### 🖥️ Graphical User Interface
- User-friendly graphical interface developed using the Pygame library

### 👥 Two-player Mode
- Play against a friend in human vs. human gameplay
- Enjoy the classic chess experience with two human players

### 🤖 AI Opponent
- Challenge yourself against an AI opponent equipped with:
  - Negamax algorithm
  - Alpha-beta pruning
  - Configurable difficulty levels

### ♔ Game Rules & Mechanics
- Full implementation of chess rules including:
  - Checkmate detection
  - Stalemate detection
  - Legal move validation

### 🎯 Advanced Chess Mechanics
- **Pawn Promotion** - Promote pawns reaching the 8th rank
- **En Passant** - Special pawn capture move
- **Castling** - King and rook special move

### ↩️ Game Controls
- **Undo Move:** Press `Z`
- **Reset Board:** Press `R`

### 🎨 Customization
- Multiple chess board color themes
- Different piece styles

### 🔊 Audio & Visual Effects
- Piece movement sounds
- Capture sounds
- Visual move highlights

---

## ♟️ Special Moves

### En Passant
En passant is a special pawn capture that can occur when an opponent's pawn moves two squares forward from its starting position, landing beside your pawn. You can capture it as if it had only moved one square.

### Pawn Promotion
When a pawn reaches the opposite end of the board (8th rank), it can be promoted to:
- Queen ♕
- Rook ♜
- Bishop ♗
- Knight ♞

### Castling
A special move involving the king and either rook, where:
- The king moves two squares toward the rook
- The rook moves to the square the king crossed

---

## 🎮 How to Play

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/anuragjain-git/chess-bot.git
   cd chess-bot
