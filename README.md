# Dice Roller

## Overview
The Dice Roller is a simple Python application that simulates rolling a six-sided dice. It uses Tkinter for the GUI and Pillow (PIL) for handling images.

## Features
- Displays a dice face corresponding to a random roll (1-6)
- Click a button to roll the dice
- Uses images for realistic dice faces

## Requirements
Make sure you have the following dependencies installed:

- Python 3.x
- Tkinter (comes pre-installed with Python)
- Pillow (PIL) for image processing

Install Pillow using:
```sh
pip install pillow
```

## Usage
1. Place six images named `dice1.png` to `dice6.png` in the same directory as the script.
2. Run the Python script:
```sh
python dice_roller.py
```
3. Click the "Roll" button to roll the dice.

## Code Explanation
- Loads six dice face images using Pillow and resizes them.
- Displays the first dice face initially.
- Clicking the "Roll" button randomly selects and displays a new dice face.

## Notes
- Ensure the image files exist in the script directory.
- Works on Windows, Mac, and Linux.

## License
This project is open-source. Feel free to modify and share!

