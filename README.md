# Driver Drowsiness Detection System

## Overview
This repository contains the implementation of a Driver Drowsiness Detection System, aimed at enhancing road safety by alerting drivers when signs of drowsiness are detected. The system utilizes computer vision techniques to monitor the driver's behavior and issues warnings if drowsiness is detected.

## Features
- Real-time drowsiness detection using computer vision.
- Detection of eye closure and head movements indicating drowsiness.
- Auditory and visual alerts to prompt the driver to take necessary actions.
- Easy-to-use interface for configuration and monitoring.

## Requirements
- Python 3.x
- OpenCV
- dlib
- imutils
- Playsound (for audio alerts)

## Installation
1. Clone this repository:
   ```
   git clone https://github.com/td-02/Driver-drowisness-detection-system.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Run the main script:
   ```
   Drowsiness_Detection.py
   ```
2. Adjust parameters such as thresholds and alert types as needed.
3. Ensure proper lighting conditions for accurate detection.
4. Keep the camera focused on the driver's face for optimal results.

## License
This project is licensed under the [MIT License](LICENSE).

## Disclaimer
This system is designed to assist drivers in maintaining alertness and should not be relied upon as a substitute for responsible driving practices. Always prioritize safety and avoid distractions while operating a vehicle.
