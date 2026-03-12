<div align="center">

# Computer Vision — MAT3562E

### Hanoi University of Science, VNU | 2025–2026

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit--image](https://img.shields.io/badge/scikit--image-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

</div>

---

## Overview

Hands-on computer vision labs covering **image processing fundamentals through advanced techniques** — from pixel-level operations to frequency-domain analysis, geometric transformations, and morphological processing.

Each lab includes:
- **Jupyter Notebook** — fully documented implementations (NumPy from-scratch + OpenCV)
- **LaTeX Report** — theory, experiments, and analysis
- **Cheatsheet** — quick-reference for key functions and formulas

---

## Labs

| Lab | Topic | Key Techniques |
|:---:|-------|----------------|
| **01** | [Histogram & Point Processing](lab-01/) | Histogram equalization, gamma correction, log transform, thresholding |
| **02** | [Arithmetic, Logical Ops & 2D Convolution](lab-02/) | Image arithmetic, Otsu thresholding, custom convolution kernel |
| **03** | [Spatial & Frequency Domain Processing](lab-03/) | DFT/FFT, ideal LP/HP filters, Gaussian/median denoising, Canny edge detection, **mini-project: image enhancement pipeline** |
| **04** | [Geometric Transformations](lab-04-05/) | Translation, scaling, rotation, shearing — forward & inverse mapping |
| **05** | [Morphological Operations](lab-04-05/) | Erosion, dilation, opening, closing — binary & grayscale morphology |

---

## Highlights

**From-Scratch Implementations**
- 2D convolution with zero-padding (NumPy) — verified against `cv2.filter2D`
- Morphological erosion/dilation from scratch
- Forward & inverse geometric mapping

**End-to-End Mini-Project (Lab 03)**

Two parallel image enhancement pipelines handling different noise types:

```
Noisy Image → Denoise → Sharpen → Edge Detect
```

| Stage | Gaussian Noise Pipeline | Salt & Pepper Pipeline |
|-------|------------------------|----------------------|
| Denoise | GaussianBlur (5×5) | MedianBlur (5×5) |
| Sharpen | Unsharp masking | Unsharp masking |
| Edge Detect | Canny (30/80) | Canny (30/80) |

---

## Project Structure

```
├── lab-01/          Histogram & point processing
│   ├── lab01_BuiQuangChien_23001837.ipynb
│   ├── lab01_report.tex
│   ├── important_functions_cheatsheet.md
│   └── Data/
├── lab-02/          Arithmetic, logical ops & convolution
│   ├── lab02_arithmetics_logical_operations.ipynb
│   ├── lab02_report.tex
│   ├── lab02_cheatsheet.tex
│   └── data/
├── lab-03/          Spatial & frequency domain + mini-project
│   ├── lab_03_spatial_frequency.ipynb
│   ├── lab03_report.tex
│   ├── lab03_cheatsheet.{md,tex}
│   └── data/
└── lab-04-05/       Geometric transforms & morphology
    ├── lab_04_Geometric_Transformations.ipynb
    └── lab_05_morphology_operation.ipynb
```

---

## Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python 3 |
| Core Libraries | NumPy, OpenCV, scikit-image, Matplotlib |
| Environment | Jupyter Notebook, Google Colab |
| Documentation | LaTeX (custom templates), Markdown |

---

## Quick Start

```bash
pip install numpy opencv-python scikit-image matplotlib jupyter
```

Open any notebook:
```bash
jupyter notebook lab-01/lab01_BuiQuangChien_23001837.ipynb
```

---

## Author

**Bùi Quang Chiến** — MSSV 23001837  
Computer Science, Hanoi University of Science — VNU  

[![GitHub](https://img.shields.io/badge/GitHub-Bravee9-181717?style=flat-square&logo=github)](https://github.com/Bravee9)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Brave9-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/brave9/)
