# Landing-Page-dengan-form-pembayaran-ke-Whatsapp
Landing Page Dengan Integrasi Form Pembayaran ke Whatsaap

# 💬 Landing Page – Pembayaran via WhatsApp

Sebuah landing page sederhana yang memungkinkan pengguna melakukan pemesanan dan mengirim data langsung ke WhatsApp dengan pesan terformat otomatis. Cocok untuk bisnis kecil, UMKM, atau personal brand yang ingin menyediakan metode pemesanan cepat tanpa integrasi payment gateway kompleks.

## 🧩 Fitur

- Formulir pemesanan (nama, produk, jumlah)
- Kirim otomatis ke WhatsApp dengan isi pesan terstruktur
- Mobile-friendly & ringan
- Mudah dikustomisasi

---

## 🚀 Cara Menggunakan

1. **Clone repositori ini**
   ```bash
   git clone https://github.com/USERNAME/landingpage-wa-payment.git
   cd landingpage-wa-payment
Edit nomor WhatsApp tujuan Buka file assets/js/wa-form.js, ganti bagian berikut:

js
Copy
Edit
const phone = '6281234567890'; // ganti dengan nomor WA kamu
Buka index.html di browser
Isi form, klik tombol “Bayar via WhatsApp”, dan kamu akan diarahkan ke WhatsApp Web/Apps.

## 🖼️ Demo
Klik gambar di bawah untuk melihat tampilan:


Atau coba langsung (jika aktif di GitHub Pages):
👉 https://USERNAME.github.io/landingpage-wa-payment/

## 📁 Struktur Folder
landingpage-wa-payment/
├── index.html               # Halaman utama
├── assets/
│   ├── css/style.css        # Styling halaman
│   └── js/wa-form.js        # Logika pengiriman WhatsApp
├── README.md                # Dokumentasi proyek
└── .gitignore               # File/folder yang diabaikan Git
## ✏️ Kustomisasi
Tambahkan field form sesuai kebutuhan: email, alamat, catatan, dsb.

Tambahkan validasi form dengan JavaScript jika diperlukan.

Ubah desain dengan mengedit assets/css/style.css.

Ganti gaya bahasa pesan WhatsApp agar sesuai dengan brand kamu.

## 📌 Catatan Teknis
Format nomor WhatsApp harus internasional tanpa tanda “+” (misal: 6281234567890)

Menggunakan metode Click to Chat WhatsApp

Tidak menyimpan data pengguna (client-side only)

## 📝 Lisensi
Proyek ini menggunakan lisensi MIT. Bebas digunakan dan dimodifikasi untuk keperluan pribadi maupun komersial.

© 2025 [RifkiMuazin]


---
