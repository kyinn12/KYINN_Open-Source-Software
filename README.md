# MySudoku - Sudoku with Your Own Characters

## Motivation

I enjoy playing Sudoku and play it every day.
However, using numbers all the time can get boring, so I want to use my favorite characters instead.
Choosing my own images could make the game more fun and personal.
I also want to try larger boards for a different challenge.

## Goal

Build an open-source Sudoku game where players can choose their own character images.
The game will follow normal Sudoku rules, with different board sizes.

## Features

### Core Game

- Each row, column, and box must contain each character exactly once.
- Start with 4×4 and 9×9 boards.
- Allow players to switch between character and number views.
- Add candidate notes, undo, and rule checking.
- Save game progress so players can continue later.

### Character Customization

- Provide a default character set.
- Let players import PNG or JPG images from their computer.
- Resize the images to fit the cells and save the character settings.

### Puzzle System

- Make a solver to check puzzles and give simple hints.
- Check that each puzzle has only one solution.
- Try to add 16×16 boards after finishing the core game.
- If time remains, add an experimental 32×32 mode with 4×8 boxes.
