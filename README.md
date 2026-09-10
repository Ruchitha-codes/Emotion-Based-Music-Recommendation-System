# Emotion-Based Music Recommendation System

## About the Project

The Emotion-Based Music Recommendation System is a Python application with a Tkinter graphical user interface. It allows the user to upload an image containing a face, detects the face using OpenCV, predicts the person's emotion using a pre-trained Keras emotion classification model, and recommends songs based on the detected emotion.

## Features

* Upload an image containing a face
* Detect faces using OpenCV
* Predict emotions from facial expressions
* Recommend songs based on the detected emotion
* Select a recommended song from a dropdown list
* Play the selected song

## Technologies Used

* Python
* Tkinter
* OpenCV
* Keras
* NumPy
* playsound

## Emotions Detected

The system can identify:

* Angry
* Disgust
* Scared
* Happy
* Sad
* Surprised
* Neutral

## How It Works

1. The user uploads an image through the Tkinter interface.
2. OpenCV detects faces in the image.
3. The detected face is processed and resized to the required input size.
4. The trained emotion classification model predicts the emotion.
5. The system searches the `songs` folder for songs matching the detected emotion.
6. The user selects a song from the list and can play it.

## Project Structure

```text
Emotion-Based-Music-Recommendation-System/
│
├── Emotion.py
├── haarcascade_frontalface_default.xml
├── _mini_XCEPTION.106-0.65.hdf5
└── songs/
```

## How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Make sure the Haar Cascade file and emotion model file are available in the project directory.
4. Keep the songs inside the `songs` folder.
5. Run:

```bash
python Emotion.py
```

## Project Purpose

This project was developed to practice Python GUI development, image processing, facial emotion detection, and basic recommendation logic.
