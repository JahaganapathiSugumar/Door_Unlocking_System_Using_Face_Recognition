# Door Unlocking System Using Face Recognition

## Overview
This project implements a door unlocking system that uses facial recognition technology for user authentication. The system captures the face of the person in front of the door, matches it against a pre-registered database, and unlocks the door if a match is found. This project combines facial recognition, security, and IoT to create a contactless and secure method for door access.

## Key Features
- Uses OpenCV for real-time face detection and recognition.
- Allows users to register their face data into the system.
- Unlocks the door upon successful face recognition.
- Provides a secure and contactless method of authentication.
- Can be integrated with an IoT-based door lock system for real-time access control.

## Technologies Used
- **Face Recognition**: OpenCV, Dlib
- **Backend**: Python
- **Database**: SQLite (for storing registered users' face data)
- **IoT Integration**: Optional (to control a physical door lock)

## How to Use
1. Clone this repository.
2. Install the required dependencies, such as OpenCV, Dlib, and SQLite.
3. Train the system by registering users' faces. Capture a series of face images and store them in the database.
4. Run the face recognition script to detect and recognize faces in real-time.
5. Upon successful recognition, the system will trigger an action to unlock the door (can be integrated with a physical IoT lock).

## Installation

1. Install Python and necessary libraries:
   ```bash
   pip install opencv-python dlib numpy sqlite3
   ```

2. Clone the repository:
   ```bash
   https://github.com/JahaganapathiSugumar/Door_Unlocking_System_Using_Face_Recognition.git
   ```

3. Set up the database by running the registration script to capture face images and store them in the database.

4. Run the face recognition script to test the system.

## Outputs
- Real-time face detection and recognition results.
- A successful match will trigger a door unlocking mechanism (can be simulated or integrated with an IoT device).
- Logs of recognized faces and matched users.

## Future Enhancements
- Integration with smart locks for physical door unlocking.
- Use of advanced deep learning models for higher accuracy.
- Mobile app integration for remote monitoring and control.
