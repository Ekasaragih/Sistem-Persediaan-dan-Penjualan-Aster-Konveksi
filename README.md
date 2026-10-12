# Sistem-Persediaan-dan-Penjualan-Aster-Konveksi
# Stockita

Stockita adalah aplikasi manajemen stok, penjualan, dan laporan usaha yang dirancang untuk bisnis konveksi dengan gaya yang lebih premium, clean, dan nyaman dilihat setiap hari. Aplikasi ini membantu pemilik usaha Aster Konveksi mengelola produk, mengawasi stok, mencatat transaksi, serta menilai performa pemasaran dan keuangan dalam satu dashboard yang lebih estetik.

Dengan tampilan boutique dan minimalis, Stockita tidak hanya memudahkan proses operasional, tetapi juga memberi kesan lebih profesional untuk bisnis fashion dan konveksi modern. Aplikasi ini cocok digunakan untuk usaha konveksi, garment, atau bisnis custom yang membutuhkan pengelolaan stok dan data penjualan dengan lebih rapi.

## Live App

Link demo [(https://stockita-aster-konveksi.vercel.app)](https://ekasaragih.github.io/Sistem-Persediaan-dan-Penjualan-Aster-Konveksi/)

## Fitur Utama

- Manajemen data produk dan kategori
- Monitoring stok serta batas minimum stok
- Pencatatan transaksi penjualan
- Pembayaran awal dan status pembayaran
- Ringkasan omzet, laba, dan piutang
- Laporan bulanan dan performa usaha
- Antarmuka boutique, feminine, dan minimalis

## Teknologi yang Digunakan

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js
- Database: Supabase
- Mode lokal: browser storage untuk demo dan pengujian cepat

## Cara Menjalankan Secara Lokal

1. Masuk ke folder project
2. Jalankan backend dengan:

```bash
node backend/app.js
```

3. Buka browser dan akses:

```text
http://localhost:3000
```

## Persiapan Database Supabase

Jika ingin menggunakan database Supabase, jalankan isi file `backend/database.sql` di SQL Editor Supabase, lalu atur environment berikut:

```bash
SUPABASE_URL=your_supabase_url
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key
```

> Jika variabel belum diatur, aplikasi tetap bisa berjalan dalam mode browser lokal dan menggunakan data demo.

## Struktur Project

- `backend/` — berisi `app.js` dan `database.sql`
- `frontend/` — berisi `index.html`, `style.css`, dan `script.js`
- `README.md` — dokumentasi project

## Status Database

Saat menjalankan SQL di Supabase, hasil yang dikembalikan akan menampilkan:

```sql
SELECT 'success' AS status;
```

Jadi, eksekusi database yang berhasil akan menghasilkan status `success`.
