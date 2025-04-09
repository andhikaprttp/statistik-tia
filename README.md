# Analisis Statistik Deskriptif

## Diketahui:
Distribusi frekuensi nilai mahasiswa:

| Nilai   | f   |
|---------|-----|
| 10–19   | 3   |
| 20–29   | 8   |
| 30–39   | 16  |
| 40–49   | 25  |
| 50–59   | 23  |
| 60–69   | 14  |
| 70–79   | 7   |
| 80–89   | 4   |
| **Jumlah** | **100** |

---

## 1. Rentang Semi Kuartil (Interquartile Range / IQR / Jangkauan Antar Kuartil)

### Langkah-langkah:
- **Q1** adalah kuartil ke-1 (25%), berarti posisi ke-25 dalam data.
- **Q3** adalah kuartil ke-3 (75%), berarti posisi ke-75 dalam data.

Kita perlu kolom frekuensi kumulatif:

| Kelas   | f   | FK  |
|---------|-----|-----|
| 10–19   | 3   | 3   |
| 20–29   | 8   | 11  |
| 30–39   | 16  | 27  |
| 40–49   | 25  | 52  |
| 50–59   | 23  | 75  |
| 60–69   | 14  | 89  |
| 70–79   | 7   | 96  |
| 80–89   | 4   | 100 |

**Mencari Q1 (Posisi ke-25)**:
Masuk di kelas 30–39 (karena FK sebelumnya 11, lalu 27)

**Mencari Q3 (Posisi ke-75)**:
Masuk di kelas 50–59 (karena FK sebelumnya 52, lalu 75)

Gunakan rumus kuartil:
Q_k = L + (((k * n) / 4) - F) / f) * i
Dimana:
- L = batas bawah kelas kuartil
- F = frekuensi kumulatif sebelum kelas
- f = frekuensi kelas kuartil
- i = panjang kelas (dari soal: 10)

### Hitung:
- **Q1**:
  - L = 29.5, F = 11, f = 16, i = 10
  - Q1 = 29.5 + ((25 - 11) / 16) * 10 = 29.5 + 8.75 = 38.25

- **Q3**:
  - L = 49.5, F = 52, f = 23, i = 10
  - Q3 = 49.5 + ((75 - 52) / 23) * 10 = 49.5 + 10 = 59.5

### **Rentang Semi Kuartil (RSK):**
RSK = (Q3 - Q1) / 2 = (59.5 - 38.25) / 2 = 21.25 / 2 = 10.625

**Tafsiran:**
Rentang semi kuartil sebesar 10.625 menunjukkan bahwa setengah data berada dalam selang ±10.625 dari nilai tengah antar kuartil (Q2).

---

## 2. Varians dan Simpangan Baku (Standar Deviasi)

Langkah:
Gunakan rumus:

x̄ = (∑ f * x) / n   dan   s² = (∑ f * (x - x̄)²) / n

Gunakan titik tengah (x) untuk setiap kelas:

| Nilai   | f   | x    | fx     | x²     | fx²      |
|---------|-----|------|--------|--------|----------|
| 10–19   | 3   | 14.5 | 43.5   | 210.25 | 630.75   |
| 20–29   | 8   | 24.5 | 196    | 600.25 | 4802     |
| 30–39   | 16  | 34.5 | 552    | 1190.25| 19044    |
| 40–49   | 25  | 44.5 | 1112.5 | 1980.25| 49506.25 |
| 50–59   | 23  | 54.5 | 1253.5 | 2970.25| 68315.75 |
| 60–69   | 14  | 64.5 | 903    | 4160.25| 58243.5  |
| 70–79   | 7   | 74.5 | 521.5  | 5550.25| 38851.75 |
| 80–89   | 4   | 84.5 | 338    | 7140.25| 28561    |

Jumlah:
- ∑ f = 100
- ∑ fx = 4920.5
- ∑ fx² = 267900.375

### Rata-rata:
x̄ = 4920.5 / 100 = 49.205

### Varians:
s² = (∑ fx²) / n - x̄² = 267900.375 / 100 - (49.205)²
s² = 2679.00375 - 2421.132 = 257.87

### Simpangan Baku:
s = √(s²) ≈ 16.06

---

## Jawaban Akhir:
1. **Rentang Semi Kuartil** = **10.625**
   **Tafsiran**: Data tersebar ±10.625 dari median kuartil tengah.

2. **Varians** = **257.87**, **Standar Deviasi** = **16.06**
