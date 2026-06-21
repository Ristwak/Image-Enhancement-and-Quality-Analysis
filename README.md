# Image Enhancement and Quality Analysis using ICCBF, CLAHE, ICS and CNN

## 📌 Overview

This project presents a research-oriented image enhancement framework designed for low-quality and traffic surveillance images. The study evaluates multiple enhancement techniques and compares their performance using objective image quality metrics and computational performance metrics.

The project implements and compares:

* CLAHE + ICS Optimization
* Histogram Equalization (HE)
* Improved Cuckoo Search (ICS)
* Hybrid HE + ICS
* ICCBF (Improved Cuckoo Search-based CLAHE with Bilateral Filtering)
* CNN-based Enhancement Framework
* CNN + ICS
* CNN Hybrid Enhancement

The framework is evaluated using image quality metrics such as SSIM, PSNR, MSE, MAE, Entropy, and EPI, along with computational metrics including Execution Time, Memory Usage, and Runtime Efficiency.

---

# ⚙️ Techniques Implemented

## 1. CLAHE + ICS

Contrast enhancement using:

* Contrast Limited Adaptive Histogram Equalization (CLAHE)
* Improved Cuckoo Search (ICS) parameter optimization
* Adaptive sharpening

Outputs:

* Enhanced Images
* Quality Metrics
* Computational Performance Metrics

---

## 2. Histogram Equalization (HE)

Traditional histogram equalization for global contrast enhancement.

Outputs:

* Enhanced Images
* Quality Metrics
* Computational Performance Metrics

---

## 3. ICS Enhancement

Image enhancement using optimized sigmoid transformation controlled by Improved Cuckoo Search.

Outputs:

* Enhanced Images
* Quality Metrics
* Computational Performance Metrics

---

## 4. Hybrid HE + ICS

Combined enhancement pipeline:

HE → ICS Optimization

Outputs:

* Enhanced Images
* Quality Metrics
* Computational Performance Metrics

---

## 5. ICCBF Framework

The proposed framework combines:

* CLAHE
* Improved Cuckoo Search (ICS)
* Bilateral Filtering

Pipeline:

Input Image
→ CLAHE Enhancement
→ ICS Parameter Optimization
→ Bilateral Filtering
→ Enhanced Output

Outputs:

* Enhanced Images
* Quality Metrics
* Computational Performance Metrics

---

## 6. CNN-Based Enhancement

Deep feature-based enhancement using:

* VGG16 Feature Extraction
* CNN-guided Optimization
* Improved Cuckoo Search

Outputs:

* Enhanced Images
* Quality Metrics
* Computational Performance Metrics

---

# 📊 Evaluation Metrics

## Image Quality Metrics

| Metric  | Description                         |
| ------- | ----------------------------------- |
| SSIM    | Structural Similarity Index Measure |
| PSNR    | Peak Signal-to-Noise Ratio          |
| MSE     | Mean Squared Error                  |
| MAE     | Mean Absolute Error                 |
| Entropy | Information Content                 |
| EPI     | Edge Preservation Index             |

---

## Computational Performance Metrics

Added to satisfy reviewer recommendations.

| Metric               | Description             |
| -------------------- | ----------------------- |
| Execution Time (sec) | Total processing time   |
| Memory Usage (MB)    | Peak memory consumption |
| Runtime Efficiency   | 1 / Execution Time      |

---

# 🧠 Research Workflow

## CLAHE Pipeline

Input Image
→ Denoising
→ CLAHE
→ ICS Optimization
→ Adaptive Sharpening
→ Enhanced Image
→ Metrics Evaluation

---

## HE + ICS Pipeline

Input Image
→ Histogram Equalization
→ ICS Optimization
→ Enhanced Image
→ Metrics Evaluation

---

## ICCBF Pipeline

Input Image
→ CLAHE
→ ICS Optimization
→ Bilateral Filtering
→ Enhanced Image
→ Metrics Evaluation

---

## CNN Pipeline

Input Image
→ VGG16 Feature Extraction
→ ICS Optimization
→ CNN-Based Enhancement
→ Metrics Evaluation

---

# 📁 Project Structure

Based on the current Google Drive organization:

```text
Colab Notebooks/
│
├── CLAHE.ipynb
├── HE+ICS.ipynb
├── ICCBF.ipynb
├── imagequality.ipynb
├── CNN.ipynb
│
├── data/
│   └── low_quality_images/
│
├── results/
│
│   ├── output_CLAHE/
│   │   ├── FINAL_FIXED/
│   │   ├── final_results.csv
│   │   ├── performance_summary.csv
│   │   └── system_info.csv
│
│   ├── output_ICCBF/
│   │   ├── enhanced_images/
│   │   ├── results.csv
│   │   ├── performance_summary.csv
│   │   └── system_info.csv
│
│   ├── HE+ICS+HYBRID/
│   │   ├── HE/
│   │   ├── ICS/
│   │   ├── HYBRID/
│   │   ├── final_results.csv
│   │   └── performance_summary.csv
│
│   ├── CNN/
│   │   ├── ICS_CNN/
│   │   ├── HYBRID_CNN/
│   │   ├── results.csv
│   │   └── performance_summary.csv
│
└── Reference Papers/
```

---

# 🚀 Running the Project

## Step 1

Open the required notebook:

* CLAHE.ipynb
* HE+ICS.ipynb
* ICCBF.ipynb
* CNN.ipynb
* imagequality.ipynb

---

## Step 2

Mount Google Drive

```python
from google.colab import drive
drive.mount('/content/drive')
```

---

## Step 3

Ensure dataset location:

```text
/content/drive/MyDrive/Colab Notebooks/data/low_quality_images
```

---

## Step 4

Run all notebook cells.

Generated outputs will automatically be stored in:

```text
Colab Notebooks/results/
```

---

# 📈 Generated Outputs

Each notebook generates:

### Enhanced Images

Stored in their respective result folders.

### Quality Analysis CSV

Contains:

* SSIM
* PSNR
* MSE
* MAE
* Entropy
* EPI

### Performance Analysis CSV

Contains:

* Execution Time
* Memory Usage
* Runtime Efficiency

### System Information CSV

Contains:

* Processor Details
* CPU Core Count
* Operating System Information

---

# 🔬 Research Contribution

The study proposes ICCBF (Improved Cuckoo Search-based CLAHE with Bilateral Filtering), a hybrid enhancement framework that combines contrast enhancement, optimization, and edge-preserving noise reduction for improving low-quality traffic surveillance images.

Experimental evaluation includes:

* Traditional Enhancement Methods
* Optimization-Based Enhancement Methods
* Deep Learning-Based Enhancement Methods
* Computational Performance Analysis

---

# 📄 Research Paper

The accompanying research paper evaluates all enhancement frameworks using objective image quality metrics and computational performance metrics for traffic surveillance image enhancement.

---

# 👨‍💻 Author

**Ristwak Pandey**

B.Tech Computer Science Engineering

Game Developer | XR Developer | Research Enthusiast
