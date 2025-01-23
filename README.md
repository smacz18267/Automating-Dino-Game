# Dino Game Automation with Computer Vision

Welcome to the Dino Game Automation project! This repository contains a Python script that automates the popular Chrome Dino Game using computer vision techniques. The project is designed to showcase the integration of OpenCV and PyAutoGUI for real-time object detection and keyboard event simulation.

## Features

- **Real-time Gameplay Automation**: Automatically plays the Dino Game by detecting obstacles and simulating key presses.
- **Computer Vision Integration**: Utilizes OpenCV to process the game screen and identify objects.
- **Keyboard Control**: Uses PyAutoGUI to interact with the game by triggering jump actions.
- **Customizable Parameters**: Adjust detection thresholds and gameplay settings to optimize performance.

## Requirements

To run this project, you need to have the following installed:

- Python 3.8+
- OpenCV
- PyAutoGUI
- NumPy
- Pillow
- mss 

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Ekanshthegreat/DinoGameAutomation.git
   cd DinoGameAutomation
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have a Chrome browser running the Dino Game (you can access it offline or via `chrome://dino/`).

## Usage

1. Open the Chrome Dino Game in your browser.
2. Run the script:

   ```bash
   python dino_game_automation.py
   ```

3. Focus on the game window, and the script will take over the gameplay.

## How It Works

1. **Screen Capture**: Captures a region of the screen where the Dino Game is displayed.
2. **Obstacle Detection**: Processes the screen capture using OpenCV to identify incoming obstacles.
3. **Decision Making**: Determines whether to jump based on the proximity of obstacles.
4. **Action Execution**: Simulates key presses using PyAutoGUI to control the Dino.

## Project Structure

```
DinoGameAutomation/
├── main.py   # Main script for automation
├── requirements.txt          # List of dependencies
├── README.md                 # Project documentation
```
## Future Enhancements

- Add support for night mode in the Dino Game.
- Improve obstacle detection using deep learning models.
- Incorporate adaptive gameplay based on speed increments.

## Acknowledgments

- The Chrome Dino Game team for the fun and addictive game.
- OpenCV and PyAutoGUI communities for their amazing libraries.

Happy coding! 🦖
