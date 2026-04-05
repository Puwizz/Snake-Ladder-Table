# Snake-Ladder-Table
This was my final project for a Python programming course in the second semester of my 11th grade year. It's a game playable via the terminal, inspired by the classic Snakes and Ladders game.

## 🌟 Key Features

- **Dynamic Player Management:** Supports more 2 players with automated turn-cycling logic.
- **Deterministic Game Board:** Implements a grid-based system with pre-defined mapping for "Snakes" (penalties) and "Ladders" (boosts).
- **Interactive Terminal UI:** Features custom ASCII-rendered boards and real-time movement updates for an engaging user experience.

## 🛠️ Technical Stack & Concepts

- **Language:** Python 3.x
- **Data Structures:** Utilized Nested Lists (2D Arrays) for board representation and Dictionaries for tile-event mapping.
- **Algorithms:** - **Randomized Simulation:** Used the `random` library to simulate unbiased dice rolls.
  - **State Tracking:** Managed player coordinates and winning condition checks within a continuous Game Loop.
- **Input Validation:** Handled user inputs to ensure robust execution during player selection and turn transitions.
