# Stress Detection using EEG Signals

This project was developed to participate in the **XXXI CONEIMERA - Trujillo 2025**.

## 📋 Description

In this project, we focus on detecting stress through EEG (electroencephalogram) signals recorded during arithmetic tasks. The dataset used was obtained from **PhysioNet**:

🔗 [https://physionet.org/content/eegmat/1.0.0/](https://physionet.org/content/eegmat/1.0.0/)

The dataset contains EEG recordings categorized into two conditions:

- **Before the task** (relaxed state)  
- **During the task** (stress condition)

Our goal was to build a machine learning model capable of classifying these two mental states: **Relaxed** and **Stress**.

## ⚙️ Methodology

To prepare and analyze the EEG signals, we applied the following signal processing techniques:

- **Discrete Wavelet Transform (DWT)**
- **Fast Fourier Transform (FFT)**
- **Power Spectral Density (PSD)**

From these processed signals, we extracted **entropy-based features**. Interestingly, the entropy values for the stress condition were significantly lower than those for the relaxed state, making the two classes more separable.

## 🤖 Model

For classification, we used a **Support Vector Machine (SVM)** model trained on the extracted features. The model successfully distinguished between relaxed and stress conditions.

## 👥 Team

This project was carried out by a dedicated research team aiming to contribute to the field of **brain-computer interfaces** and **mental health monitoring**.
