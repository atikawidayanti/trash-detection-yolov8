# Trash Detection using YOLOv8

## Deskripsi

Trash Detection using YOLOv8 merupakan proyek Machine Learning yang dikembangkan untuk mendeteksi dan mengklasifikasikan jenis sampah menggunakan algoritma YOLOv8 (You Only Look Once versi 8). Sistem ini memanfaatkan teknologi Computer Vision untuk mengenali objek sampah secara otomatis sehingga dapat mendukung proses pemilahan sampah yang lebih cepat dan efisien.

---

## Latar Belakang

Pemilahan sampah secara manual masih membutuhkan waktu dan tenaga yang cukup besar serta berpotensi menimbulkan kesalahan. Oleh karena itu, proyek ini dikembangkan untuk memanfaatkan teknologi Deep Learning dalam mendeteksi jenis sampah secara otomatis berdasarkan citra digital.

---

## Tujuan

- Mendeteksi objek sampah pada gambar.
- Mengklasifikasikan sampah berdasarkan jenisnya.
- Membangun model deteksi objek menggunakan YOLOv8.
- Menjadi dasar pengembangan sistem pemilahan sampah otomatis.

---

## Model

- Model : YOLOv8n (Nano)
- Framework : Ultralytics YOLOv8
- Bahasa Pemrograman : Python

---

## Kategori Sampah

Model dilatih untuk mendeteksi tiga kategori sampah, yaitu:

- Organic
- Inorganic
- Metal

---

## Struktur Repository

```
trash-detection-yolov8/
│
├── notebook/
│   └── Proyek UAS ML.ipynb
│
├── hasil/
│   ├── confusion_matrix.png
│   ├── confusion_matrix_normalized.png
│   ├── labels.jpg
│   ├── results.png
│   ├── results.csv
│   ├── train_batch*.jpg
│   ├── val_batch*.jpg
│   └── ...
│
└── README.md
```

---

## Hasil Pelatihan

Model dilatih selama 50 epoch dan menghasilkan performa yang baik dalam mendeteksi objek sampah. Repository ini menyertakan berbagai hasil evaluasi, antara lain:

- Confusion Matrix
- Normalized Confusion Matrix
- Precision Curve
- Recall Curve
- Precision-Recall Curve
- F1 Curve
- Grafik hasil pelatihan
- Visualisasi batch training
- Visualisasi batch validasi

---

## Insight

- YOLOv8 mampu mendeteksi objek sampah dengan cukup baik.
- Variasi dan kualitas dataset sangat memengaruhi performa model.
- YOLOv8n memiliki ukuran model yang ringan sehingga cocok digunakan pada perangkat dengan sumber daya terbatas.
- Model dapat dikembangkan lebih lanjut untuk implementasi deteksi sampah secara real-time.

---

## Teknologi

- Python
- YOLOv8
- Ultralytics
- OpenCV
- NumPy
- Matplotlib
- Google Colab

---

## Author

Atika Widayanti

Teknik Informatika – Universitas Pamulang

GitHub: https://github.com/atikawidayanti
