# YOLOv8 Object Detection Web App 🚀

This project is a **YOLOv8-based Object Detection Web Application** built using **Gradio**. It allows users to perform object detection on both **images and videos** using different YOLOv8 model variants through an interactive web interface.

---

## 🔍 Features

* 📸 **Image Object Detection**
* 🎥 **Video Object Detection (frame-by-frame)**
* 🤖 Supports multiple YOLOv8 models:

  * `yolov8n`, `yolov8s`, `yolov8m`, `yolov8l`, `yolov8x`
* 🎚️ Adjustable **image size** and **confidence threshold**
* 🔄 Dynamic UI toggle between image and video inputs
* 🖼️ Annotated output displayed directly in the browser

---

## 🛠️ Tech Stack

* **Python**
* **YOLOv8 (Ultralytics)**
* **Gradio**
* **OpenCV**
* **Tempfile**

---

## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/yolov8-object-detection-gradio.git
cd yolov8-object-detection-gradio
```

2. **Create a virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

3. **Install required dependencies**

```bash
pip install gradio opencv-python ultralytics
```

---

## ▶️ How to Run

```bash
python app.py
```

After running the command, a **local Gradio URL** will appear in the terminal. Open it in your browser to use the application.

---

## 🧪 How It Works

* The user selects **Image** or **Video** as input.
* A YOLOv8 model is loaded dynamically based on selection.
* For images:

  * Object detection is performed once.
  * Annotated image is displayed.
* For videos:

  * Each frame is processed individually.
  * The annotated frames are written to a new output video.
* Results are visualized directly in the web UI.

---

## 📌 Notes

* Larger models (`yolov8l`, `yolov8x`) provide better accuracy but require more computation.
* Video processing may take longer depending on video length and model size.
* Ensure sufficient system memory when working with large videos.

---

## 🎯 Use Cases

* Computer Vision learning and experimentation
* Real-time object detection demos
* Academic mini-projects
* YOLOv8 model comparison

---

