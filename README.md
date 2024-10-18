# Person Detection Using Google Coral

## Overview
This project implements real-time person detection using a TensorFlow Lite model optimized for the Google Coral USB Accelerator. The system processes live video feeds to detect people and sends alerts via the GSM 900A MINI module, ensuring effective communication of detected locations.

## Hardware
- **Camera**: Captures the live video feed.
- **Google Coral USB Accelerator**: Provides fast inference capabilities, significantly boosting detection speed.
- **Raspberry Pi 4B+**: Handles the processing of the video stream and the detection logic.
- **SIM900A MINI GSM Module**: Sends SMS alerts with the GPS coordinates of detected individuals.

## Model and Performance
- **Model Type**: TensorFlow Lite model optimized for Edge TPU.
- **Accuracy**: Achieved a maximum of **92% accuracy** in person detection.
- **Frame Rate**: Capable of processing at **32 frames per second (FPS)**, ensuring real-time detection.

## Usage
1. **Real-time Detection**: The system processes the camera feed in real time, detecting persons with high accuracy and low latency thanks to the Coral USB Accelerator.
2. **Alert System**: Upon detecting a person, the system sends an SMS alert with the GPS coordinates via the GSM module, ensuring immediate communication with rescue teams or monitoring personnel.


## Steps to install required libraries and files
- Note:- Make Sure that git for windows installed
     ```bash
     git clone https://github.com/ShivaTsavatapalli5/Alert_on_person_detection.git
     cd Alert_on_person_detection
     ./requirements.sh
     ```
