# 💼 Program Perhitungan Gaji Karyawan (Java)

Program ini dibuat menggunakan bahasa **Java** dan berfungsi untuk menghitung **total penghasilan karyawan** berdasarkan **golongan** dan **jam lembur**.

---

## 📝 Fitur Program

- Memasukkan golongan karyawan (A, B, atau C)
- Memasukkan jumlah jam lembur
- Menghitung gaji pokok berdasarkan golongan
- Menghitung tunjangan lembur berdasarkan jam lembur
- Menampilkan total penghasilan

---

## 🧮 Rumus Perhitungan

- **Gaji Pokok** berdasarkan golongan:
  - A = Rp 5.000.000
  - B = Rp 6.500.000
  - C = Rp 9.500.000

- **Persentase Lembur**:
  - 1 jam = 30% dari gaji pokok
  - 2 jam = 32%
  - 3 jam = 34%
  - 4 jam = 36%
  - ≥5 jam = 38%

- **Total Penghasilan** = Gaji Pokok + Gaji Lembur

---

## 🚀 Cara Menjalankan Program

1. Buka terminal / command prompt
2. Compile program:
   ```bash
   javac latihan.java
   ```
3. Jalankan program:
   ```bash
   java latihan
   ```

---

## 🖥️ Contoh Output

```
====================================
PROGRAM JAVA
PERHITUNGAN GAJI KARYAWAN
====================================
Masukkan Golongan (A/B/C):
B
Masukkan Jam Lembur:
3
Total Penghasilan Rp.7540000.0
====================================
```

---

## ❗ Validasi

- Jika input golongan salah → muncul peringatan.
- Jika jam lembur < 0 → muncul peringatan lembur tidak valid.

---

## 📌 Catatan

- Program ini menggunakan `Scanner` untuk input dari user.
- Data seperti gaji pokok dan persentase lembur disimpan dalam array.

---

## 👨‍💻 Kontributor

Nana
```

---