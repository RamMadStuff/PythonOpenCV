# Drowsiness Detection Using OpenCV

## Overview
This project is a **real-time driver drowsiness detection system** using OpenCV and Haar cascade classifiers. It detects faces and eyes from a webcam feed and triggers an alert when signs of drowsiness (such as closed eyes) are detected for an extended period.

## Features
- **Face and Eye Detection** using OpenCV Haar cascades.
- **Drowsiness Detection** by monitoring eye closure.
- **Real-time Alerts** with on-screen text and beep sound.
- **Console Logging** of detected features.

## Installation
### Requirements
- Python 3.x
- OpenCV
- NumPy
- Windows (for `winsound` module)

### Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/RamMadStuff/PythonOpenCV.git
   ```
2. Install dependencies:
   ```sh
   pip install opencv-python numpy
   ```
3. Run the script:
   ```sh
   python drowsiness_detection.py
   ```

## Usage
- Ensure your **webcam is connected**.
- Run the script and keep your **face visible**.
- If your eyes remain closed for a prolonged period, you will see an alert on the screen and hear a beep sound.
- Press `q` to exit.



