
# ♟️ Checkers

A browser-based implementation of the classic Checkers game built with **HTML, CSS, and Vanilla JavaScript**.

The project focuses on implementing the core game mechanics without external libraries, providing a smooth drag-and-drop experience, sound effects, and move validation directly in the browser.

---

<img width="1215" height="898" alt="image" src="https://github.com/user-attachments/assets/f970e36a-db62-4e52-8fad-e68cae52a251" />

---


## Features

* 🎮 Classic 8×8 Checkers board
* 🖱️ Drag & Drop piece movement
* ✅ Real-time move validation
* 🔄 Automatic turn switching
* 🍽️ Piece capture
* 👑 King promotion
* ✨ Highlighting of legal moves
* 🔊 Sound effects for game events
* 🔄 Restart button

---

## Technologies

* HTML5
* CSS3
* Vanilla JavaScript

No frameworks or external libraries are required.

---

## Project Structure

```
checkers/
│
├── index.html          # Game board and page structure
├── css/
│   ├── style.css       # Styling
│   └── futuristic.png  # Background image
│
└── js/
    ├── main.js         # Game logic
    └── Sounds/
        ├── capture.wav
        ├── drag_start.wav
        ├── invalid_move.wav
        ├── promotion.wav
        ├── release.wav
        └── wrong_turn.wav
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/codeformegpt-dev/checkers.git
```

2. Open the project folder.

3. Launch `index.html` in your browser.

No installation or build process is required.

---

## Gameplay

* Dark pieces move first.
* Pieces move diagonally.
* Captures are performed by jumping over an opponent's piece.
* Reaching the opposite side of the board promotes a piece to a **King**.
* Kings gain extended movement abilities.
* Invalid moves are rejected with visual and audio feedback.

---

## Future Improvements

Some possible enhancements include:

* Forced captures
* Multiple captures in a single turn
* AI opponent
* Online multiplayer
* Move history
* Undo/Redo
* Game timer
* Score tracking
* Mobile touch support
* Improved animations

---

## Purpose

This project was created as a learning exercise to practice:

* DOM manipulation
* Event handling
* Drag & Drop API
* Game state management
* Object-oriented thinking
* Front-end application architecture

---

## License

This project is available under the MIT License.

