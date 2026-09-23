# 🦴 Bone Fracture Detection

An AI-powered computer vision web application designed to detect and localize bone fractures from medical X-ray imagery using deep learning.

---

## 📌 Features

- **Automated Detection:** Upload an X-ray scan to automatically detect potential bone fractures.
- **Visual Bounding Boxes:** Highlights fracture locations directly on the uploaded image.
- **Interactive Web UI:** Clean, intuitive browser-based interface built with Flask, HTML, and CSS.
- **Real-time Inference:** Rapid model execution for fast turnarounds.

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **Computer Vision / Deep Learning:** OpenCV, PyTorch / YOLO
- **Frontend:** HTML5, CSS3, JavaScript

---

## 📂 Project Structure

```text
Bone-Fracture-Detection/
├── bone/
│   ├── app.py                # Main Flask web server
│   ├── detector.py           # Model inference & image preprocessing logic
│   ├── requirements.txt      # Project dependencies
│   ├── static/               # CSS styles, JavaScript, and asset files
│   └── templates/            # HTML frontend templates
└── README.md
