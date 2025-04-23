# 🔧 Fuzzy AC Fan Control & Flu Diagnosis

Proyek ini berisi dua sistem cerdas:

1. **Fuzzy Logic** untuk mengatur kecepatan kipas AC berdasarkan suhu dan kelembaban.
2. **Certainty Factor (CF)** untuk mendiagnosis flu dari gejala pengguna.

## 🌀 Fuzzy Logic (Logika Fuzzy)
- Menggunakan suhu (15–40°C) dan kelembaban (20–100%) sebagai input.
- Output: kecepatan kipas (0–100%).
- Logika fuzzy memungkinkan nilai berada di lebih dari satu kategori (contoh: suhu bisa "nyaman" dan "panas").

## 🤒 Certainty Factor (CF)
- Menghitung kemungkinan flu berdasarkan gejala seperti demam, batuk, pilek, dll.
- Output: nilai keyakinan (0–1).
- CF dihitung dari kombinasi nilai user dan bobot pakar.

## ▶️ Cara Menjalankan
```bash
pip install numpy scikit-fuzzy matplotlib
python main.py
