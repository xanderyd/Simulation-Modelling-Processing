# Simulation-Modelling-Processing

# Optimasi Model Klasifikasi: Baseline vs Grid Search

Proyek ini berfokus pada pengembangan *pipeline* pembelajaran mesin untuk memprediksi tingkat kelulusan mahasiswa berdasarkan dataset performa akademik. Fokus utama proyek adalah melakukan pembersihan data (*data cleaning*), seleksi fitur (*feature selection*), dan optimasi *hyperparameter* untuk meningkatkan performa model.

## 📌 Gambaran Proyek
Tujuan utama adalah membandingkan performa model **Random Forest Classifier** standar (*baseline*) dengan model yang telah dioptimasi menggunakan **Grid Search CV**. Evaluasi dilakukan menggunakan metrik ROC-AUC dan F1-Score serta analisis waktu komputasi.

## 📂 Struktur Kerja
```text
.
├── data/
│   └── dataset_feature_selection.csv   # Dataset Utama
├── notebooks/
│   └── experimentation.ipynb           # Proses Analisis & Pemodelan
├── README.md                           # Dokumentasi Proyek
└── results/
    └── confusion_matrix.png            # Visualisasi Hasil