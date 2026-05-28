# 🚗 Pothole Detection System

> Computer Vision Project — Smart City Infrastructure

## 📌 Overview

A computer vision system that detects potholes from road images using image processing and machine learning. The project supports automated road maintenance workflows and smart city infrastructure by enabling real-time pothole identification.

---

## 🎯 Objectives

- Detect potholes accurately from road images
- Apply image processing techniques for feature extraction
- Support smart city and automated road maintenance applications

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| OpenCV | Image processing and feature extraction |
| Scikit-learn | Classification model |
| NumPy | Numerical operations |
| Matplotlib | Visualisation |
| Jupyter Notebook | Development environment |

---

## 📁 Project Structure

```
pothole-detection-system/
│
├── data/
│   └── sample_images/           # Sample road images
│
├── notebooks/
│   └── pothole_detection.ipynb  # Main notebook
│
├── src/
│   ├── detect.py                # Detection pipeline
│   └── preprocess.py            # Image preprocessing
│
├── outputs/
│   └── results/                 # Annotated output images
│
├── requirements.txt
└── README.md
```

---

## ⚙️ How It Works

1. Road image is loaded and preprocessed (grayscale, blur, edge detection)
2. Region of interest is extracted
3. Features are passed to a trained classifier
4. Pothole regions are highlighted on the output image

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/AmerAhmed-creator/pothole-detection-system.git
cd pothole-detection-system

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook notebooks/pothole_detection.ipynb
```

---

## 📜 Requirements

```
opencv-python
numpy
scikit-learn
matplotlib
jupyter
```

---

## 👤 Author

**Amer Ahmed Mohammed**
[GitHub](https://github.com/AmerAhmed-creator) • [Email](mailto:mdamerahmedoffical@gmail.com)
