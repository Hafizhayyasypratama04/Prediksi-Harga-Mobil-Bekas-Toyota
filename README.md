# Prediksi Harga Mobil Bekas

MIT License | Python 3.8+ | Streamlit | Scikit-learn

Aplikasi interaktif untuk memprediksi harga mobil bekas berdasarkan data spesifik pengguna. Dibangun menggunakan Streamlit untuk antarmuka pengguna yang intuitif.

---

## Demo Prediksi Harga Mobil Bekas

![Demo Video](demo.gif)

✨ **Fitur Utama**

🧠 **Machine Learning yang Akurat**

- Algoritma prediksi harga berbasis data.
- Dukungan berbagai model regresi.
- Evaluasi performa menggunakan MAE dan MAPE.

📊 **Analisis Data Interaktif**

- Eksplorasi data secara visual.
- Grafik dan tabel interaktif.

🌐 **Antarmuka Pengguna Modern**

- Desain responsif.
- Antarmuka berbasis web yang mudah digunakan.

---

## 🚀 Quickstart

### Prasyarat

Pastikan Anda telah menginstal:

- Python 3.8 atau lebih tinggi
- `pip` untuk mengelola pustaka Python

```bash
# Periksa versi Python
python --version
```

### Instalasi

1. Clone repositori:

   ```bash
   git clone https://github.com/Hafizhayyasypratama04/Prediksi-Harga-Mobil-Bekas.git
   cd Prediksi-Harga-Mobil-Bekas
   ```

2. Setup environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # atau
   venv\Scripts\activate  # Windows
   ```

3. Install dependensi:

   ```bash
   pip install -r requirements.txt
   ```

4. Jalankan aplikasi:

   ```bash
   streamlit run app.py
   ```

5. Buka browser dan akses `http://localhost:8501`.

---

## 🏗️ Arsitektur Sistem

📁 **Struktur Proyek**

```
Prediksi-Harga-Mobil-Bekas/
├── assets/
│   ├── demo.gif
│   ├── Untitled video - Made with Clipchamp.mp4
├── dataset/
│   ├── data.csv
│   ├── model.pkl
├── app.py
├── requirements.txt
└── README.md
```

---

## 🛠️ Teknologi yang Digunakan

### Backend

- **Streamlit**: Framework untuk aplikasi web interaktif.
- **Scikit-learn**: Model machine learning.
- **Pandas**: Manipulasi data.
- **NumPy**: Komputasi numerik.

### Frontend

- **HTML5**
- **CSS3**
- **Streamlit Widgets**: Komponen interaktif bawaan.

---

## 💡 Penggunaan

### Contoh Interaksi

```python
# Inisialisasi model prediksi
from app.models.predictor import CarPricePredictor

model = CarPricePredictor()

# Contoh penggunaan
input_data = {
    "year": 2018,
    "brand": "Toyota",
    "km_driven": 50000,
    "owner": "First",
    "seller_type": "Dealer",
    "ex_showroom_price": 1200000
}

predicted_price = model.predict(input_data)
print(f"Prediksi Harga: Rp{predicted_price}")
```

### API Endpoints

| Endpoint     | Metode | Deskripsi                        |
| ------------ | ------ | -------------------------------- |
| `/`          | GET    | Halaman utama aplikasi           |
| `/predict`   | POST   | Endpoint untuk memprediksi harga |
| `/visualize` | GET    | Grafik dan tabel interaktif      |

---

## 🧪 Testing

Jalankan unit tests:

```bash
python -m pytest tests/
```

Coverage testing:

```bash
pytest --cov=app tests/
```

---

## 🤝 Kontribusi

Kontribusi membuat komunitas open source menjadi tempat yang luar biasa untuk belajar, menginspirasi, dan berkreasi. Setiap kontribusi yang Anda berikan sangat dihargai.

1. Fork proyek ini.
2. Buat branch fitur Anda.
3. Commit perubahan Anda.
4. Push ke branch.
5. Buka Pull Request.

Lihat panduan kontribusi untuk detail lebih lanjut.

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT. Lihat file [LICENSE](LICENSE) untuk informasi lebih lanjut.

---

## 📬 Kontak

- **Hafizh Ayyasy Pratama** - [@Hafizhayyasypratama04](https://github.com/Hafizhayyasypratama04)
- **[Nama Teman Anda]** - [Kontak atau Akun Anda]

---

## 🙏 Pengakuan

- Streamlit Documentation
- Scikit-learn Tutorials
- Pandas Documentation

⭐️ Star repository ini jika membantu proyek Anda!

