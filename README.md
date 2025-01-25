# Random Number Guessing Game

## Game Description
The **Random Number Guessing Game** is an interactive browser-based game where players guess a randomly generated number within a specified range. The game provides feedback on whether the player's guess is too high, too low, or correct. The objective is to guess the correct number in as few attempts as possible.

---

## Features
1. **Random Number Generation**:
   - A random number is generated at the start of the game using JavaScript's `Math.random()` function.
   - Example range: 1 to 100.

2. **Player Input**:
   - The player enters their guess using an input field.
   - A "Submit" button processes the guess.

3. **Feedback System**:
   - The game tells the player if the guess is:
     - Too high.
     - Too low.
     - Correct.

4. **Attempts Tracker**:
   - The game keeps track of the number of guesses made by the player.

5. **Reset Option**:
   - Once the correct number is guessed, the player can reset the game to play again.

6. **Dynamic Styling**:
   - Feedback messages (like "Congratulations!" or "Try again") are styled dynamically to enhance user experience.

---

## How It Works
1. A random number is generated when the game starts.
2. The player guesses the number by entering it in the input field.
3. The script compares the guessed number with the generated number:
   - If the guess is correct, a success message is displayed.
   - If not, the player gets a hint ("Too high" or "Too low").
4. The player continues guessing until they guess the correct number.
5. A "Play Again" button resets the game.

---

## Technologies Used
- **HTML**: For structuring the game interface.
- **CSS**: For styling the interface.
- **JavaScript**: For game logic and interactivity.

---
