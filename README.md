# Face Recognition Attendance System

## Overview

The Face Recognition Attendance System is a Python-based project that automates the process of attendance marking using facial recognition technology. This system captures an image of a person, recognizes the face, and marks attendance automatically. The project uses a database to store the attendance records and a graphical user interface for user interaction.

## Features

- Real-time face detection and recognition
- Automated attendance marking
- User-friendly graphical user interface (GUI)
- Database integration for storing attendance records
- Easy setup and configuration

## Requirements

- Python 3.x
- OpenCV
- NumPy
- SQLite3 (for database)
- PyQt5 (for GUI)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/face-recognition-attendance-system.git
    cd face-recognition-attendance-system
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main Python script:
    ```bash
    python Face-reco.py
    ```

2. The GUI will open. Use the interface to capture images, recognize faces, and mark attendance.

3. Attendance records will be stored in the SQLite database (`face-reco.db`).

## Files

- `Face-reco.py`: Main script to run the face recognition attendance system.
- `face-reco.db`: SQLite database file for storing attendance records.
- `Face-recogniton.ui`: User interface file for the project.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgements

- OpenCV for providing the computer vision library
- PyQt5 for the GUI components
- Contributors and maintainers of the dependencies

