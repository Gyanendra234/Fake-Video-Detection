# Fake-Video-Detection
##This project detects whether a given video is **REAL or FAKE (deepfake)** using a deep learning model trained on manipulated facial data. It performs **face extraction from video frames**, applies a trained **binary classifier**, and outputs a final prediction. This helps fight misinformation, manipulated media, and deepfake content.
## 🧠 Project Overview

With the rising threat of deepfake videos, detecting AI-generated facial manipulations has become critical. This project offers an automated solution for detecting such manipulated videos using:

- Deep Learning classification
- Frame-by-frame face detection
- Final video verdict (Real/Fake)

---

## 🎯 Objectives

- Detect fake videos by analyzing human facial features
- Build an inference pipeline for real-time prediction
- Use a pre-trained model on a benchmark dataset
- Automate face extraction and classification from videos

---

## 🧰 Tools & Technologies

- 🧠 **PyTorch** – for model loading and prediction
- 🎥 **OpenCV** – video reading and frame extraction
- 👤 **MTCNN** – face detection from frames
- 🧪 **FaceForensics++ Dataset** – training data
- 📝 **Python, NumPy, Pandas** – scripting and data handling

---

## 📦 Dataset: FaceForensics++

This project leverages the **[FaceForensics++](https://github.com/ondyari/FaceForensics)** dataset — a large-scale benchmark for facial manipulation detection.

### 🔍 Features:
- 1,000+ real videos collected from YouTube
- Four manipulation methods:
  - **DeepFakes**
  - **FaceSwap**
  - **Face2Face**
  - **NeuralTextures**
- Includes compressed and raw videos
- Pre-cropped face images available
- Used for training and validating deepfake detection models

📌 **License:** Academic use only

