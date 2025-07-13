# 👋 Gesture-Controlled Cursor System 🎯🖐️

A computer cursor system controlled completely by hand gestures — no need for a physical mouse!  

This project uses your webcam and AI models to track hand gestures in real time and translate them into system actions like cursor movement, click, scroll, and even screenshots.

---

## 🌟 Features

- 🖱️ *Move the cursor* by pointing your **index finger**
- 🖱️ *Click* by tapping **index and thumb** together twice
- 📜 *Scroll up/down* with simple finger gestures
- 📸 *Take a screenshot* by folding all **five fingers**
- 💡 *Hands-free navigation* with ease and comfort

---

## 🛠️ Tech Stack

- `OpenCV` – Real-time video capture and frame processing  
- `MediaPipe` – Hand detection and landmark extraction  
- `PyAutoGUI` – Simulate mouse actions (move, click, scroll, etc.)  
- `Python` – Backend logic and gesture control

---

## 📽️ Demo Video

▶️ [Watch the demo on LinkedIn](https://www.linkedin.com/posts/isha-garg-768946258_python-opencv-mediapipe-activity-7350167970968457216-v5Qn?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD9_3MABTi9Kbxvc1KQLYZuyyzme19Y3ASQ)

---

## 🖼️ Screenshots

| Gesture | Action |
|--------|--------|
| ![Move Cursor](images/move_cursor.png) | Move cursor with index finger |
| ![Click](images/click.png) | Click with thumb + index tap |
| ![Scroll up](images/scroll_up.png) | Scroll up gesture |
| ![Scroll down](images/scroll_down.png) | Scroll down gesture |


> *(Make sure to put your images inside an `/images` folder in your repo)*

---

## 🚀 Get Started

```bash
git clone https://github.com/Isha882004/mouse_by_gesture
cd mouse_by_gesture
pip install -r requirements.txt
python main.py
