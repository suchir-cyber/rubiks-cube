# Rubik's Cube Solver


## Overview

This project is a Rubik's Cube solver that takes input from a camera, detects the colors of the cube's stickers, and provides a solution using the Kociemba algorithm. The application uses OpenCV for image processing and NumPy for numerical operations.


## Key Features

- Real-time color detection of Rubik's Cube stickers.

- Visualization of the cube's state in 2D and 3D.

- Step-by-step solution display.

- User-friendly interface for input and output.


## Technologies Used

- Python 3.x

- OpenCV

- NumPy

- Kociemba

## Demo Images

![Screenshot 2024-12-15 233724](https://github.com/user-attachments/assets/78592a6e-2461-49e0-a834-c3fcebbf77fb)
![Screenshot 2024-12-15 233750](https://github.com/user-attachments/assets/60623ce3-3095-4c50-8330-5fc511f22f0e)

## Demo Video

https://github.com/user-attachments/assets/5786f3c6-e719-45cb-882e-e0b948979a20

## Installation

1. Clone the repository:

   ```bash

   git clone https://github.com/suchir_18/rubiks-cube-solver.git

   cd rubiks-cube-solver

   ```

2.Install the required packages:

```bash

pip install opencv-python numpy kociemba

```

## Usage

  1. Connect your webcam.

  2. Run the application:

  ```bash

    python cube.py

  ```

  3. Follow the on-screen instructions to scan each face of the Rubik's Cube:
      - Press u for the upper face.
      - Press d for the down face.
      - Press l for the left face.
      - Press r for the right face.
      - Press f for the front face.
      - Press b for the back face.

   4. Once all six faces are scanned, press Enter or a number key (1-9) to get the solution.

   5. The solution will be displayed step-by-step, and you can visualize the moves in 3D.

## Controls

  - y: Start scanning the cube.
  - n: Exit the application.
  - Esc: Exit the current scanning mode.
  - Enter or 1-9: Get the solution based on the selected method.
