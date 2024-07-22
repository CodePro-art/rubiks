# Rubik's Cube Game

This is a 3D Rubik's Cube game developed using JavaScript and Three.js. It provides an interactive simulation of the classic Rubik's Cube puzzle.

## Table of Contents

1. [Installation](#installation)
2. [How to Play](#how-to-play)
3. [Tutorial](#tutorial)
4. [Code Summary](#code-summary)
5. [License](#license)

## Installation

1. Clone the repository:

   ```bash
   git clone git@github.com:CodePro-art/rubiks.git
   ```

2. Navigate to the project directory:

   ```bash
   cd rubiks
   ```

3. Install the necessary dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

## How to Play

1. Use the mouse to rotate the cube. Click and drag to change the view.
2. Click on a face of the cube to select it.
3. Use the buttons on the screen to rotate the selected face clockwise or counterclockwise.
4. Solve the cube by getting all faces to have a uniform color.

## Tutorial

1. Rotating the Cube:

    * Click and hold the left mouse button.
    * Drag the mouse to rotate the cube in different directions.

2. Selecting a Face:
    * Hover over the cube to highlight a face.
    * Click on the face to select it. The selected face will be marked.

3. Rotating a Face:
    * Use the on-screen buttons to rotate the selected face:
        * Clockwise
        * Counterclockwise

4. Resetting the Cube:
    * Use the reset button to reset the cube to its initial state.

## Code Summary

* **index.html**: The main HTML file that sets up the structure of the webpage.
* **styles.css**: The CSS file that provides the styles for the game.
* **script.js**: The main JavaScript file that initializes the Three.js scene and handles user interactions.
  * Contains the logic for creating and manipulating the Rubik's Cube.
  * src/controls.js: Manages the controls for rotating the cube and its faces.

## License

This project is licensed under the MIT License. See the LICENSE.txt file for more details.
