# 🤚 Hand Gesture Volume Control using Python

This project uses a webcam and hand gesture detection to control the system volume — no hardware buttons needed! When you bring your **thumb and index finger** closer or farther apart, the script increases or decreases your system volume.

## 🛠️ Technologies Used

- **Python**
- **OpenCV** – For webcam access and image processing
- **MediaPipe** – For real-time hand tracking
- **PyAutoGUI** – To simulate volume key presses

---

## 🎯 Features

- Detects your **thumb and index finger tips** using MediaPipe
- Calculates the **distance between fingers** to control volume
- Uses `pyautogui.press("volumeup")` or `("volumedown")` to adjust volume
- Displays real-time hand landmarks and gesture line

---

## 🖥️ How It Works

- If the distance between thumb and index finger is **greater than 30 pixels**, volume goes **up**
- If the distance is **less than 30 pixels**, volume goes **down**

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/hand-gesture-volume-control.git
cd hand-gesture-volume-control
