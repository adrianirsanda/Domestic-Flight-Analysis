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

##  Analisis & Insight

### A. Price vs Days Left
- **Insight**: Analisis tren harga berdasarkan jarak waktu pemesanan dengan keberangkatan.  
- **Rekomendasi**: Menentukan waktu terbaik untuk memesan tiket.

### B. Price vs Duration
- **Insight**: Dampak durasi penerbangan terhadap harga tiket.  
- **Rekomendasi**: Strategi pemilihan rute berdasarkan durasi dan harga.

### C. Price vs Departure Time
- **Insight**: Perbedaan harga berdasarkan jam keberangkatan.  
- **Rekomendasi**: Menyesuaikan jadwal keberangkatan untuk efisiensi biaya.

### D. Price vs Arrival Time
- **Insight**: Pola harga berdasarkan jam ketibaan.  
- **Rekomendasi**: Memilih waktu ketibaan yang sesuai dengan anggaran.

### E. Price vs Stops
- **Insight**: Dampak jumlah transit terhadap harga tiket.  
- **Rekomendasi**: Pertimbangan antara harga dan kenyamanan perjalanan.

### F. Busiest Route
- **Insight**: Rute penerbangan dengan frekuensi tertinggi.  
- **Rekomendasi**: Peluang promosi atau penyesuaian strategi harga pada rute padat.

## Tools & Library
- **Python** : Bahasa pemrograman utama
- **Pandas** : Manipulasi data
- **Matplotlib / Seaborn** : Visualisasi data
- **Jupyter Notebook** : Dokumentasi dan eksekusi analisis
