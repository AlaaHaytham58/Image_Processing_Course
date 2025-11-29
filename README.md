🖼️ Image Processing Course – Labs & Projects (1–10)
<p align="center"> <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge"/> <img src="https://img.shields.io/badge/OpenCV-Image%20Processing-green?style=for-the-badge"/> <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge"/> <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge"/> </p>

A complete collection of Image Processing labs (1–10) built during the course, covering the full pipeline from basic image operations to segmentation, morphology, feature extraction, HOG classification, and SIFT-based matching.

This repository is ideal for:

Students learning digital image processing

Researchers looking for classical CV techniques

Anyone who wants hands-on, beginner → intermediate vision skills

📚 Table of Contents

Overview

Features

Repository Structure

Labs Overview (1–10)

Installation

Requirements

Usage

Tech Stack

Learning Outcomes

Contributing

License

Author

🔍 Overview

This repository contains a complete series of 10 hands-on labs exploring core topics in digital image processing using Python, OpenCV, NumPy, and scikit-image.

Each lab features:

Clean, commented code

Visual outputs and plots

Practical exercises

Step-by-step demonstrations

The content follows a natural progression from fundamentals → advanced concepts.

⭐ Features

✔️ Covers 10 labs from basics to advanced CV
✔️ Clean, educational Jupyter notebooks
✔️ Real image examples & visual explanations
✔️ Morphology, segmentation, HOG, SIFT, and more
✔️ Excellent study reference for exams and projects
✔️ Works on all major operating systems

🗂️ Repository Structure
Image_Processing_Course/
│
├── Lab1/
├── Lab2/
├── Lab3/
├── Lab4/
├── Lab5/
├── Lab6/   # Morphology
├── Lab7/   # Segmentation (Part 1)
├── Lab8/   # Segmentation (Part 2)
├── Lab9/   # HOG + Classification
├── Lab10/  # SIFT + Harris features
│
├── utils/
├── requirements.txt
└── README.md

🔬 Labs Overview (1–10)
📌 Lab 1 — Introduction to Image Processing

Reading & displaying images

RGB vs Grayscale

Basic pixel operations

Histograms

Image resizing, flipping, cropping

📌 Lab 2 — Spatial Filtering & Smoothing

Convolution & correlation

Box filters / Gaussian filters

Smoothing & denoising

Sharpening (Laplacian, high-boost)

📌 Lab 3 — Edge Detection & Gradients

Sobel, Prewitt, Roberts

Gradient magnitude & direction

Canny edge detection

Basic thresholding

📌 Lab 4 — Histogram Processing & Enhancement

Histogram equalization

Contrast stretching

Adaptive histogram equalization (CLAHE)

Brightness/contrast control

📌 Lab 5 — Feature Detection (Classical Methods)

Harris Corner Detector

Shi–Tomasi Detector

FAST detection

Intro to feature descriptors

📌 Lab 6 — Morphological Image Processing

Structuring elements

Erosion & dilation

Opening & closing

Morphological gradient

Hit-or-miss

Noise cleaning and shape extraction

📌 Lab 7 — Image Segmentation (Part 1)

Global thresholding

Otsu's method

Local/adaptive thresholding

Region growing

Connected components

📌 Lab 8 — Image Segmentation (Part 2)

Watershed segmentation

Marker-controlled watershed

Basic graph segmentation

Region merging

Superpixel segmentation (SLIC)*

📌 Lab 9 — HOG Features & Classification

Histogram of Oriented Gradients

Feature extraction pipeline

Sliding window overview

ML classifiers (SVM, kNN)

Evaluation metrics

📌 Lab 10 — Local Feature Detection & Matching (SIFT + Harris)

SIFT feature extraction

Scale-space theory

Descriptor matching (FLANN)

Harris corners extended

Application: image matching & alignment

🛠️ Requirements

The repository includes a requirements.txt file with everything needed.

requirements.txt:
numpy
matplotlib
opencv-python
scikit-image
scipy
jupyter
notebook
scikit-learn


Install dependencies using:

pip install -r requirements.txt

⚙️ Installation
1. Clone the repository
git clone https://github.com/AlaaHaytham58/Image_Processing_Course.git
cd Image_Processing_Course

2. Install requirements
pip install -r requirements.txt

3. Launch Jupyter Notebook
jupyter notebook

▶️ Usage

Open any lab folder

Run the .ipynb notebook

Adjust parameters to see effects visually

Explore image outputs and plots

Combine techniques for mini-projects

🧰 Tech Stack

Python 3.x

OpenCV

NumPy

Matplotlib

SciPy

Scikit-image

Scikit-learn

Jupyter Notebook

🎓 Learning Outcomes

By completing these labs, you will learn:

📘 Fundamentals

Pixel operations

Filtering & enhancement

Histogram processing

📗 Intermediate

Edge detection

Morphology

Segmentation

📙 Advanced

HOG & classification

SIFT matching

Feature tracking

This provides a complete foundation for moving into modern deep learning computer vision.
