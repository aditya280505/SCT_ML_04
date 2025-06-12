# 🤚 Hand Gesture Recognition with Webcam

This project uses a deep learning model to recognize hand gestures in real-time using your webcam. It supports 10 gesture classes and can be extended to trigger system actions like opening apps or automating tasks.

---

## 📁 Project Structure


---

## ✅ Features

- Real-time hand gesture recognition
- 10 customizable gesture classes
- Optional system automation (e.g., open Chrome)
- Webcam-based ROI detection
- FPS limiter for smooth performance

---

## 📦 Installation

1. **Clone the repository** (or download the ZIP):

git clone https://github.com/your-username/hand-gesture-recognition.git
cd hand-gesture-recognition



RUN THE APP
python gesture_recognition.py
Press Q to quit the webcam.

🧠 Model Info
The model (gesture_model.keras) should be trained to accept 64x64 RGB input and output one of 10 gesture classes. You can replace the model with your own trained one.

🛠️ Optional Enhancements
✨ Add system actions (e.g., open apps when a gesture is detected)

🎨 Build a GUI using Tkinter or PyQt

📦 Package the app into .exe using PyInstaller


📌 Example Gesture Labels
python
Copy
Edit
label_map = {
    0: "Palm",
    1: "Fist",
    2: "Thumbs Up",
    3: "OK",
    4: "Peace",
    5: "Call Me",
    6: "Stop",
    7: "Rock",
    8: "Point",
    9: "None"
}


🙌 Credits
Made with ❤️ by Aditya Borgaonkar
Special thanks to OpenCV, TensorFlow, and the ML community!

📄 License
This project is open-source for educational use.










