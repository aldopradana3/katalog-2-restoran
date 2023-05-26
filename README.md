# Submission: Katalog Restoran + PWA
### 1. Halaman Utama (Daftar Restoran)
Syarat:
- Menampilkan daftar restoran yang datanya bersumber dari API https://restaurant-api.dicoding.dev/. Silakan lihat dokumentasinya pada halaman tersebut.
- Wajib menampilkan nama, gambar dan minimal salah satu diantara kota, rating, dan atau deskripsi pada restoran.
- Terdapat tautan/CTA yang mengarah ke detail restoran pada tiap itemnya.
- Hero elemen tetap dipertahankan.
### 2. Halaman Detail Restoran
Syarat:
- Menampilkan detail dari restoran yang dipilih dari halaman utama (daftar restoran) atau halaman favorit restoran.
- Pada halaman detail restoran harus terdapat:
  - Nama restoran
  - Gambar
  - Alamat
  - Kota 
  - Deskripsi
  - Menu Makanan
  - Menu Minuman
  - Customer Reviews
- Terdapat tombol favorite untuk memasukkan atau menghapus restoran favorit dari database (gunakan IndexedDB).
### 3. Halaman Daftar Restoran Favorit
Syarat:
- Halaman Daftar Restoran dapat diakses melalui menu navigasi favorit.
- Menampilkan restoran yang difavoritkan oleh pengguna (data diambil dari indexedDB).
- Wajib menampilkan nama, gambar dan minimal salah satu diantara kota, rating, dan atau deskripsi pada restoran.
- Terdapat tautan/CTA yang mengarah ke detail restoran pada tiap itemnya.
### 4. Native Capability
Syarat:
- Aplikasi dapat diakses dalam keadaan offline tanpa ada aset yang gagal dimuat, termasuk data yang didapatkan dari API. Anda bebas menggunakan strategi caching apapun, bahkan menggunakan workbox.
- Aplikasi harus menampilkan icon Add to Home Screen.
- Aplikasi memiliki custom icon yang ditampilkan pada home screen dan splash screen.
### 5. Code Quality
Syarat:
- Menggunakan ESLint sebagai linter ketika menuliskan kode JavaScript. Harap lampirkan berkas konfigurasi ESLint ya.
- Menerapkan salah satu style guide baik itu Google JavaScript Code Style, AirBnB JavaScript Code Style, atau StandardJS Code Style.
- Periksa kembali sebelum mengirimkan submission, apakah project yang Anda kirimkan sesuai dengan kriteria yang ditetapkan atau tidak, ditandai dengan tidak adanya satupun error ketika menjalankan eslint.
### 6. Pertahankan syarat yang ada pada submission sebelumnya
Seperti responsibilitas tampilan, aksesibilitas pada website, appbar, footer dan sebagainya.

Install :
```
npm install
```
Start Development :
```
npm run start-dev
```
Build :
```
npm run build
```
