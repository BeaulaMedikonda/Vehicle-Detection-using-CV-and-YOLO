# Real-Time Traffic Vehicle Detection using YOLO

This project demonstrates a real-time traffic analysis pipeline using a pretrained YOLO model.
It focuses on detecting vehicles from traffic video footage in a CPU-friendly and explainable way.

---

## 🚀 Features
- Vehicle detection using YOLO (cars, buses, trucks, motorcycles)
- CPU-optimized processing using frame skipping
- Confidence and size-based filtering to reduce false positives
- Clean visualization inside Jupyter Notebook
- Designed for real-world CCTV / traffic camera footage

---

## 🧠 Tech Stack
- Python
- YOLO (Ultralytics)
- OpenCV
- NumPy
- Jupyter Notebook

---

## 📊 Output
The model draws bounding boxes around detected vehicles and labels them as **vehicle** for stable traffic analysis.

> Note: Vehicle subclasses are merged into a single category to reduce misclassification noise.

---

## ⚠️ Limitations
- Occasional false positives due to camera angle and road artifacts
- Vehicle counts are frame-level estimates (no tracking across frames)

---

## 🔮 Future Improvements
- Add object tracking for stable vehicle counting
- Lane-wise traffic density estimation
- Speed estimation using frame-to-frame tracking
