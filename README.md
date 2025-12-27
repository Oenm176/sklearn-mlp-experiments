# 🧠 Employee Attrition Prediction using MLP (Neural Network)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

Project ini adalah implementasi **Jaringan Syaraf Tiruan (JST)** menggunakan algoritma **Multi-Layer Perceptron (MLP)** untuk memprediksi tingkat risiko *attrition* (keluar masuknya) karyawan.

Eksperimen ini membandingkan kinerja model dengan berbagai **Learning Rate**, **Split Data Ratio**, dan **Solver (Optimizer)** yang berbeda.

## 📂 Project Structure

Struktur file dalam repository ini disusun sebagai berikut:

```text
├── 📂 data/
│   └── processed_attrition_data.csv    # Dataset hasil preprocessing (Scaled & Cleaned)
│
├── 📂 notebooks/
│   ├── 2_Experiment_Config1_50_50.ipynb  # Eksperimen Split 50% Train : 50% Test
│   ├── 3_Experiment_Config2_60_40.ipynb  # Eksperimen Split 60% Train : 40% Test
│   └── 4_Experiment_Config3_70_30.ipynb  # Eksperimen Split 70% Train : 30% Test
│
├── 📂 output/
│   
├── README.md           # Dokumentasi Project
└── requirements.txt    # Daftar library yang dibutuhkan