# ✋ Gesture-Controlled Smart Mouse using Computer Vision

A real-time gesture-controlled smart mouse that enables users to control their computer using hand gestures via webcam.  
The system replaces traditional mouse interactions with intuitive gestures, allowing touchless control of cursor movement, clicks, scrolling, and screenshots.

---

## 🚀 Demo

🎥: https://drive.google.com/file/d/1Um7K3cXiwiqr5LjSTWYF4HOSbFtVg_0d/view?usp=sharing

---

## 💡 Features

- 🖐️ Real-time hand tracking using webcam  
- 🖱️ Cursor movement using index finger  
- 👌 Pinch gesture for single and double click  
- 🔄 Scroll control using hand gestures  
- 📸 Screenshot capture using closed fist  
- ⚡ Smooth and responsive interaction  

---

## 🧠 Tech Stack

- **Python**
- **OpenCV**
- **MediaPipe**
- **PyAutoGUI**
- **NumPy**

---

## ⚙️ How It Works

1. Webcam captures live video feed  
2. MediaPipe detects hand landmarks (21 key points)  
3. Gestures are recognized based on:
   - Finger positions  
   - Distance between thumb and index finger  
4. Detected gestures are mapped to system actions:
   - Move cursor  
   - Click / Double Click  
   - Scroll  
   - Take screenshot  

---

## 📂 Project Structure
main.py # Main application (gesture detection + control logic)
utils.py # Helper functions (angle, distance calculations)
