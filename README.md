# Hand Gesture Detection using OpenCV and MediaPipe

This project uses a webcam feed to detect hand gestures in real-time using OpenCV and MediaPipe. It can identify simple gestures like an open palm or a closed fist based on finger positions.

---

## ✅ Features

- Real-time hand tracking using webcam  
- Detects hand landmarks with MediaPipe  
- Classifies basic gestures (Open Hand, Fist)  
- Overlays gesture name on the video feed  

---

## 📦 Requirements

- Python 3.7 or above  
- OpenCV  
- MediaPipe  
- NumPy  

Install dependencies using:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install opencv-python mediapipe numpy
```

---

## 🚀 How to Run

1. Clone or download the project.
2. Ensure your webcam is connected.
3. Run the script:

```bash
python hand_gesture_detection.py
```

4. A window will open showing the webcam feed with detected hand gestures labeled on-screen.
5. Press **`q`** to quit the program.

---

## 🧠 How It Works

- MediaPipe provides 21 hand landmarks per hand.
- We calculate angles or distances between landmarks to determine which fingers are open or closed.
- Based on the finger states, we classify the gesture as:
  - ✋ **Open Hand**
  - ✊ **Fist**
  - (You can extend this to more gestures later.)

---

## 📁 File Structure

```
hand-gesture-detection/
├── hand_gesture_detection.py
├── requirements.txt
└── README.md
```

---

## 🔮 Future Improvements

- Add more gesture classes (e.g., thumbs up, peace ✌️)
- Trigger actions based on gestures (e.g., volume control, slides)
- Add multi-hand support and gesture recognition with labels

---

## 📜 License

This project is open-source and free to use for educational purposes.
