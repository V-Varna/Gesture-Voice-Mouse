# Gesture-Voice-Mouse

An AI-powered Gesture and Voice Controlled Virtual Mouse system developed using Python, OpenCV, MediaPipe, Speech Recognition, and Eel.
The project enables users to control mouse operations, system volume, brightness, scrolling, and other computer functions using real-time hand gestures and voice commands.

---

## Features

### Gesture Controls

* Cursor Movement using hand gestures
* Left Click
* Right Click
* Double Click
* Drag and Drop
* Vertical Scrolling
* Horizontal Scrolling
* Volume Control
* Brightness Control

### Voice Assistant (Proton)

* Voice-based command execution
* Open Google Search
* Open Locations in Maps
* Copy/Paste operations
* Launch/Stop Gesture Recognition
* File Navigation
* Interactive Chatbot GUI

### GUI Interface

* Desktop chatbot interface using Eel
* Real-time message display
* Voice + Text interaction

---

## Technologies Used

| Technology                | Purpose                     |
| ------------------------- | --------------------------- |
| Python                    | Backend Development         |
| OpenCV                    | Video Capture & Processing  |
| MediaPipe                 | Hand Landmark Detection     |
| PyAutoGUI                 | Mouse & Keyboard Automation |
| SpeechRecognition         | Voice Recognition           |
| pyttsx3                   | Text-to-Speech              |
| Eel                       | GUI Communication           |
| HTML/CSS/JavaScript       | Frontend Interface          |
| pycaw                     | System Volume Control       |
| screen_brightness_control | Brightness Adjustment       |

---

## Project Architecture

```text
User
 ├── Voice Input
 │      ↓
 │ Speech Recognition
 │      ↓
 │ Command Processing
 │      ↓
 │ System Automation
 │
 └── Hand Gesture
        ↓
     Webcam Input
        ↓
   MediaPipe Detection
        ↓
   Gesture Recognition
        ↓
   PyAutoGUI Actions
```

---

## Folder Structure

```text
Gesture-Voice-Mouse/
│
├── app.py
├── Proton.py
├── Gesture_Controller.py
├── requirements.txt
│
├── web/
│   ├── index.html
│   ├── main.js
│   └── jquery.convform.css
│
└── README.md
```

---

## How It Works

### Gesture Recognition

* Webcam captures hand movements.
* MediaPipe detects hand landmarks.
* Finger positions are analyzed.
* Gestures are mapped to mouse/system controls.

### Voice Assistant

* SpeechRecognition converts voice to text.
* Commands are processed dynamically.
* pyttsx3 provides voice responses.

### GUI Communication

* Eel connects Python backend with frontend UI.
* Messages are displayed in real-time chatbot interface.

---

## Installation

### Clone Repository

```bash
git clone https://github.com/V-Varna/Gesture-Voice-Mouse.git
cd Gesture-Voice-Mouse
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Project

```bash
python Proton.py
```

---

## Gesture Mapping

| Gesture               | Action                    |
| --------------------- | ------------------------- |
| V Gesture             | Cursor Movement           |
| Fist                  | Drag & Drop               |
| Middle Finger Gesture | Left Click                |
| Index Finger Gesture  | Right Click               |
| Two Fingers Closed    | Double Click              |
| Pinch (Major Hand)    | Volume/Brightness Control |
| Pinch (Minor Hand)    | Scrolling                 |

---

## Future Enhancements

* Machine Learning-based Gesture Classification
* Custom Gesture Training
* Face Recognition Authentication
* Virtual Keyboard
* Offline Speech Recognition
* Cross-platform Support
* Gesture Sensitivity Settings

---

## Key Highlights

* Real-time Computer Vision Application
* Human-Computer Interaction System
* Voice + Gesture Hybrid Control
* Multi-threaded Execution
* Interactive GUI Interface

---

## Author

Varna Vanamala

