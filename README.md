# Aim Trainer

## Overview

**Aim Trainer** is a simple web-based game designed to help users improve their aim and precision through progressively challenging levels. The game consists of two levels, each with a different target size and pace, aimed at enhancing the player's self-management skills.

## Features

- **Level 1:** 30 targets with a larger size (60px) to ease the player into the game.
- **Level 2:** 30 targets with a smaller size (30px) for an increased challenge.
- **Dynamic Timing:** The game tracks how long it takes for the player to complete each level, providing feedback upon completion.
- **Progression:** The game guides players from Level 1 to Level 2, offering motivational messages to encourage continuous improvement.

## How to Play

1. **Start the Game:** Click the "Start" button to begin the first level. Targets will appear on the screen at random positions.
2. **Click the Targets:** Click on the targets as quickly as possible. The level ends when all 30 targets have been clicked.
3. **Level Progression:** After completing Level 1, you'll be given your time and a motivational message. You can then proceed to Level 2 by clicking the "Next Level" button.
4. **Complete Level 2:** Click all 30 targets in Level 2 to finish the game. Upon completion, you'll receive your total time and a final message, which leads to the next training skill after a short delay.

## File Structure

- **index.html:** The main HTML file that contains the structure and logic for the Aim Trainer game.
- **style.css:** Inline CSS is used in the HTML file to style the game elements.
- **red-black-bulls-eye-removebg-preview.png:** The image used as the target in the game. Ensure this image is in the same directory as the HTML file.

## Usage

To run the Aim Trainer game, simply open the `index.html` file in a web browser.

## Customization

- **Target Image:** Replace the `red-black-bulls-eye-removebg-preview.png` file with your own image to change the appearance of the targets.
- **Target Size and Speed:** Adjust the target sizes and the time interval between target appearances by modifying the `currentLevel` conditions in the `createTarget` function.

## Future Enhancements

- Add more levels with varying difficulties.
- Implement a scoring system based on accuracy and speed.
- Provide more detailed feedback and tips for improvement.
- Create a leaderboard to track and compare scores among users.

