# GLVQ-Backpropagation-from-Scratch-Perbandingan-Klasifikasi-Python
Implementasi algoritma GLVQ dan Backpropagation Neural Network dari nol menggunakan Python. Backpropagation diuji dengan fungsi aktivasi Sigmoid dan TanH. Evaluasi mencakup waktu pelatihan, waktu pengujian, akurasi, F-measure, sensitivitas, dan spesifisitas.

Proyek ini berisi **implementasi dari nol (from scratch)** dua algoritma pembelajaran mesin populer, yaitu:
* **Generalized Learning Vector Quantization (GLVQ)**
* **Backpropagation Neural Network (dengan fungsi aktivasi Sigmoid & TanH)**

Tujuan utama dari proyek ini adalah membandingkan kinerja dari ketiga varian model tersebut dari segi:
* Waktu pelatihan
* Waktu pengujian
* Akurasi dan metrik evaluasi lainnya

---
### ⚙️ Fitur Utama
* 💻 Implementasi 100% dari nol tanpa library ML seperti Scikit-learn atau TensorFlow
* 🔁 Fungsi aktivasi dapat disesuaikan (Sigmoid dan TanH)
* 📈 GLVQ dengan update berbasis diferensiasi fungsi cost
* 🧪 Termasuk eksperimen benchmarking (akurasi, F1, sensitivitas, spesifisitas)
* ⏱️ Pengukuran waktu training dan testing secara presisi

---
### 📊 Hasil Eksperimen
Hasil pengujian performa model terhadap dataset yang sama menghasilkan perbandingan sebagai berikut:

| Model                     | Waktu Train (detik) | Waktu Test (detik) | Akurasi (%) | F-Measure | Sensitivitas | Spesifisitas |
| ------------------------- | ------------------- | ------------------ | ----------- | --------- | ------------ | ------------ |
| Backpropagation (Sigmoid) | 233.91              | 0.0342             | 97.22       | 0.9856    | 0.9728       | 0.9394       |
| Backpropagation (TanH)    | 210.97              | 0.0188             | 96.80       | 0.9834    | 0.9685       | 0.9394       |
| GLVQ                      | 171.60              | 0.0199             | 98.02       | 0.9900    | 0.9930       | 0.3485       |

📌 **Catatan**:
* GLVQ menunjukkan *akselerasi pelatihan tercepat* dan akurasi tertinggi.
* Namun, spesifisitas GLVQ rendah dibandingkan Backpropagation, yang menunjukkan trade-off terhadap class imbalance.

### 📂 Struktur Folder

```
glvq-backprop-scratch/
├── code.ipynb             # GLVQ dan Backpropagation from scratch
├── dataset.xlsx            # Dataset yang dipakai
├── results.xlsx           # Hasil eksperimen dalam format Excel
└── README.md              # Dokumentasi ini
```
