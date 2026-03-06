# ♟ Magnus Chess — Elite AI Browser Chess Engine

![Magnus Chess](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JavaScript-f0a500?style=for-the-badge)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-green?style=for-the-badge)
![Mobile Ready](https://img.shields.io/badge/Mobile-Responsive-blue?style=for-the-badge)

> A fully playable, production-quality browser chess game with a powerful AI engine — built entirely with pure HTML, CSS & JavaScript. No frameworks. No libraries. No dependencies.

**Developed by Sai Krishna × AI**

---

## 🎮 Live Demo

[Click here](https://neurosensen.github.io/Inteli-Chess/)

---

## ✨ Features

### 🤖 AI Engine
- **Alpha-Beta Pruning** — eliminates branches that won't affect the result
- **Iterative Deepening** — progressively searches deeper within a time budget
- **Transposition Tables** — 1M entry cache to avoid re-evaluating positions
- **Quiescence Search** — searches captures beyond the horizon to avoid tactical blindness
- **MVV-LVA Move Ordering** — Most Valuable Victim / Least Valuable Attacker for better cutoffs
- **Piece-Square Evaluation Tables** — positional bonuses for all 6 piece types
- **6 Difficulty Levels** — from Beginner (~800 Elo) to Magnus (~2800 Elo)

### ♟ Full Chess Rules
- Legal move validation
- Castling (kingside & queenside)
- En passant
- Pawn promotion with modal selector
- Check, Checkmate & Stalemate detection
- 50-move draw rule

### 🎨 UI / UX
- Professional dark-themed interface
- Drag-and-drop & tap-to-move support
- Legal move highlighting
- Last move indicator
- Check highlight on king
- Move history panel with algebraic notation
- Material advantage tracker
- Board flip option
- Undo move

### 📱 Responsive Design
- Mobile-first CSS
- Touch drag-and-drop
- Scales from 320px phones to 4K desktops
- No overflow or layout breaking

### 🎵 Audio
- Web Audio API synthesized sound effects (move, capture, check)
- Generative background music
- Volume control & toggle
- Zero external audio files

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/yourusername/magnus-chess.git

# Open in browser
open chess.html
```

That's it. No `npm install`. No build step. No server.

---

## 🗂 Project Structure

```
magnus-chess/
└── chess.html       # Entire game — HTML + CSS + JS in one file
└── README.md        # You are here
```

Everything lives in a single self-contained HTML file — intentionally, for maximum portability.

---

## 🧠 How the AI Works

The AI uses a classic **Minimax** algorithm enhanced with modern engine techniques:

1. **Root search** begins at depth 1 and iterates deeper (Iterative Deepening)
2. **Alpha-Beta pruning** cuts branches that cannot improve the current best score
3. **Move ordering** ensures the best moves are searched first for maximum cutoffs
4. **Transposition table** caches previously seen positions to avoid redundant work
5. **Quiescence search** at leaf nodes keeps searching captures to avoid the horizon effect
6. **Piece-square tables** reward good piece placement (knights in the center, kings behind pawns, etc.)
7. **Noise injection** at lower difficulty levels introduces intentional imprecision for a fair challenge

---

## 🎚 Difficulty Levels

| Level | Name | Elo | Description |
|-------|------|-----|-------------|
| 1 | Beginner | ~800 | Makes frequent blunders |
| 2 | Casual | ~1200 | Plays reasonable moves |
| 3 | Club | ~1600 | Solid club-level play |
| 4 | Expert | ~2000 | Strong positional awareness |
| 5 | Master | ~2400 | Near-perfect tactics |
| 6 | Magnus | ~2800 | Maximum engine strength |

---

## 🛠 Tech Stack

| Technology | Usage |
|-----------|-------|
| HTML5 | Structure & layout |
| CSS3 | Styling, animations, responsiveness |
| Vanilla JavaScript | Chess engine, game logic, UI |
| Web Audio API | Sound effects & background music |
| CSS Grid & Flexbox | Board and responsive layout |

---

## 📸 Screenshots

<img width="675" height="787" alt="image" src="https://github.com/user-attachments/assets/6456fd76-cb39-4551-8d68-aa8150342bb2" />
<img width="684" height="773" alt="image" src="https://github.com/user-attachments/assets/f5c9eea9-03bf-4897-84c3-32805c04a375" />
<img width="836" height="776" alt="image" src="https://github.com/user-attachments/assets/e7286a82-47ac-4736-b9fb-0f7dbcf1dd5c" />







## 👤 Author

**Sai Krishna**,**Itz-Jitesh**
Built in collaboration with AI — a project that demonstrates the power of human creativity + AI execution.

---

> *"Chess is the art of analysis."* — Mikhail Botvinnik
