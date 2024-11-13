# Throw Dice Game

## Project Description

This is a simple web-based game created to help teams make decisions by rolling virtual dice. In this game, each dice represents a team member (Member A, Member B, and Member C), and the highest roll decides which team member's solution will be implemented. If two or more members roll the same highest number, a tie is indicated by a unique color.

## Features

- **Three Dice Roll Simulation**: Each dice represents a team member:
  - Dice 1 for Member A
  - Dice 2 for Member B
  - Dice 3 for Member C
- **Roll Button**: A button to roll all three dice at once, generating random numbers between 1 and 6.
- **Winner Announcement**: Displays the winning team member with the highest roll at the top.
- **Color Coding for Dice Results**:
  - **Green** for the highest roll.
  - **Yellow** for the second-highest roll.
  - **Red** for the lowest roll.
  - **Blue** for dice showing tied values.

## Files and Structure

- **index.html**: Contains the HTML structure with:

  - Three `div` elements representing each dice with IDs (`member-1`, `member-2`, `member-3`).
  - A `div` for displaying the winner (`winner`).
  - A roll button with ID `roll`.

![alt text](<Code/media/game(op).png>)

- **index.css**: Styles to:

  - Format the dice and button.
  - Apply background colors to indicate roll rankings (highest, second-highest, lowest, and tie).

![alt text](<Code/media/max(op).png>)

- **index.js**: JavaScript to:

  - Simulate the dice rolls.
  - Determine the highest, second-highest, and lowest rolls.
  - Apply color coding and display the winner or handle ties.

![alt text](<Code/media/equal(op).png>)

## Instructions

1. Open `index.html` in a browser.
2. Click the "ROLL THE DICE" button to roll all three dice.
3. Observe the results with color-coded dice and winner display.

This app provides a fair, random method for selecting a solution among team members and a fun way to make group decisions.
