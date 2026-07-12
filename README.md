# 🚗 License Plate Detection and Recognition Using YOLO26n and EasyOCR

A real-time **Automatic License Plate Recognition (ALPR)** system developed using a custom **YOLO26n** object detection model and **EasyOCR**. The system detects vehicle license plates from images, videos, and live webcam feeds, extracts the plate region, and recognizes the alphanumeric text for applications in intelligent transportation systems, smart parking, toll collection, and traffic monitoring.

---

## 🚀 Features

- Real-time license plate detection
- Automatic license plate text recognition using EasyOCR
- Supports images, videos, and live webcam streams
- Bounding box visualization with confidence scores
- OCR preprocessing for improved text recognition
- Lightweight YOLO26n model for fast inference

---

## 📊 Model Performance

The custom **YOLO26n** model was trained for **30 epochs** on a labeled license plate dataset and achieved excellent detection performance for Automatic License Plate Recognition (ALPR).

### Overall Performance

| Metric | Value |
|---------|------:|
| **Precision** | **95.4%** |
| **Recall** | **91.5%** |
| **mAP@50** | **94.6%** |
| **mAP@50-95** | **71.6%** |

---

## ⚙️ Training Details

| Parameter | Value |
|-----------|-------|
| **Model** | YOLO26n |
| **Epochs** | 30 |
| **Framework** | Ultralytics YOLO |
| **Validation Images** | 67 |
| **Validation Instances** | 71 |
| **Classes** | License Plate |
| **Model Size** | 5.4 MB |
| **Parameters** | 2,375,031 |
| **GFLOPs** | 5.2 |
| **Training Time** | 0.166 Hours (~10 Minutes) |
| **GPU** | NVIDIA Tesla T4 |

---

## 🛠️ Technologies Used

- Python
- YOLO26n (Ultralytics)
- EasyOCR
- OpenCV
- NumPy
- Google Colab

---

## 📈 Output

The system provides:

- Vehicle license plate detection
- Plate bounding box
- Confidence score
- Recognized license number using EasyOCR

Example:

```
License Plate   98%
Plate Number: LEA-1234
```

---

## 📌 Key Highlights

- ✅ Achieved **94.6% mAP@50** for accurate license plate detection.
- ✅ Reached **95.4% precision** with **91.5% recall**, ensuring reliable plate localization.
- ✅ Lightweight **5.4 MB YOLO26n** model suitable for real-time deployment.
- ✅ Fast inference speed of **3.8 ms per image**, enabling high-performance Automatic License Plate Recognition (ALPR).
- ✅ Integrated with **EasyOCR** for end-to-end license plate detection and text recognition from images, videos, and live camera streams.


## 💡 Applications

- Automatic License Plate Recognition (ALPR)
- Smart Parking Systems
- Toll Collection
- Traffic Monitoring
- Intelligent Transportation Systems
- Vehicle Access Control
- Law Enforcement
- Border Security

---
