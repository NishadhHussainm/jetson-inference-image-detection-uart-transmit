# jetson-inference-image-detection-uart-transmit

# Object Detection and UART Communication on NVIDIA Jetson

This Python program combines object detection and UART communication on an NVIDIA Jetson device. It uses the NVIDIA `detectnet` model for object detection and communicates the detected object's name via UART.

## Prerequisites

Before using this program, ensure you have the following:

- An NVIDIA Jetson device (Jetson Nano, Jetson Xavier, etc.).
- A camera connected to your Jetson device.
- Python 3 installed on your Jetson.
- Required Python packages, which can be installed using `pip`:
  - `serial` for UART communication
  - `cv2` (OpenCV) for video capture
  - `subprocess` for running the `detectnet` command
  - `threading` for managing concurrent execution
  - `queue` for passing data between threads

## Usage

1. Clone or download this repository to your NVIDIA Jetson device.

2. Make sure your camera is connected and operational.

3. Execute the Python script with Python 3:

   ```bash
   python3 object_detection_uart.py
