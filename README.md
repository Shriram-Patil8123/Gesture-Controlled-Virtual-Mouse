# 🖐️ Gesture-Controlled Virtual Mouse

Control your computer or laptop using **hand gestures** detected through your **webcam**!  
This Python project turns your hand into a virtual mouse using **MediaPipe**, **OpenCV**, and **PyAutoGUI** — with features like cursor movement, clicks, volume and brightness control, and scrolling.

---

## 🚀 Features

- 👆 **Cursor Control** using index finger  
- ✌️ **Mouse Click** with index and middle fingers  
- 🔊 **Volume Control** via distance between thumb and index finger  
- 💡 **Brightness Control** using thumb and pinky gestures  
- 📜 **Scrolling** using hand gestures  
- 🎯 Real-time performance with **hand landmark detection** (MediaPipe)

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV** – for computer vision
- **MediaPipe** – for hand landmark detection
- **PyAutoGUI** – for controlling mouse and screen actions
- **pycaw** – for volume control
- **screen-brightness-control** – for adjusting screen brightness



🚀 Getting Started
# 1. Clone the repository
git clone https://github.com/your-username/gesture-virtual-mouse.git
cd gesture-virtual-mouse

# 2. Install required libraries
pip install -r requirements.txt

# 3. Run the Python script
python "Gesture Mouse.py"


## ✨ How It Works

- 🖐️ Uses **MediaPipe** to detect hand landmarks  
- 🎯 Maps **finger positions** to screen coordinates  
- 📏 Measures **finger distances** to trigger actions like:
  - Mouse click  
  - Volume control  
  - Brightness adjustment  
  - Scrolling  

---

## ⚠️ Requirements

- 📸 A functional **webcam**  
- 🪟 **Windows OS** (for volume & brightness control compatibility)  
- 🐍 **Python 3.7+**

---

## 🙌 Credits

This project uses the following open-source tools and libraries:

- [MediaPipe](https://google.github.io/mediapipe/)  
- [OpenCV](https://opencv.org/)  
- [PyAutoGUI](https://pyautogui.readthedocs.io/)  
- [pycaw](https://github.com/AndreMiras/pycaw)  
- [screen-brightness-control](https://pypi.org/project/screen-brightness-control/)

