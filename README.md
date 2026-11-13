8. Praktikum Bab 8: Support Vector Machine (SVM) & Kernel

### 1. Perbandingan Kernel SVM (Praktikum 8.7):
- **Linear Kernel:** Cocok untuk data yang dapat dipisahkan secara linier (*linearly separable*). Proses pelatihan cenderung cepat dan sederhana.
- **Polynomial (poly) Kernel:** Efektif untuk menangani pola data berderajat lebih tinggi, namun memerlukan penyesuaian parameter derajat (*degree*) yang tepat.
- **RBF (Radial Basis Function) Kernel:** Sangat ampuh untuk data non-linier kompleks dengan memetakannya ke dimensi yang lebih tinggi menggunakan parameter $C$ dan $\gamma$ (gamma)[cite: 10].

### 2. Visualisasi Decision Boundary & Tuning:
- **Pipeline & Scaling:** Penggunaan `StandardScaler` sangat krusial pada SVM agar skala antar fitur tidak timpang, yang dapat mendistorsi pembentukan bidang batas keputusan (*decision boundary*).
- **Analisis Hyperparameter:** Area performa terbaik (*puncak*) pada kombinasi nilai $C$ dan gamma ditemukan pada rentang optimal tertentu untuk menghindari risiko *underfitting* maupun *overfitting*[cite: 10].
