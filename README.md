# Accessible Vision - A YOLO-based Object Recognition Web App

Welcome to **Accessible Vision**, a project developed during the MakeUC Hackathon in Cincinnati, OH, in November 2023. This web app is designed to assist visually impaired users in recognizing objects and reading text aloud, making the world more accessible and inclusive.

## Overview

- **Hackathon:** MakeUC Hackathon, Cincinnati, OH
- **Duration:** November 2023
- **Objective:** Utilized a pre-trained machine learning model, YOLO (You Only Look Once), to build a website capable of recognizing objects and reading text aloud for blind users.
- **Technology Stack:** Python, Flask, HTML, Java, YOLO, Azure

## Features

- **Real-time Object Recognition:** The project integrates the YOLO machine learning model to recognize objects in real-time, enhancing accessibility for visually impaired users.
- **Text-to-Speech Integration:** Text detected in the images is read aloud using audio feedback, providing an inclusive experience for users.
- **Seamless Accessibility:** The solution is hosted on Azure for seamless accessibility and reliability.

## Project Structure

### Front-end (HTML, Java, Flask)

#### Homepage (not currently online)

The homepage provides an overview of the Accessible Vision project and invites users to tap anywhere to begin.

#### Subpage

The subpage captures video from the user's device and allows them to capture and upload images for object recognition.

[Code](#) - Insert link to the HTML/Java code

### Back-end (Python, YOLO, OpenCV)

The back-end processes the captured images, runs YOLOv8 inference, and provides real-time annotations on the video feed.

[Code](#) - Insert link to the Python code

## Usage

1. Visit the Accessible Vision homepage.
2. Tap anywhere to start the object recognition process.
3. Use the "Capture and Upload" button on the subpage to upload images for real-time processing.

## Setup

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Flask application using `python app.py`.

## Acknowledgments

This project was developed during the MakeUC Hackathon. Special thanks to the organizers and sponsors for providing the platform to innovate and create inclusive solutions.

Feel free to explore the code and contribute to the project. We believe in making technology accessible to everyone! 🌐🔍🔊
