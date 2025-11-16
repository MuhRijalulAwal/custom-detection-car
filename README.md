# Custom Detection Car menggunakan YOLOv8

Project **Custom Detection Car** ini bertujuan untuk mendeteksi objek mobil menggunakan model *object detection* YOLOv8. Model ini dapat dilatih dengan dataset custom sehingga mampu mengenali jenis atau kondisi mobil tertentu sesuai kebutuhan.

---

## 🚗 Deskripsi Project

Project ini dibangun menggunakan bahasa **Python** dan memanfaatkan library **YOLOv8 (Ultralytics)** untuk melakukan:

* Deteksi objek mobil secara real-time
* Pelatihan model menggunakan dataset custom.
* Evaluasi performa model hasil training.

Project cocok digunakan untuk berbagai kebutuhan seperti:

* Sistem parkir otomatis.
* Pendataan jumlah kendaraan.
* Pengawasan lalu lintas.
* Sistem keamanan berbasis CCTV.

---

## 📦 Teknologi yang Digunakan

* **Python 3.8+**
* **Ultralytics YOLOv8**
* OpenCV (opsional, untuk video & kamera)
* Jupyter Notebook / Script Python
* Dataset custom (format YOLO)

---

## 📁 Struktur Project

```
custom-detection-car/
├── best.pt
├── data.yaml
├── predict.py
└── README.md
```

---

## 🛠 Instalasi

1. **Clone repositori**

```
git clone https://github.com/username/custom-detection-car.git
cd custom-detection-car
```

2. **Install dependencies**

```
pip install python
```

Atau langsung install YOLOv8:

```
pip install ultralytics
```

---

## Cara Running

* Buka CMD di folder direktori
* Ketik "python predict.py"
