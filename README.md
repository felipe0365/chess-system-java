# ♟️ Chess System in Java

Welcome to the **Chess System** project! This application is a chess game implemented in Java, demonstrating concepts of **Object-Oriented Programming (OOP)** such as encapsulation, inheritance, polymorphism, and more. The goal is to provide an interactive console-based chess game with full gameplay functionality, including special moves like castling, en passant, and promotion.

## 🧩 Project Overview

This project was developed as part of the **Object-Oriented Programming with Java** course, following a structured approach to applying fundamental OOP principles.

### Features
- 🎮 Full chess game implementation
- 🧑‍🏫 Utilizes key OOP concepts such as:
  - Encapsulation
  - Inheritance
  - Polymorphism
  - Abstract classes and methods
- 📑 Defensive programming with custom exceptions
- ♟️ Supports special chess moves:
  - Castling
  - En passant
  - Pawn promotion
- 🎨 Console-based UI with colored piece printing (depending on terminal support)

## 🛠️ Technologies Used

- **Java**: The entire project is written in Java, leveraging OOP principles.
- **Git**: Version control for tracking the development progress.
- **GitHub**: Hosting the project repository and showcasing the development process.

## 📚 Key Concepts

- **Positioning**: The game uses a matrix to represent the chessboard and handle piece movements.
- **Encapsulation & Defensive Programming**: Classes are designed with encapsulation in mind, preventing direct access to internal attributes, and utilizing custom exceptions to manage invalid states.
- **Inheritance & Polymorphism**: The piece hierarchy leverages inheritance, with abstract methods to define possible moves for each piece.
- **Custom Exceptions**: `BoardException` and `ChessException` are used to handle invalid board positions and game logic.

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/felipe0365/chess-system-java.git
2. Open the project in your favorite Java IDE (e.g., IntelliJ, Eclipse).
3. Compile and run the "Main" class to start the game in the console.
4. Follow the on-screen instructions to move the chess pieces and enjoy the game!

## 📝 How to Play

- The game is played in the terminal. Players alternate turns by inputting chess moves in standard chess notation (e.g., `e2 e4`).
- Special moves like castling, en passant, and pawn promotion are supported.
- The game automatically checks for **check** and **checkmate** conditions.

## 🔍 Project Structure

- `Position`: Represents a position on the chessboard (row and column).
- `Piece`, `Board`: Handle pieces and board state.
- `ChessPiece`, `ChessMatch`: Implements the game logic and rules.
- `UI`: Manages the console-based user interface, including board printing and move input.

## 🏆 Special Moves

- **Castling**: King and rook move together under specific conditions.
- **En Passant**: A special capture move for pawns.
- **Promotion**: When a pawn reaches the opposite end of the board, it can be promoted to another piece (usually a queen).

## 📷 Preview
- Here's a snapshot of the console interface with a sample board:
  ```css
    a b c d e f g h
  8 - - - - - - - - 
  7 - - - - - - - - 
  6 - - - - - - - - 
  5 - - - - - - - - 
  4 - - - - - - - - 
  3 - - - - - - - - 
  2 - - - - - - - - 
  1 - - - - - - - - 

