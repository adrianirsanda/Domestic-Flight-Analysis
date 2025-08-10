# Domestic Flight Analysis

Analisis ini bertujuan untuk memahami berbagai faktor yang memengaruhi harga tiket penerbangan domestik di India berdasarkan dataset yang tersedia.  
Proyek ini mencakup eksplorasi data, analisis visual, dan rekomendasi berbasis temuan.

## Dataset
Dataset berisi informasi mengenai penerbangan domestik, dengan fitur utama sebagai berikut:

- `airline` : Maskapai penerbangan
- `flight` : Kode penerbangan
- `source_city` : Kota asal
- `departure_time` : Waktu keberangkatan
- `stops` : Jumlah transit
- `arrival_time` : Waktu ketibaan
- `destination_city` : Kota tujuan
- `class` : Kelas penerbangan
- `duration` : Durasi penerbangan (jam)
- `days_left` : Jumlah hari sebelum keberangkatan
- `price` : Harga tiket (dalam INR)

## Problem Statement

- Menganalisis hubungan antara **harga tiket (`price`)** dan **jumlah hari sebelum keberangkatan (`days_left`)** untuk melihat tren perubahan harga.  
- Mengevaluasi pengaruh **durasi penerbangan (`duration`)** terhadap harga tiket.  
- Mengidentifikasi pola harga berdasarkan **waktu keberangkatan (`departure_time`)**.  
- Mengidentifikasi pola harga berdasarkan **waktu ketibaan (`arrival_time`)**.  
- Menilai perbedaan harga tiket berdasarkan **jumlah transit (`stops`)**.  
- Menemukan rute penerbangan paling sibuk dan hubungannya dengan harga tiket.

## Tools & Library
- **Python** : Bahasa pemrograman utama
- **Pandas** : Manipulasi data
- **Matplotlib / Seaborn** : Visualisasi data
- **Jupyter Notebook** : Dokumentasi dan eksekusi analisis
