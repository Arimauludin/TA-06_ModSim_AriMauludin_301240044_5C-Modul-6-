# TA-06 Pemodelan dan Simulasi — Simulasi Sistem Dinamik (Suhu Ruangan ber-AC)

Repositori ini berisi implementasi kode dan hasil visualisasi grafik untuk tugas mata kuliah **Pemodelan dan Simulasi (Modul 6)** mengenai simulasi sistem dinamik perubahan suhu ruangan ber-AC menggunakan metode integrasi numerik **Euler**.

## Identitas Mahasiswa
* **Nama:** Ari Mauludin
* **NIM:** 301240044
* **Kelas:** 5C — Teknik Informatika (Universitas Bale Bandung)

## Struktur File
* `TA6_Ari_Mauludin.ipynb` — Notebook utama berisi pemodelan matematis, kode simulasi lengkap, serta analisis hasil setiap skenario.
* `simulasi_suhu_ruangan.py` — Skrip Python mandiri untuk menjalankan simulasi suhu ruangan.
* `grafik_1_steady_state.png` — Hasil plot simulasi pada kondisi tunak (*steady-state*).
* `grafik_2_step.png` — Hasil plot respons sistem terhadap input fungsi tangga (*step*).
* `grafik_3_ramp.png` — Hasil plot respons sistem terhadap input fungsi tanjakan (*ramp*).
* `grafik_4_impuls.png` — Hasil plot respons sistem terhadap gangguan sesaat (*impulse*).
* `grafik_5_sinus.png` — Hasil plot respons sistem terhadap variasi suhu/beban sinusoidal.

## Parameter Model Simulasi
* **Kapasitas panas efektif ruangan ($C$):** `200000.0` J/K
* **Resistansi termal dinding/ventilasi ($R$):** `0.01` K/W
* **Daya pendinginan maksimum AC ($Q_{\max}$):** `1000.0` W
* **Suhu luar ruangan ($T_{\text{out}}$):** `32.0` °C
* **Beban panas internal ($Q_{\text{int}}$):** `300.0` W
* **Langkah waktu simulasi ($dt$):** `10.0` detik

## Prasyarat & Cara Menjalankan

1. **Instal pustaka yang dibutuhkan:**
   ```bash
   pip install numpy matplotlib jupyter