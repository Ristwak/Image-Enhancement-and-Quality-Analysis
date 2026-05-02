# Image Enhancement and Quality Analysis

## 📌 Overview

This project presents a research-based approach to image enhancement and quality evaluation using classical image processing techniques along with deep learning.

The pipeline combines methods like CLAHE, Histogram Equalization (HE), ICCBF filtering, and a CNN model to analyze and improve image quality.

---

## ⚙️ Techniques Used

* CLAHE (Contrast Limited Adaptive Histogram Equalization)
* Histogram Equalization (HE)
* ICCBF Filtering
* Image Quality Analysis
* Convolutional Neural Networks (CNN)

---

## 🧠 Workflow

1. Apply CLAHE for contrast enhancement
2. Perform Histogram Equalization + ICS
3. Apply ICCBF filtering
4. Evaluate image quality
5. Use CNN for final analysis

---

## 📁 Project Structure

```
image-enhancement-research/
│── notebooks/
│     ├── 01_CLAHE.ipynb
│     ├── 02_HE_ICS.ipynb
│     ├── 03_ICCBF.ipynb
│     ├── 04_image_quality.ipynb
│     ├── 05_CNN.ipynb
│── data/
│── results/
│── paper/
│     └── paper.pdf
│── requirements.txt
│── README.md
```

---

## 🚀 How to Run

1. Download or clone this repository

2. Upload the entire folder to your **Google Drive** (keep the same structure)

3. Open the notebooks using **Google Colab**

4. Mount your Google Drive:

```python
from google.colab import drive
drive.mount('/content/drive')
```

5. Update file paths if required (e.g., `/content/drive/MyDrive/...`)

6. Run the notebooks step by step

---

### ⚠️ Note

This project was developed using Google Colab with Google Drive for file handling.
To run without modifying the code, it is recommended to follow the Drive-based setup.


---

## 📊 Results

The project demonstrates how combining traditional image enhancement techniques with CNN improves image quality and analysis.

---

## 📄 Research Paper

The complete research paper is included in the `paper/` directory.

---

## 👨‍💻 Author

Ristwak Pandey
