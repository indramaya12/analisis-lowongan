📊 Analisis Lowongan Kerja untuk Menentukan Keterampilan yang Dibutuhkan
Proyek ini bertujuan untuk menganalisis data lowongan kerja dan mengidentifikasi keterampilan (skills) yang paling sering diminta dalam industri data.

📁 Struktur Folder
- `postings.csv` - Dataset asli dari lowongan kerja
- `analisis_lowongan.py` - Script Python untuk preprocessing, analisis, dan visualisasi
- `hasil_cleaning.csv` - Data setelah melalui proses cleaning & normalisasi
- `frekuensi_skill.png` - Visualisasi 10 skill paling dicari
- `wordcloud_lowongan.png` - Word Cloud deskripsi lowongan kerja
- `slide_9_interpretasi_ai.pptx` - Slide PowerPoint berisi hasil ringkasan AI

🔍 Tahapan Analisis
1. **Menyiapkan Dataset**
   - Sumber: Kaggle (Job postings dataset)
2. **Cleaning & Preprocessing**
   - Menggabungkan `job_summary` + `job_skills`
   - Normalisasi teks: huruf kecil, hapus tanda baca, dan hapus stopwords
3. **Analisis & Visualisasi**
   - Barplot frekuensi skill seperti Python, SQL, Excel
   - Word Cloud berdasarkan deskripsi pekerjaan
4. **AI Interpretasi**
   - Menggunakan Granite (Replicate API) untuk membuat ringkasan keterampilan

🧠 Insight
- Skill paling umum: **Python**, **SQL**, dan **Excel**
- Perusahaan mengutamakan keterampilan komunikasi, analisis data, dan pemahaman alat visualisasi

📌 Author
Indramaya – Capstone Project 2025
