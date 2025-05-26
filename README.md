# Virtual-Thermin
Thermin is a virtual recreation of the classic **theremin**, one of the earliest electronic musical instruments that is played without physical contact. This project uses a webcam and real-time hand tracking to allow users to control **pitch** and **volume** using their **left and right hands**, respectively.

---

## Features

- Real-time audio synthesis using sine waves
- Hand tracking powered by computer vision
- Pitch control via left hand horizontal movement
- Volume control via right hand vertical movement
- Visual feedback with pitch and volume indicators
- Reverb and smoothing for enhanced audio output

---

## Tech Stack

- Python 3
- MediaPipe
- OpenCV
- SoundDevice
- NumPy
- SciPy

---

## How It Works

- A webcam captures the video stream.
- Hand landmarks are detected using MediaPipe.
- The X-coordinate of the **left index finger** controls the pitch.
- The Y-coordinate of the **right index finger** controls the volume.
- Audio is generated in real time and modified based on hand movements.
- The screen displays visual cues for both pitch and volume.
