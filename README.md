# 🔥 Aplikasi Interaktif Sains Tahun 5 - Haba

Aplikasi pembelajaran interaktif untuk murid Tahun 5 yang membahas topik **Haba (Heat)** dalam mata pelajaran Sains.

## ✨ Ciri-Ciri Utama

### 📚 Kandungan Pendidikan
- 20 soalan kuiz berformat **pilihan berganda** dan **benar/salah**
- Topik meliputi: pemindahan haba, konduktor/penebat haba, pengukuran suhu, dan sumber haba
- Imej dan deskripsi untuk membantu pemahaman

### 🎮 Kuiz Interaktif
- Soalan dimuatkan secara berurutan
- Maklum balas serta-merta (✅ betul / ❌ salah)
- Bilah kemajuan untuk menunjukkan penyelesaian kuiz
- Paparan skor akhir

### 🏆 Gamifikasi
- **Lencana/Pingat** berdasarkan prestasi:
  - 🥉 Lencana Gangsa (5+ jawapan betul)
  - 🥈 Lencana Perak (10+ jawapan betul)
  - 🥇 Lencana Emas (15+ jawapan betul)
- **Papan Pendahulu** untuk menjejaki skor murid
- Skor disimpan secara lokal menggunakan browser localStorage

### 📊 Penjejakan Prestasi
- Paparan skor masa nyata
- Bilah kemajuan visual
- Papan kedudukan dengan 10 skor teratas

### 💻 Reka Bentuk Responsif
- Mesra pelbagai peranti (mudah alih, tablet, desktop)
- Antara muka yang bersih dan menarik dengan warna kehangatan
- Susun atur berasaskan kad

## 🚀 Cara Menggunakan

1. Buka aplikasi di: `https://cikgudinskkt1-creator.github.io/sains-tahun5-haba/`
2. Baca setiap soalan dengan teliti
3. Klik pada pilihan jawapan anda
4. Lihat maklum balas serta-merta
5. Klik "Soalan Seterusnya" untuk meneruskan
6. Selepas menamatkan kuiz, masukkan nama anda dan klik "Simpan Skor"
7. Lihat skor anda dalam papan pendahulu

## 📝 Soalan-Soalan

Aplikasi ini mengandungi soalan tentang:
- Definisi haba dan tenaga
- Pemindahan haba (konduksi, konveksi, radiasi)
- Konduktor dan penebat haba
- Pengukuran suhu
- Keselamatan berkaitan haba
- Aplikasi praktikal haba dalam kehidupan seharian

## 🛠️ Teknologi

- **HTML5** untuk struktur
- **CSS3** untuk reka bentuk responsif
- **JavaScript vanilla** untuk interaktivitas
- **LocalStorage API** untuk penyimpanan skor

## 💾 Penyimpanan Data

Semua skor murid disimpan secara lokal di peranti mereka (tidak dihantar ke pelayan). Ini bermakna:
- ✅ Data murid bersifat peribadi
- ✅ Tidak memerlukan rangkaian internet setelah halaman dimuatkan
- ⚠️ Data akan hilang jika cache browser dikosongkan

## 🎨 Penyesuaian

Untuk menambah atau mengubah soalan, edit bahagian `quizData` dalam `index.html`:

```javascript
const quizData = [
  {
    q: "Soalan anda di sini?",
    type: "mcq", // atau "tf" untuk benar/salah
    options: ["Pilihan 1", "Pilihan 2", "Pilihan 3", "Pilihan 4"],
    answer: "Jawapan yang betul"
  },
  // Tambah soalan lagi di sini
];
```

## 📱 Keserasian

- ✅ Chrome, Firefox, Safari, Edge
- ✅ Desktop, tablet, mudah alih
- ✅ Tidak memerlukan plugin tambahan

## 🔄 Pembaruan Masa Depan

Ciri-ciri yang mungkin ditambah:
- Pengukuran masa untuk setiap soalan
- Tahap kesukaran yang berbeza
- Laporan analitik untuk guru
- Papan pemain berbilang pengguna (dengan backend)
- Lebih banyak soalan dan topik sains

## 📄 Lesen

Projek ini terbuka untuk kegunaan pendidikan dan pengubahsuaian.

---

**Dibuat untuk tujuan pendidikan dengan ❤️**
