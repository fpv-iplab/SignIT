# SignIT

[![Website](https://img.shields.io/badge/website-fpv--iplab.github.io-blue)](https://fpv-iplab.github.io/SignIT/)

SignIT is a **comprehensive dataset and benchmark for Italian Sign Language (LIS) recognition**, designed to support research in multimodal sign language analysis and automatic gesture understanding.

## 📌 Overview

SignIT provides a large, annotated collection of sign language videos together with extracted visual features for studying and evaluating sign recognition models.

## 🧠 Dataset Contents

- **Multimodal Dataset:**  
  644 videos (~3.33 hours) covering **94 distinct LIS signs** organized into **five macro-categories**: *Animals*, *Food*, *Colors*, *Emotions*, and *Family*.

- **Annotations and Splits:**  
  Each video is manually segmented into clips containing single sign instances. Data is divided into *training*, *validation*, and *test* splits for benchmarking.

- **2D Keypoints & Media:**  
  For every frame, SignIT includes **2D keypoints extracted** from hands, face, and body using MediaPipe, enabling both pose-based and appearance-based approaches.

## 📊 Benchmarks

SignIT provides baseline models and evaluation protocols for sign recognition, including:

- **K-Nearest Neighbors (K-NN)** on normalized keypoint features  
- **MLP (Multi-Layer Perceptron)** on pose keypoints  
- **Convolutional Models (e.g., ResNet18)** on RGB frames  
- **Multimodal models** combining spatial and temporal information

Standard metrics reported: *accuracy*, *precision*, *recall*, and *F1-score*.

## 📁 Dataset Download

The dataset includes:

- RGB video frames  
- CSV files with frame labels and split information  
- Extracted 2D keypoints for hands, body, and face  

You can download everything from the [official project page](https://fpv-iplab.github.io/SignIT/).

## 🧪 Use Cases

- Training and evaluating sign language recognition models  
- Research on multimodal representation learning  
- Human behavior understanding from egocentric video data

## 📄 Citation

If you use SignIT in your research, please cite the associated paper linked on the project page.

## 🤝 Credits

Developed by the **LIVE@IPLab** group at the *Department of Mathematics and Computer Science – University of Catania* in collaboration with **Next Vision s.r.l.** and supported by academic research programs.
