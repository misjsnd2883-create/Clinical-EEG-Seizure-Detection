# Clinical-EEG-Seizure-Detection# 🧠 Clinical EEG Seizure Detection using Deep Learning (1D-CNN)

### 👤 Author: Mohamed | Biochemistry & Physiology Student @ Cairo University

## 🚀 Project Overview
This repository contains a high-performance **End-to-End Pipeline** for detecting epileptic seizures from real-world clinical EEG signals. It bridges the gap between **Neurophysiology** and **Artificial Intelligence** by processing raw brainwave data to identify neural patterns associated with seizure events.

## 🛠️ Technical Stack
*   **Domain:** Neuroscience / Bioinformatics / Clinical AI.
*   **Data Processing:** `MNE-Python` (Filtering, Resampling, Windowing).
*   **Deep Learning:** `TensorFlow/Keras` (Custom 1D-CNN Architecture).
*   **Data Source:** **CHB-MIT Scalp EEG Database** via **PhysioNet**.

## 🧬 Key Research Features
*   **Real Data Integration:** Direct handling of `.edf` clinical files.
*   **Subject-Wise Integrity:** Strategic data splitting (Subject-level) to prevent "Data Leakage" and ensure scientific accuracy.
*   **Adaptive 1D-CNN:** A robust architecture designed to extract frequency-domain features from multi-channel neural signals using `GlobalAveragePooling1D`.

## 📊 Results & Validation
- **Seizure Detection:** The model successfully identified **Seizure events (Class 1)** in unseen clinical data with real-time confidence scoring.
- **Signal Processing:** Implemented 1-40Hz filtering to isolate biological brain activity from environmental noise.

---
### 🔗 Research & Collaboration
*Currently developing expertise in Computational Neuroscience and Digital Bio-Diagnostics. Open for Research/PhD opportunities.*
