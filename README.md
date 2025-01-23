# Kickshoes

## Deskripsi Proyek
**Kickshoes** adalah sebuah aplikasi penjualan sepatu, socks, dan merchandise dari **Kicksolution**. Proyek ini adalah sebuah *self-project* yang bertujuan untuk mengasah kemampuan dalam pengembangan web dengan menggunakan **Tailwind CSS** untuk tampilan antarmuka dan **PHP Laravel Filament** untuk pengelolaan admin.

**Status:** Proyek ini masih dalam tahap pengembangan (*on-going*), sehingga fitur-fitur mungkin belum sepenuhnya selesai atau stabil.

## Fitur Utama
- **Katalog Produk**: Menampilkan daftar produk sepatu, socks, dan merchandise yang terorganisir dengan baik.
- **Keranjang Belanja**: Memungkinkan pengguna untuk menambahkan produk ke keranjang dan melanjutkan ke proses pembayaran.
- **Manajemen Admin**: Dibangun menggunakan **Laravel Filament** untuk mengelola data produk, kategori, dan transaksi.
- **Desain Responsif**: Tampilan yang optimal untuk desktop dan perangkat seluler.

## Teknologi yang Digunakan
- **Frontend**: Tailwind CSS
- **Backend**: PHP Laravel
- **Admin Panel**: Laravel Filament
- **Database**: MySQL

## Instalasi
Ikuti langkah-langkah berikut untuk menjalankan proyek ini secara lokal:

### Prasyarat
Pastikan Anda sudah menginstal:
- **PHP** (>= 8.1)
- **Composer** (Dependency Manager untuk PHP)
- **Node.js** dan **npm** (untuk pengelolaan frontend)
- **MySQL** (Database Management System)

### Langkah Instalasi
1. **Clone Repository**
   ```bash
   git clone https://github.com/imambahy/kickshoes.git
   cd kickshoes
   ```

2. **Install Dependencies**
   Jalankan perintah berikut untuk menginstal semua dependency backend dan frontend:
   ```bash
   composer install
   npm install
   ```

3. **Konfigurasi Environment**
   Salin file `.env.example` menjadi `.env`:
   ```bash
   cp .env.example .env
   ```
   Sesuaikan konfigurasi database di file `.env` sesuai dengan pengaturan lokal Anda:
   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=kickshoes
   DB_USERNAME=root
   DB_PASSWORD=yourpassword
   ```

4. **Migrasi Database**
   Jalankan perintah berikut untuk membuat tabel di database:
   ```bash
   php artisan migrate
   ```

5. **Jalankan Aplikasi**
   Gunakan perintah berikut untuk menjalankan server backend dan frontend:
   - Backend:
     ```bash
     php artisan serve
     ```
   - Frontend:
     ```bash
     npm run dev
     ```

6. **Akses Aplikasi**
   Buka browser Anda dan akses aplikasi di:
   ```
   http://localhost:8000
   ```
   
## Lisensi
Proyek ini dilisensikan di bawah [MIT License](https://opensource.org/licenses/MIT).

## Kontribusi
Proyek ini adalah *self-project*, tetapi kontribusi, ide, atau saran dari komunitas selalu diterima. Jangan ragu untuk membuat *pull request* atau melaporkan masalah melalui [issues](https://github.com/imambahy/kickshoes/issues).

## Kontak
Jika Anda memiliki pertanyaan lebih lanjut tentang proyek ini, silakan hubungi saya:
- **Email**: imambahyp@gmail.com
- **GitHub**: [imambahy](https://github.com/imambahy)
