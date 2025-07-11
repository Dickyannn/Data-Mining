# 🌾 Analisis Pengaruh Encoding pada Neural Network & Random Forest Regressor untuk Prediksi Luas Panen

Perubahan iklim berdampak langsung terhadap hasil panen, sehingga diperlukan model prediksi yang andal berbasis data iklim. Penelitian ini membandingkan dua algoritma machine learning: **Neural Network (NN)** dan **Random Forest Regressor (RFR)** dalam memprediksi luas panen, dengan fokus pada pengaruh metode encoding data.

📊 **Hasil utama:**

- **Neural Network (NN)** dengan **Label Encoding** memberikan performa terbaik:
  - RMSE: **0.6648**
  - MAE: **0.5283**
  - R²: **0.5813**

- **Random Forest Regressor (RFR)** menunjukkan hasil yang **stabil**:
  - Dengan Label Encoding: RMSE **0.6246**, MAE **0.4988**, R² **0.6303**
  - Dengan One-Hot Encoding: RMSE **0.6234**, MAE **0.4978**, R² **0.6318**

🔎 Hasil ini menegaskan bahwa metode encoding harus disesuaikan dengan **karakteristik model dan data**. Pemilihan encoding yang tepat dapat meningkatkan akurasi model prediksi, yang penting dalam mendukung sistem pertanian adaptif terhadap perubahan iklim.

---

## 🔧 Algoritma yang Digunakan

- 🔁 **Neural Network (NN)** – Regresi berbasis arsitektur jaringan saraf tiruan
- 🌲 **Random Forest Regressor (RFR)** – Algoritma ensemble berbasis decision tree

---

## 🧪 Evaluasi Model

| Model | Encoding | RMSE   | MAE    | R²     |
|-------|----------|--------|--------|--------|
| Neural Network | Label Encoding | 0.6648 | 0.5283 | 0.5813 |
| Neural Network | One-Hot Encoding | 0.7176 | 0.5713 | 0.5122 |
| Random Forest Regressor | Label Encoding | 0.6246 | 0.4988 | 0.6303 |
| Random Forest Regressor | One-Hot Encoding | **0.6234** | **0.4978** | **0.6318** |


