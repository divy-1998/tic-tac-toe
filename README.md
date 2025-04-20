#Simple React Tic-Tac-Toe
A basic implementation of the clasic Tic-Tac-Toe game built with 

## Features
- 2-Player mode (X and O)
- Detects the winner
- Simple UI using plain CSS
- React functional components with Hooks

## Tech Stack
- [React]
- [vite]
- Css

## Getting Started

### 1.Clone the repo
``` bash
git clone
cd tic-tac-toe


### 2.Install dependencies
npm install

### 3.Start the development server
npm run dev

### 4.Open in browser
Go to http://localhost:5173 to play the game!

Project Structure
Attach image

![image alt](https://github.com/divy-1998/tic-tac-toe/blob/main/Screenshot%202025-04-20%20184124.png?raw=true)

How it Works
- The board is a 3x3 grid of <Square /> components.
- State is managed using React's useState:
    - squares: current state of the board.
    - xIsNext: tracks which player's turn it is.
- calculateWinner() checks for a win after every move.

Possible Improvements
- Add a reset button
- Add score tracking
- Add AI opponennt9vs computer mode)
- Add sound effects or animations

License
Feel free to use or modify this project for learning or fun.


