# 🍦 Es Lilin Aa Sio

Website sederhana untuk usaha **Es Lilin Aa Sio**.

Website ini dibuat menggunakan:

- HTML
- CSS
- JavaScript

Tidak membutuhkan framework tambahan.

---

# 📁 Struktur Folder

Susun file seperti berikut:

es-lilin-aa-sio/
│
├── index.html
├── style.css
├── script.js
├── README.md
│
└── images/
    ├── coklat.png
    ├── strawberry.png
    ├── alpukat.png
    └── mangga.png

---

# 🍦 Produk

Website memiliki 4 varian Es Lilin:

1. Coklat
2. Strawberry
3. Alpukat
4. Mangga

Harga default:

Rp3.000 / buah

Harga dapat diubah melalui file:

index.html

Contoh:

onclick="addToCart('Coklat', 3000)"

Angka `3000` merupakan harga produk.

---

# 🛒 Fitur Website

Website Es Lilin Aa Sio memiliki fitur:

- Tampilan responsif
- Navbar
- Hero section
- Katalog produk
- Gambar produk
- Pencarian produk
- Keranjang belanja
- Tambah produk
- Kurangi jumlah produk
- Hapus produk
- Perhitungan total otomatis
- Checkout
- Data pemesan
- Nomor WhatsApp pelanggan
- Pilihan ambil sendiri
- Pilihan pengantaran
- Ongkos kirim
- Catatan pesanan
- Pembayaran tunai
- Transfer bank
- QRIS
- Pemesanan melalui WhatsApp
- Notifikasi ketika produk ditambahkan

---

# 🖼️ Cara Menambahkan Gambar

Masukkan gambar ke folder:

images/

Kemudian gunakan nama:

coklat.png
strawberry.png
alpukat.png
mangga.png

Contoh pada HTML:

<img src="images/coklat.png" alt="Es Lilin Coklat">

Pastikan nama file sesuai.

---

# 📱 Mengubah Nomor WhatsApp

Buka file:

script.js

Cari:

const whatsappNumber = "6281234567890";

Kemudian ganti dengan nomor WhatsApp penjual.

Contoh nomor:

081234567890

Ubah menjadi:

6281234567890

Jangan menggunakan:

+6281234567890

Gunakan:

6281234567890

---

# 💰 Mengubah Ongkir

Buka:

script.js

Cari:

const deliveryFee = 5000;

Contoh jika ongkir ingin menjadi Rp10.000:

const deliveryFee = 10000;

---

# 🏦 Mengubah Rekening

Buka file:

script.js

Cari bagian:

Bank BCA

No. Rekening:
1234567890

a.n. Es Lilin Aa Sio

Kemudian ganti dengan data rekening usaha yang sebenarnya.

---

# 💳 Pembayaran

Website menyediakan pilihan:

1. Tunai / COD
2. Transfer Bank
3. QRIS

Perlu diperhatikan bahwa sistem pembayaran pada website ini
belum terhubung langsung dengan payment gateway.

Artinya pembayaran belum dapat diverifikasi secara otomatis.

Untuk pembayaran otomatis dapat dikembangkan menggunakan
payment gateway dan backend.

---

# 🚚 Pengantaran

Terdapat dua metode:

## Ambil Sendiri

Ongkir:

Rp0

## Diantar

Ongkir default:

Rp5.000

Nilainya dapat diubah melalui:

script.js

---

# ▶️ Menjalankan Website

Cara paling sederhana:

1. Buka folder project.
2. Klik dua kali `index.html`.
3. Website akan terbuka di browser.

Untuk development disarankan menggunakan Visual Studio Code
dan extension Live Server.

Kemudian:

1. Buka project menggunakan VS Code.
2. Klik kanan `index.html`.
3. Pilih `Open with Live Server`.

---

# ⚠️ Catatan

Pastikan struktur file benar.

File:

index.html
style.css
script.js

Harus berada pada folder utama yang sama.

Sedangkan gambar harus berada pada:

images/

Jika gambar tidak muncul, periksa kembali nama dan ekstensi file.

Contoh:

images/coklat.png

berbeda dengan:

images/Coklat.png

pada beberapa server.

---

# 👨‍💻 Project

Nama:

Es Lilin Aa Sio

Jenis:

Website katalog dan pemesanan Es Lilin

Teknologi:

HTML + CSS + JavaScript

© 2026 Es Lilin Aa Sio