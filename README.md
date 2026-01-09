# 🌱 Potato Leaf Disease Detection
> **Automated Detection of Late Blight in Potato Crops using Deep Learning**

![Potato Leaf](https://img.shields.io/badge/Status-Completed-success)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview
Potatoes are one of the most critical staple crops globally. However, diseases like **Late Blight** (*Phytophthora infestans*) can cause devastating yield losses (up to 100%).

This project aims to develop a robust **Computer Vision** system to automatically classify potato leaves into two categories:
1.  **Healthy** ✅
2.  **Late Blight** ⚠️

By leveraging **Deep Learning** techniques, specifically **Convolutional Neural Networks (CNN)** and **Transfer Learning**, we aim to provide an accurate and rapid diagnostic tool for farmers.

---

## 🚀 Key Features
- **Data Augmentation:** Overcame limited dataset size (430 images) using rotation, zooming, and flipping techniques.
- **Custom CNN Architecture:** A manually designed CNN model trained from scratch.
- **Transfer Learning:** Implementation of state-of-the-art models **ResNet152** and **ResNet50** for superior performance.
- **Performance Evaluation:** Comparative analysis using Accuracy and Confusion Matrix metrics.

---

## 📂 Dataset Details
- **Source:** Kaggle Potato Health Dataset (Ethiopia, Holeta Region).
- **Conditions:** Real-world farm images with noisy backgrounds and varying lighting.
- **Classes:**
    - `Healthy`: 363 Images
    - `Late Blight`: 67 Images
- **Preprocessing:** Images were resized and normalized. Data augmentation was applied to balance and expand the dataset.

---

## 🛠️ Technologies Used
- **Language:** Python 🐍
- **Deep Learning:** TensorFlow, Keras
- **Image Processing:** OpenCV, PIL
- **Data Visualization:** Matplotlib, Seaborn
- **Utilities:** NumPy, Pandas, Pathlib

---

## 📊 Methodology
1.  **Data Preprocessing:** Loading images, resizing, and normalizing pixel values.
2.  **Augmentation:** Applied `ImageDataGenerator` to increase dataset diversity.
3.  **Model 1 (Manual CNN):** Built a sequential CNN with Conv2D, MaxPooling, and Dropout layers.
4.  **Model 2 (Transfer Learning):** Utilized **ResNet152** & **ResNet50** (pre-trained on ImageNet) with fine-tuning on potato data.
5.  **Evaluation:** Models were tested on unseen data to calculate accuracy and loss.

---

## ⚙️ Installation & Usage
1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/potato-disease-detection.git
    cd potato-disease-detection
    ```

2.  **Install Dependencies:**
    ```bash
    pip install tensorflow opencv-python matplotlib seaborn pandas
    ```

3.  **Run the Notebook:**
    Open `SerdarYARDIMCI_Final.ipynb` in [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/).

---

## 📈 Results
*Comparative results of the models implemented in this project:*

| Model | Accuracy | Remarks |
|-------|----------|---------|
| **Manual CNN** | *TBD* | Baseline model |
| **ResNet50** | *TBD* | Pre-trained weighted |
| **ResNet152** | *TBD* | Deeper architecture |

*(See the notebook for detailed confusion matrices and training graphs)*

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](https://github.com/yourusername/potato-disease-detection/issues).

## 📝 License
This project is licensed under the [MIT License](LICENSE).

---
<p align="center">
  Developed by <strong>Serdar Yardımcı</strong>
</p>
