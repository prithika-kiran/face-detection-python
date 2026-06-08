# Face Detection using Python & OpenCV

This project implements a real-time face detection system using Python, OpenCV, and a laptop webcam. The application uses OpenCV's Haar Cascade Classifier to detect human faces in live video frames and highlights them with bounding boxes.

## Features

- Real-time face detection using webcam feed
- Haar Cascade Classifier (`haarcascade_frontalface_default.xml`)
- Bounding boxes around detected faces
- Live face count displayed in the console
- Grayscale image processing for improved detection performance
- Press **Esc** to exit the application

## Technologies Used

- Python
- OpenCV (cv2)
- Haar Cascade Classifier

## How It Works

1. The webcam captures live video frames.
2. Each frame is converted to grayscale.
3. The Haar Cascade face detection algorithm scans the frame for faces.
4. Detected faces are highlighted using red bounding boxes.
5. The number of faces detected is printed in the console in real time.
6. The application continues running until the **Esc** key is pressed.

## Project Structure

face-detection-python/

├── face_detection.py

├── haarcascade_frontalface_default.xml

└── README.md

## Run the Project

Install OpenCV:

pip install opencv-python

Run the program:

python face_detection.py

## Sample Output

- Detects faces from the webcam feed in real time.
- Draws red rectangles around detected faces.
- Prints the number of detected faces in the terminal.
