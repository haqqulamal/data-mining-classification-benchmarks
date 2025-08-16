# Data Mining — Classification (KNN/SVM/Random Forest)

End-to-end workflow untuk tugas klasifikasi klasik: **EDA → preprocessing → training → evaluasi**, dibangun dengan Python & scikit-learn.
Notebook utama: `notebooks/DataMining.ipynb`.

> Opsi tambahan: baseline **clustering** (KMeans/DBSCAN) untuk eksplorasi struktur data.

## Metodologi Singkat
- **EDA**: ringkasan statistik, missing values, distribusi target.
- **Preprocessing**: imputasi, encoding (OneHot/Ordinal), scaling (Standard/MinMax), train/validation split.
- **Model**: K-Nearest Neighbors, SVM (RBF/linear), Random Forest (grid search ringan).
- **Evaluasi**: Accuracy, Precision, Recall, F1, Confusion Matrix, (opsional ROC-AUC untuk biner).
- **Clustering (opsional)**: KMeans/DBSCAN + elbow/silhouette untuk n_cluster.

## Hasil (contoh, ganti angka sesuai notebook)
- **Random Forest** akurasi ≈ `0.xx`, **F1** ≈ `0.xx`
- **SVM** akurasi ≈ `0.xx`, **F1** ≈ `0.xx`
- **KNN** akurasi ≈ `0.xx`, **F1** ≈ `0.xx`  
Lihat `results/metrics.json` & `results/*.png` untuk detail (confusion matrix/ROC).

## Struktur Proyek
