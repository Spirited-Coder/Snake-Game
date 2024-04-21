# Snake Game in C++

This project is a simple implementation of the classic Snake game in C++. It features a console-based interface and allows players to control a snake to collect fruit, growing in size with each fruit collected. The game has three difficulty levels: Easy, Medium, and Hard.

## Table of Contents

- [Gameplay](#gameplay)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Gameplay

- Control the snake using the following keys:
  - `w`: Move up
  - `a`: Move left
  - `s`: Move down
  - `d`: Move right
  - `x`: Exit the game
- The snake grows in length each time it collects a fruit (`#`).
- The game ends if the snake hits the wall or itself.
- Your score is calculated based on the number of fruits collected.
- Choose between three difficulty levels to set the speed of the game:
  - Easy
  - Medium
  - Hard

## Installation

1. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
2. Open the project folder and ensure you have a C++ compiler installed. If you don't have one, install GCC or similar.
3. Compile the source code:
   ```bash
    g++ -o snake_game snake_game.cpp

## Usage

After compiling, run the executable:
```bash
  ./snake_game
Follow the on-screen instructions to enter your name and select a difficulty level. Use the control keys to navigate the snake and avoid hitting the walls or your own tail.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this project in accordance with the terms of the license.
