# 🍊 Belajar Klasifikasi Jeruk

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)

> Aplikasi web Machine Learning interaktif untuk memprediksi **kualitas jeruk** berdasarkan atribut fisik dan asal daerah, dibangun dengan Python dan Streamlit.

🔗 **Live Demo:** [belajar-klasifikasi-jeruk-rizal.streamlit.app](https://belajar-klasifikasi-jeruk-rizal.streamlit.app/)

---

## 📌 Tentang Proyek

Proyek ini mengimplementasikan model Machine Learning klasifikasi untuk memprediksi kualitas jeruk berdasarkan fitur-fitur seperti diameter, berat, tebal kulit, kadar gula, asal daerah, warna, dan musim panen. Model dilatih menggunakan dataset jeruk dan di-deploy sebagai aplikasi web interaktif melalui Streamlit.

---

## ✨ Fitur Aplikasi

- 🎚️ **Input Slider** — Pengguna memasukkan nilai Diameter, Berat, Tebal Kulit, dan Kadar Gula secara interaktif
- 🏷️ **Pilihan Kategori** — Memilih Asal Daerah (Kalimantan / Jawa Barat), Warna (hijau / kuning / oranye), dan Musim Panen (kemarau / hujan)
- ⚡ **Prediksi Real-time** — Hasil klasifikasi kualitas jeruk ditampilkan setelah klik tombol **Prediksi**
- 🌙 **Dark Mode UI** — Antarmuka gelap yang bersih dan nyaman digunakan

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Kegunaan |
|-----------|----------|
| Python | Bahasa pemrograman utama |
| Streamlit | Framework web app interaktif |
| scikit-learn | Training & inferensi model ML |
| Joblib | Menyimpan & memuat model (`.joblib`) |
| Pandas | Manipulasi dan analisis data |
| NumPy | Komputasi numerik |
| Jupyter Notebook | Eksplorasi data & eksperimen model |

---

## 🤖 Model Machine Learning

- **Algoritma:** `[Isi — contoh: Random Forest / SVM / KNN]`
- **Dataset:** `[Isi — contoh: Dataset Kualitas Jeruk buatan sendiri / Kaggle]`
- **Fitur Input:** Diameter, Berat, Tebal Kulit, Kadar Gula, Asal Daerah, Warna, Musim Panen
- **Target/Label:** Kualitas Jeruk `[Isi kelas — contoh: Baik / Cukup / Buruk]`
- **Akurasi:** `[Isi — contoh: 92.3%]`

---

## 📁 Struktur Proyek

```
belajar-klasifikasi-jeruk/
│
├── app.py                    # Aplikasi Streamlit (main)
├── notebook.ipynb            # Jupyter Notebook: EDA & training model
├── dataset.csv               # Dataset jeruk (raw)
├── dataset_clean.csv         # Dataset jeruk setelah preprocessing
├── model.joblib              # Model ML yang sudah dilatih & disimpan
└── README.md
```

---

## 📸 Screenshot

![Tampilan Aplikasi](assets/screenshot.png)

> Atau lihat langsung: [belajar-klasifikasi-jeruk-rizal.streamlit.app](https://belajar-klasifikasi-jeruk-rizal.streamlit.app/)

---

## 🚀 Cara Menjalankan Secara Lokal

### Prasyarat
- Python 3.9+
- pip

### Instalasi

```bash
# 1. Clone repository ini
git clone https://github.com/[username]/belajar-klasifikasi-jeruk.git
cd belajar-klasifikasi-jeruk

# 2. Buat virtual environment (disarankan)
python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows

# 3. Install dependencies
pip install streamlit scikit-learn pandas numpy joblib

# 4. Jalankan aplikasi
streamlit run app.py
```

Aplikasi otomatis terbuka di browser pada `http://localhost:8501`

---

## 📖 Cara Penggunaan

1. Buka aplikasi melalui live demo atau jalankan secara lokal
2. Atur nilai **Diameter**, **Berat**, **Tebal Kulit**, dan **Kadar Gula** menggunakan slider
3. Pilih **Asal Daerah**, **Warna**, dan **Musim Panen** sesuai jeruk yang ingin diprediksi
4. Klik tombol **🔴 Prediksi** untuk melihat hasil klasifikasi kualitas jeruk

---

## 👤 Author

**Rizal**

- 🔗 GitHub: [@username](https://github.com/username)
- 🌐 Live App: [belajar-klasifikasi-jeruk-rizal.streamlit.app](https://belajar-klasifikasi-jeruk-rizal.streamlit.app/)

---

## 📄 Lisensi

Proyek ini dibuat untuk keperluan pembelajaran dan portofolio pribadi.  
Bebas dijadikan referensi dengan mencantumkan kredit yang sesuai.

---

<p align="center">Dibuat dengan ❤️ menggunakan Python & Streamlit 🐍</p>
