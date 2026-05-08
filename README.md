# Text Summarization Project

Project ini berisi implementasi peringkasan teks artikel berita secara ekstraktif menggunakan pendekatan TextRank dan pemrosesan teks berbasis Python.

## Fitur
- Input teks artikel melalui aplikasi Streamlit
- Preprocessing teks
- Tokenisasi kalimat dan kata
- Stopword removal dan stemming bahasa Indonesia
- Perhitungan kemiripan antar kalimat menggunakan cosine similarity
- Pembentukan graf kalimat
- Pemeringkatan kalimat menggunakan TextRank
- Pemilihan kalimat penting sebagai hasil ringkasan

## Teknologi
- Python
- Streamlit
- NLTK
- Sastrawi
- NetworkX
- scikit-learn
- Matplotlib

## Status Project
Repository ini berisi implementasi utama untuk proses peringkasan teks. Versi antarmuka berbasis Streamlit sedang dikembangkan dan akan ditambahkan pada update berikutnya.

## Tujuan Project
Project ini dikembangkan sebagai bagian dari pembelajaran dan penelitian terkait peringkasan teks otomatis secara ekstraktif.

## Cara Menjalankan
1. Clone repository ini
2. Install library yang dibutuhkan:
   ```bash
   pip install -r requirements.txt
3. Jalankan file utama
   ```bash
   python main.py
