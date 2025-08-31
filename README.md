# 🛒 Aplikasi Toko – Versi Browser

Aplikasi Toko sederhana yang bisa dijalankan langsung di browser (HP maupun laptop).  
Tidak butuh server, database, ataupun API. Semua data tersimpan di **LocalStorage** masing-masing perangkat.  

Cocok untuk usaha kecil seperti toko kelontong, penjual makanan ringan, atau sekadar belajar membuat aplikasi toko.

---

## ✨ Fitur Utama
- **Panel Admin (PIN Login)**
  - PIN default: `1234`
  - Bisa diubah hanya dengan memasukkan PIN lama
  - Logout / keluar dari admin
- **Produk**
  - Tambah, edit, hapus produk
  - Kolom opsional: kategori, deskripsi, gambar
  - Nama produk wajib, harga default `0` jika kosong
- **QRIS**
  - Upload gambar QRIS
  - Ditampilkan saat checkout (total belanja + gambar QRIS)
- **Checkout**
  - Kirim pesanan via WhatsApp
  - Lihat QRIS untuk pembayaran
- **Tampilan**
  - Mode Grid / List
  - Tema warna lembut & nyaman dilihat
- **Data**
  - Backup data ke file JSON
  - Import data dari JSON
  - Reset data total (untuk uji coba)

---

## 🚀 Cara Menggunakan
1. Buka aplikasi dari GitHub Pages (contoh: `https://username.github.io/toko`).
2. Untuk masuk ke panel admin:
   - Klik ikon ⚙️ (gear) di pojok kanan atas
   - Masukkan PIN (default `1234`)
3. Tambahkan produk sesuai kebutuhan.
4. Upload QRIS jika ingin pembayaran via QR.
5. Simpan data (otomatis tersimpan di LocalStorage).
6. Pembeli bisa:
   - Tambahkan produk ke keranjang
   - Checkout via WhatsApp **atau** lihat QRIS untuk bayar.

---

## 🔐 Catatan
- Semua data hanya tersimpan di perangkat pengguna (**LocalStorage**).
- Jika pengguna hapus cache browser → data toko ikut hilang.
- Gunakan fitur **Backup JSON** agar data tidak hilang.
- QRIS opsional, jika tidak diupload maka tombol "Lihat QRIS" tidak aktif.

---

## 📘 Tutorial Lengkap
Silakan baca file [Tutorial PDF](Tutorial_Aplikasi_Toko.pdf) untuk panduan lengkap cara penggunaan.
