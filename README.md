# 📊 DataVista V2
### Media Pembelajaran Interaktif Statistika Kelas VIII SMP
**Project-Based Learning · Universitas Pendidikan Indonesia**

---

## 🌐 Demo Live
👉 **[Buka DataVista V2](https://[username].github.io/datavista-v2/)**
> *(Ganti `[username]` dengan username GitHub Anda)*

---

## 📖 Tentang Media

**DataVista** adalah media pembelajaran statistika berbasis web interaktif yang dirancang untuk siswa kelas VIII SMP menggunakan model **Project-Based Learning (PjBL)**. Media ini dikembangkan sebagai bagian dari penelitian disertasi di **Program S3 Pendidikan Matematika, Universitas Pendidikan Indonesia**.

| Keterangan | Detail |
|---|---|
| 📚 Mata Pelajaran | Matematika — Statistika |
| 🎓 Jenjang | SMP Kelas VIII / Fase D |
| 🏫 Model Pembelajaran | Project-Based Learning (PjBL) |
| 🧑‍💻 Versi | DataVista V2 |
| 🌍 Bahasa | Bahasa Indonesia |
| 📱 Platform | Web (Mobile-Friendly) |

---

## ✨ Fitur Utama

### 🏠 Beranda
- Identitas kelompok **cukup diisi sekali** — tampil otomatis di semua pertemuan
- Tujuan pembelajaran terstruktur dengan kata kerja operasional Bloom
- **Data tersimpan otomatis** di browser (localStorage)

### 📁 Proyek (5 Pertemuan)
| Pertemuan | Topik | Fitur Khusus |
|---|---|---|
| P1 | Pertanyaan Mendasar | Observasi fenomena, prediksi awal |
| P2 | Perencanaan & Penjadwalan | Rancang instrumen, bagi tugas |
| P3 | Pengumpulan Data | Tabel 40 baris (No · Kode · Durasi · Tujuan · Waktu) |
| P4 | Pengolahan & Penyajian | Tabel turus otomatis · Hitung statistik · Grafik interaktif |
| P5 | Presentasi & Evaluasi | Kesimpulan, rekomendasi, refleksi akhir |

### 📚 Materi
- **Mean** — Rumus, langkah, dan contoh kontekstual
- **Median** — Data ganjil dan genap
- **Modus** — Satu dan lebih dari satu modus
- **Jangkauan** — Ukuran penyebaran sederhana
- **Penyajian Data** — Batang, garis, lingkaran, tabel frekuensi
- **Kuartil** *(Opsional/Pengayaan)* — Q1, Q2, Q3, Simpangan Kuartil

### 🧮 Kalkulator Statistik Interaktif
- Siswa **mengisi langkah sendiri** — hasil hanya muncul setelah jawaban benar
- Feedback langsung: ✓ hijau (benar) / merah (coba lagi)
- Mencakup: **Mean · Median · Modus · Jangkauan · Kuartil**
- Tabel distribusi frekuensi dengan **turus otomatis**

### 💾 Penyimpanan Otomatis
- Seluruh data tersimpan di `localStorage` browser
- Notifikasi toast "✓ Data tersimpan otomatis" setiap ada perubahan
- Data tidak hilang saat berpindah halaman

---

## 🎯 Capaian & Tujuan Pembelajaran

**Capaian Pembelajaran (Kurikulum Merdeka Fase D):**
> *Peserta didik dapat menentukan dan menafsirkan rerata (mean), median, modus, dan jangkauan (range) dari data untuk menyelesaikan masalah — termasuk membandingkan data, memprediksi, dan membuat keputusan.*

**Tujuan Pembelajaran:**
1. **Membaca** data dalam bentuk tabel dan grafik dengan benar
2. **Menghitung** mean, median, modus, jangkauan, dan kuartil secara sistematis
3. **Menyajikan** data ke dalam diagram yang sesuai
4. **Menganalisis** data nyata penggunaan HP menggunakan ukuran pemusatan & penyebaran
5. **Menyimpulkan** hasil analisis untuk membuat keputusan sederhana

---

## 🚀 Cara Menggunakan

### Untuk Guru
1. Bagikan link GitHub Pages ke siswa
2. Minta siswa buka di browser HP atau laptop
3. Siswa isi identitas kelompok di menu **Beranda**
4. Mulai dari **Proyek → Pertemuan 1**
5. Setiap akhir pertemuan, siswa klik **Unduh PDF**

### Untuk Siswa
1. Buka link yang diberikan guru di browser
2. Isi identitas kelompok (cukup sekali!)
3. Pilih pertemuan sesuai jadwal
4. Kerjakan aktivitas satu per satu
5. Gunakan menu **Kalkulator** untuk membantu pengolahan data
6. Unduh PDF di akhir pertemuan

---

## 🛠️ Teknologi

| Teknologi | Kegunaan |
|---|---|
| HTML5 + CSS3 | Struktur dan tampilan |
| Vanilla JavaScript | Logika interaktif |
| Chart.js 4.4.1 | Grafik interaktif |
| Google Fonts (Sora + Plus Jakarta Sans) | Tipografi |
| localStorage API | Penyimpanan data otomatis |

> **Tidak memerlukan server, database, atau instalasi apapun.**
> Cukup satu file HTML — buka langsung di browser.

---

## 📂 Struktur File

```
datavista-v2/
│
├── index.html          ← File utama (semua dalam satu file)
└── README.md           ← Dokumentasi ini
```

---

## 📋 Persyaratan Sistem

| Perangkat | Minimum |
|---|---|
| Browser | Chrome 80+ / Firefox 75+ / Safari 13+ / Edge 80+ |
| Koneksi | Diperlukan untuk Google Fonts & Chart.js (pertama kali) |
| Layar | Optimal di 360px – 520px (mobile) |

> Logo UPI dan DataVista sudah di-embed — tampil meski offline.

---

## 👨‍🎓 Pengembang

| | |
|---|---|
| **Nama** | Wahyu Setiawan |
| **NIM** | 2211397 |
| **Program Studi** | S3 Pendidikan Matematika |
| **Institusi** | Universitas Pendidikan Indonesia |
| **Pembimbing 1** | Prof. Dr. H. Nanang Priatna, M.Pd |
| **Pembimbing 2** | Prof. Drs. Suhendra, M.Ed., Ph.D |
| **Pembimbing 3** | Dr. Bambang Avip Priatna, M.Si |

---

## 📝 Catatan Pengembangan

- **Kuartil** ditempatkan sebagai materi **opsional/pengayaan** karena tidak termasuk dalam materi wajib kelas VIII Kurikulum Merdeka (lebih tepat untuk kelas IX atau SMA)
- Tujuan pembelajaran disusun menggunakan **kata kerja operasional Bloom** yang terukur
- Beban kognitif per pertemuan dibatasi **3–4 aktivitas + 2 pertanyaan refleksi**
- Identitas kelompok hanya diisi sekali untuk menghindari pengisian berulang

---

## 📄 Lisensi

Media ini dikembangkan untuk keperluan **penelitian pendidikan** di Universitas Pendidikan Indonesia.
Penggunaan untuk keperluan pembelajaran diperbolehkan dengan menyertakan atribusi kepada pengembang.

---

<div align="center">
  <strong>DataVista V2</strong> · Statistika Kelas VIII · UPI · 2025
</div>

