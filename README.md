# 👀 Human Detection using YOLOv8 & OpenCV

This project uses **YOLOv8** (You Only Look Once, Version 8) and **OpenCV** to perform **real-time human detection** from your laptop’s webcam or any connected camera.  
It’s lightweight, fast, and easy to set up on Windows.

---

## 📌 Features
- **Real-time Detection** – Detects humans instantly using your webcam.
- **YOLOv8 Model** – High accuracy with the `yolov8n.pt` model.
- **Lightweight Code** – Just Python, OpenCV, and Ultralytics.
- **Customizable** – Replace the YOLO model with your own for different object detection tasks.

---

## 📂 Project Structure
📁 Human-Detection-Project
├── main.py # Main Python script
├── yolov8n.pt # YOLOv8 nano model (pre-trained)
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---

## ⚙️ Installation & Setup

1️⃣ **Clone the repository**
```bash
git clone https://github.com/<your-username>/Human-Detection-Project.git
cd Human-Detection-Project
```
2️⃣ Create a virtual environment (recommended)
```
python -m venv venv
venv\Scripts\activate   # On Windows
```
3️⃣ Install dependencies
```
pip install -r requirements.txt
```
4️⃣ Download YOLOv8 model (if not already in the folder)


# From Ultralytics GitHub or using:
```
pip install ultralytics
yolo download model=yolov8n.pt
```
▶️ How to Run
Run the script:
```
python main.py
```
The webcam feed will open.

Humans will be detected and marked with bounding boxes.

Press q to quit.

🧠 How It Works
YOLOv8 detects objects in each video frame.

The detection is filtered to only show persons.

Bounding boxes and labels are drawn using OpenCV.

📦 requirements.txt

ultralytics
opencv-python

🔧 Customization
```
Change Model → Replace yolov8n.pt with yolov8s.pt or your custom-trained model.

Change Source → Modify cv2.VideoCapture(0) to use a video file or IP camera.
```
📜 License
This project is open-source under the MIT License.
Feel free to modify and use it in your own projects.

🙌 Acknowledgments
Ultralytics YOLOv8

OpenCV

---

If you want, I can also give you a **second section** in the README explaining **how to build it into a `.exe` with PyInstaller** so people can run it without Python.  
Do you want me to include that?







