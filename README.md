# BookShelfAPI
Membangun API Bookshelf dengan JavaScript dan Node.js

Selamat datang ke repositori API Bookshelf! Proyek ini dibangun menggunakan JavaScript dan Node.js untuk memungkinkan Anda mengelola koleksi buku Anda.

## Instalasi

**Prasyarat**: Pastikan Anda memiliki Node.js dan npm (Node Package Manager) terinstal di sistem Anda. Anda dapat memeriksanya dengan menjalankan perintah node -v dan npm -v di terminal. Jika belum terinstal unduh dan instal dari situs web resmi Node.js (https://nodejs.org/en).

## Penggunaan

1. Menjalankan API: Setelah instalasi dependensi selesai, Anda dapat menjalankan API dengan perintah berikut:
```cmd
npm start
```
Ini akan memulai server Node.js dan API akan berjalan pada port tertentu (biasanya port 3000).

2. Endpoints API

Dapatkan semua buku: ``GET /books``

Dapatkan buku berdasarkan ID: ``GET /books/:id``

Tambahkan buku baru: ``POST /books`` (Body request berupa JSON berisi informasi buku)

Perbarui buku: ``PUT /books/:id`` (Body request berupa JSON berisi informasi buku yang ingin diperbarui)

Hapus buku: ``DELETE /books/:id``

Catatan: Ganti :id dengan ID buku yang sebenarnya.
