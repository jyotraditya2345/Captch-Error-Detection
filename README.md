# Cheating Detection System

## Overview

The Cheating Detection System is a Python-based application that utilizes facial landmark detection to identify potential cheating behavior by monitoring eye movements. If cheating is detected, the system plays a sound alert and requires the user to solve a captcha for additional verification.

## Features

- **Facial Landmark Detection:** Utilizes Dlib to detect facial landmarks, focusing on eye movements for cheating detection.
- **Audio Alert:** Plays a sound alert when cheating behavior is detected.
- **Voice Recognition:** Uses SpeechRecognition to recognize voice input for additional confirmation through captcha.

## Prerequisites

Ensure you have the following dependencies installed:

- [OpenCV](https://pypi.org/project/opencv-python/)
- [Dlib](https://pypi.org/project/dlib/)
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
- [Pydub](https://pypi.org/project/pydub/)

Install dependencies using:

```bash
pip install opencv-python dlib SpeechRecognition pydub
