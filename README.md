# Memory Card Game

## Overview
This is a simple memory card game built with HTML, CSS, and JavaScript. The game features a 4x4 grid of cards that players flip to find matching pairs. Cards are shuffled at the start of each game, and the game tracks flipped cards and matched pairs. Matching pairs remain face-up, while non-matching pairs flip back after a short delay. A restart button allows players to reset and shuffle the board for a new game. The design is responsive, ensuring compatibility with both desktop and mobile devices.

## Features
- **Card Flipping**: Click a card to flip it and reveal its front face.
- **Matching Logic**: Find matching pairs to keep cards face-up; non-matching pairs flip back after a delay.
- **Shuffle Function**: Randomizes card positions at the start of the game.
- **Restart Functionality**: Resets the game board and shuffles cards for a new game.
- **Responsive Design**: Adapts to various screen sizes for desktop and mobile play.
- **Clean Code**: Well-documented HTML, CSS, and JavaScript for maintainability.

## Setup Instructions
1. **Clone or Download**: Copy the project files (`index.html`, `styles.css`, `script.js`) to your local machine.
2. **Open the Game**: Open `index.html` in a web browser (e.g., Chrome, Firefox).
3. **No Dependencies**: The game runs entirely in the browser without additional setup or server requirements.

## How to Play
- **Objective**: Find all matching pairs of cards.
- **Gameplay**:
  - Click a card to flip it and reveal its symbol.
  - Click a second card to flip it. If the cards match, they stay face-up. If not, they flip back after a brief delay.
  - Continue flipping pairs until all matches are found.
- **Restart**: Click the "Restart" button in the header to shuffle the cards and start a new game.
- **Winning**: The game is won when all pairs are matched (no explicit win screen is implemented).

## File Structure
- `index.html`: Contains the HTML structure, including the game board container and header with title and restart button.
- `styles.css`: Defines responsive styling for the game, including card animations and layout.
- `script.js`: Implements game logic, including card flipping, matching, shuffling, and restarting.

## Technologies Used
- **HTML**: Structures the game board and UI elements.
- **CSS**: Styles the game with a responsive grid, card flip animations, and mobile-friendly design.
- **JavaScript**: Handles game logic, including shuffling, flipping, matching, and restarting.

## Notes
- The game uses emoji symbols for card faces (e.g., 🐶, 🐱). Modify the `cards` array in `script.js` to use different symbols or images.
- The card flip animation uses CSS transforms for smooth transitions.
- The game is designed for a 4x4 grid (8 pairs). Adjust the grid size by modifying CSS and JavaScript (ensure an even number of cards for pairing).

## Future Enhancements
- Add a move counter or timer to track player performance.
- Implement a win screen or congratulations message when all pairs are found.
- Allow players to choose difficulty levels (e.g., different grid sizes).
- Add sound effects for card flips and matches.
