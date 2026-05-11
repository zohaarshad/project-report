# 🧬 Women's Vital Organs Cancer Classification Using Deep Learning

**Final Year Project | Bachelor of Software Engineering**
**Lahore Garrison University, Lahore**
**Supervised by: Mr. Omer Aftab**

---

## 📌 Overview

Cancer remains one of the leading causes of death worldwide, and early detection is critical to improving survival rates. This project presents a deep learning-based system for the **early classification of cancer in women's vital organs** — specifically the **liver, lungs, kidneys (renal), and ovaries**.

The system analyzes MRI images using state-of-the-art Convolutional Neural Network (CNN) models to classify whether an organ shows signs of cancer, providing medical professionals with a fast, accurate, and non-invasive diagnostic tool.

---

## 🎯 Objectives

- Develop a CNN-based model to classify cancer in women's vital organs from MRI images
- Train and evaluate deep learning models (ResNet-50 and VGG-19) on medical imaging data
- Build a user-friendly web interface for real-time cancer detection
- Provide an accurate, non-invasive alternative to traditional diagnostic methods

---

## 🧠 Deep Learning Models

| Model | Training Accuracy | Validation Accuracy |
|-------|-------------------|----------------------|
| ResNet-50 | 100% | 93.4% |
| VGG-19 | 100% | 93.7% |

Both models were trained for **40 epochs** on an augmented dataset of MRI images.

---

## 🗂️ Dataset

- **Source:** The Cancer Imaging Archive (TCIA) — provided by the National Cancer Institute (NCI)
- **Classes:** Liver Cancer, Lung Cancer, Renal Cancer, Ovarian Cancer
- **Augmentation:** Images were augmented to **1,000 images per class** for balanced training

| Class | Before Augmentation | After Augmentation |
|-------|---------------------|---------------------|
| Liver | 188 | 1000 |
| Lungs | 153 | 1000 |
| Ovarian | 334 | 1000 |
| Renal | 751 | 1000 |

---

## 🛠️ Tools & Technologies

- **Language:** Python 3
- **Deep Learning:** TensorFlow, Keras
- **Models:** ResNet-50, VGG-19
- **Frontend:** Gradio
- **Environment:** Google Colaboratory

---

## 🖥️ How It Works

1. Medical staff uploads an MRI image through the Gradio interface
2. The image is preprocessed (resized, normalized, augmented)
3. The trained CNN model classifies the image into one of four cancer types
4. The result is displayed on screen with the detected cancer type

---

## 📄 Project Report

The full thesis report is available in this repository:
👉 [View Project Report (PDF)](./project_thesis_report.pdf)

---

## 🏫 Institution

**Department of Software Engineering**
Lahore Garrison University, Lahore
Session: 2020 – 2024
