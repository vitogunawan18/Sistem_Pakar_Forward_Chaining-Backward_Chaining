#Vito Gunawan (2306149)
# 🧠 Sistem Pakar Diagnosis Penyakit - Forward & Backward Chaining

Selamat datang di proyek **Sistem Pakar Diagnosis Penyakit** berbasis aturan!  
Sistem ini mampu mendiagnosis beberapa penyakit umum berdasarkan gejala yang kamu alami.  
Menggunakan pendekatan **Forward Chaining** dan **Backward Chaining**, sistem ini tidak hanya terbatas pada kasus medis, tapi juga dapat digunakan untuk simulasi penalaran logis lainnya.

---

## 📦 Teknologi yang Digunakan

- Python 🐍
- [experta](https://github.com/noxdafox/experta) - pustaka sistem pakar
- Google Colab atau Python environment lokal

---

## 🏥 Penyakit yang Dapat Dideteksi

- 🤧 Flu  
- 😷 Pneumonia  
- 🤒 Common Cold  
- 🔥 Throat Infection  
- 🦠 COVID-19  
- 🌼 Allergic Rhinitis  
- 😮‍💨 Asthma  
- 🤢 Typhoid Fever  
- 😖 Sinusitis  
- 🦟 Dengue Fever  
- 🤯 Migraine  
- 🌡️ Malaria  
- 👁️ Measles  
- 😤 Bronchitis  
- ✅ Kondisi Sehat

---

## 🧪 Studi Kasus Non-Medis

Sistem ini juga memuat implementasi penalaran berbasis aturan dalam konteks **non-medis**, seperti:

- 🐧 **Klasifikasi Hewan**: Menentukan apakah objek adalah penguin, ayam, atau elang
- 💼 **Rekomendasi Karier**: Software Engineer vs UI/UX Engineer
- 🚗 **Identifikasi Kendaraan**: Motor atau mobil berdasarkan atribut

---

## 🧩 Penjelasan Sistem

### 🔄 Forward Chaining
Metode inferensi **maju** ini bekerja dengan:
1. Mengumpulkan fakta awal dari pengguna (misalnya: gejala)
2. Mencocokkan fakta dengan aturan dalam basis pengetahuan
3. Menyimpulkan diagnosis dari aturan yang terpenuhi

### 🔙 Backward Chaining
Metode inferensi **mundur** ini dimulai dari suatu **hipotesis**:
1. Misalnya, ingin membuktikan apakah seseorang adalah penguin
2. Sistem mencari fakta-fakta pendukung
3. Jika semua prasyarat aturan terpenuhi, hipotesis dikonfirmasi

---

## 🚀 Cara Menjalankan di Google Colab

1. Buka [Google Colab](https://colab.research.google.com)
2. Klik menu **"File" > "Upload Notebook"** atau ikon 📁
3. Upload file `forward_chaining.ipynb` atau `backward_chaining.ipynb` dari repositori
4. Tambahkan *cell* di awal dan jalankan perintah:
   ```python
   !pip install experta
   !pip install --upgrade Frozendict
