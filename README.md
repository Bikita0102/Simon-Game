# Simon Game

A simple Simon memory game built using HTML, CSS, and JavaScript. The game challenges your memory as you repeat an increasingly long sequence of lights and sounds. 

## Overview

In this game, you need to follow the sequence of flashing colored quadrants. Each quadrant plays a unique tone when activated. The game features:
- **Power Toggle**: Turn the game on or off.
- **Strict Mode**: When enabled, a single mistake restarts the game.
- **Start Button**: Begin a new game.
- **Win Condition**: Successfully repeat 20 steps to win the game!

## Files

- **simon.html**  
  Contains the structure of the game. It includes:
  - Links to the external CSS (`styles/simon.css`) for styling.
  - Audio elements for each sound effect.
  - A reference to the JavaScript file (`scripts/simon.js`) that contains the game logic.

- **simon.css**  
  Styles the game board including:
  - Layout of the four colored quadrants.
  - Design of the inner circle, buttons, and text.
  - Visual effects like box shadows and font styling.

- **simon.js**  
  Contains the logic for the Simon game:
  - Generates a random sequence of steps.
  - Manages user interactions and sequence validation.
  - Controls game states such as user turn, strict mode, and winning the game.
  - Handles audio playback and visual feedback.

## How to Play

1. **Power On**: Toggle the power switch to turn the game on.
2. **Strict Mode (Optional)**: Toggle the strict mode checkbox if you want the game to restart immediately upon a mistake.
3. **Start the Game**: Click the "Start" button to begin a new game.
4. **Follow the Sequence**: Watch the sequence of flashes and listen to the sounds, then repeat the sequence by clicking the colored quadrants.
5. **Win the Game**: Repeat the entire sequence correctly for 20 rounds to win!

## Getting Started

1. **Download or Clone the Repository**:

   ```bash
   git clone https://github.com/Bikita0102/Simon-Game.git
   cd Simon-Game

2. **Run the Game**:
   - Open the `simon.html` file in your web browser.
   - Alternatively, run a local web server (for example, using the Live Server extension in VS Code) to open the game.

## Customization

- **Audio**: The audio sources are linked from external URLs. You can replace these with local files or other online resources.
- **Styles**: Modify `simon.css` to change colors, layout, and other design aspects.
- **Game Logic**: Update `simon.js` to tweak game difficulty, change the sequence length, or add new features.

## Credits

This Simon Game is inspired by the classic memory game "Simon". Audio files are courtesy of freeCodeCamp's resources.

## License

This project is open source and available under the [MIT License](LICENSE).

Enjoy playing and feel free to contribute to improve the Simon Game!