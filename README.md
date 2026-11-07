
#  Tic-Tac-Toe AI – 4×4 Strategy Game

An interactive **Tic-Tac-Toe game with an AI opponent**, developed using Python and Tkinter. Unlike traditional 3×3 Tic-Tac-Toe, this version features a 4×4 game board where players must connect four symbols in a straight line to win.

The game combines a graphical user interface, artificial intelligence, animations, sound effects, and a real-time scoreboard to create an engaging gaming experience.

##  Features

###  Gameplay
- Interactive 4×4 Tic-Tac-Toe board.
- Play against an AI-powered computer opponent.
- Connect four symbols horizontally, vertically, or diagonally to win.
- Alternating starting player between rounds.
- Automatic detection of winning moves and draws.

###  Artificial Intelligence
- **Minimax Algorithm:** Helps the computer evaluate possible moves and select strategic decisions.
- **Alpha-Beta Pruning:** Optimizes the search process by eliminating unnecessary branches.
- **Immediate Win Detection:** Allows the AI to recognize and take winning opportunities.
- **Threat Blocking:** Detects and blocks the player's immediate winning moves.
- **Dynamic Search Depth:** Adjusts the AI's search depth according to the number of empty cells.
- **Strategic Move Evaluation:** Uses a heuristic scoring system to evaluate board positions.

###  User Interface
- Modern dark-themed graphical interface.
- Interactive board with animated X and O symbols.
- Responsive layout that adjusts to window size.
- Full-screen gaming experience.
- Hover effects and interactive buttons.
- Live scoreboard for player wins, computer wins, and draws.
- Visual winning-line animation.

###  Additional Features
- Sound effects for moves, wins, losses, and draws.
- Sound on/off control.
- New Round and Reset Scores options.
- Keyboard shortcuts for convenient navigation.

##  Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Tkinter | Graphical User Interface |
| Minimax | AI decision-making |
| Alpha-Beta Pruning | Search optimization |
| Threading | Running AI calculations separately |
| Queue | Communication between AI thread and GUI |
| Random | Randomized opening and equally scored moves |

##  How the AI Works

The computer opponent uses the Minimax algorithm with Alpha-Beta Pruning to make strategic decisions.

1. The AI examines possible moves on the board.
2. It evaluates potential outcomes from its own perspective.
3. It prioritizes winning opportunities.
4. It blocks the player's immediate winning moves.
5. Alpha-Beta Pruning reduces unnecessary calculations.
6. The AI selects a move based on the highest evaluated score.

The AI also uses a heuristic evaluation function to estimate the strength of board positions when it cannot search all the way to the end of a game.

##  Installation and Setup

### Requirements
- Python 3.8 or later.
- Tkinter support.

No external Python packages are required.

### Step 1: Clone the Repository

```bash
git clone https://github.com/bintemahmood71-prog/Tic-Tac-Toe-AI.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Tic-Tac-Toe-AI
```

### Step 3: Run the Game

```bash
python3 Tic_Tac_Toe_corrected.py
```

*On Windows, you can use `python` instead of `python3`.*

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| F11 | Toggle Full Screen |
| Esc | Exit Full Screen |
| N | Start a New Round |
| R | Reset Scores |
| M | Toggle Sound |

##  AI Testing

The project includes a built-in self-test mode to check important AI functionality.

Run:

```bash
python3 Tic_Tac_Toe_corrected.py --selftest
```

The tests check:
- Winning move detection.
- Opponent threat blocking.
- AI performance against a random opponent.
- AI performance against another AI.

##  Project Objectives

- Apply Artificial Intelligence concepts in a practical game.
- Understand Minimax and Alpha-Beta Pruning.
- Develop an interactive desktop application using Python.
- Explore game-state evaluation and decision-making.
- Improve programming and problem-solving skills.

##  Future Improvements

Potential future enhancements include:
- Multiple difficulty levels.
- Two-player local mode.
- Game history and statistics.
- Customizable themes.
- Improved AI strategy and search optimization.

##  Author

**Ayeza Mahmood**

Computer Science Undergraduate | Python & AI Enthusiast

- GitHub: [bintemahmood71-prog](https://github.com/bintemahmood71-prog)

---

⭐ If you find this project interesting, consider giving the repository a star!
