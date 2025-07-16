# ✈️ Airline Delay Analysis using AI Support

## 📌 Project Overview
Analisis ini bertujuan untuk mengeksplorasi penyebab keterlambatan penerbangan di Amerika Serikat berdasarkan data historis. Proyek ini menggunakan pendekatan analitik berbasis AI untuk menghasilkan insight dan rekomendasi strategis.

## 📂 Raw Dataset Link
Dataset yang digunakan adalah **[Airline_Delay_Cause.csv])**  
([link-ke-google-drive-atau-repo](https://www.kaggle.com/datasets/jawadkhattak/us-flight-delay-from-january-2017-july-2022)

## 📊 Insight & Findings
- **Late aircraft delay** dan **carrier delay** merupakan dua penyebab utama keterlambatan penerbangan.
- Terdapat korelasi tinggi (0.88) antara keterlambatan maskapai dan pesawat sebelumnya.
- Tren tahunan menunjukkan peningkatan keterlambatan yang fluktuatif setelah 2020.
- Maskapai dengan carrier delay tertinggi adalah OO, WN, dan AA.
- Faktor cuaca dan keamanan memiliki pengaruh relatif kecil terhadap total delay.

## 🤖 AI Support Explanation
Proyek ini menggunakan **IBM Granite LLM** melalui integrasi di Google Colab untuk:
- Menghasilkan insight otomatis dari visualisasi
- Menyusun rekomendasi strategis berdasarkan pola data
- Mendukung analisis naratif dan summarization

AI digunakan untuk **mempercepat proses interpretasi data** dan membantu menyusun laporan berbasis temuan yang akurat.  
Model yang digunakan: `ibm-granite/granite-3-3b-8b-instruct` via `langchain`.
