# 🩺 Medical X-Ray Pneumonia Detection System

An AI-powered medical imaging system that automatically detects Pneumonia from Chest X-Ray images using Deep Learning techniques.

---

## 📌 Project Overview

Pneumonia is a serious respiratory disease that can be difficult to diagnose quickly, especially in areas with limited medical resources.

This project applies Machine Learning / Deep Learning techniques to analyze Chest X-Ray images and classify them into:

- ✅ Normal
- 🫁 Pneumonia

The system helps support medical professionals by providing fast and automated preliminary screening.

---

## 🎯 Objectives

- Detect pneumonia from chest X-ray images
- Improve diagnosis efficiency
- Reduce manual screening workload
- Demonstrate practical applications of AI in healthcare

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Core programming language |
| Jupyter Notebook | Model development |
| TensorFlow / Keras | Deep Learning framework |
| NumPy | Numerical computation |
| Pandas | Data processing |
| Matplotlib | Visualization |
| OpenCV | Image processing |
| Scikit-learn | Evaluation metrics |

---

## 📂 Project Structure

```text
Medical_X-Ray_Pneumonia_Detection_System
│
├── MedicalXray_Starter.ipynb
├── README.md
├── .gitignore
│
├── dataset/
│   ├── train/
│   ├── test/
│   └── val/
│
├── models/
│   └── trained_model.h5
│
└── results/
    ├── accuracy_plot.png
    └── confusion_matrix.png
```

---

## 🧠 Model Workflow

1. Load Chest X-Ray Dataset
2. Image Preprocessing
3. Data Augmentation
4. CNN Model Training
5. Model Evaluation
6. Pneumonia Prediction

---

## 📊 Dataset

Chest X-Ray dataset containing:

- Normal chest X-rays
- Pneumonia chest X-rays

Dataset is commonly used for medical image classification research.

---

## 📈 Evaluation Metrics

The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Example:

| Metric | Score |
|----------|----------|
| Accuracy | 95% |
| Precision | 94% |
| Recall | 96% |
| F1 Score | 95% |

> Replace with your actual results.

---

## 🚀 Installation

Clone repository:

```bash
git clone https://github.com/0836600804/Medical_X-Ray_Pneumonia_Detection_System.git
```

Move to project folder:

```bash
cd Medical_X-Ray_Pneumonia_Detection_System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶ Running the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```text
MedicalXray_Starter.ipynb
```

---

## 🔬 Future Improvements

- Deploy as a Web Application
- Real-time Image Upload
- Multi-class Disease Detection
- Model Explainability using Grad-CAM
- Integration with Hospital Systems

---

## 👨‍💻 Author

**Nguyen Van Duy An**

Data Analyst Student

Artificial Intelligence • Machine Learning • Medical Imaging

---

