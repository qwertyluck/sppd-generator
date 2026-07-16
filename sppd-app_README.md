# Aplikasi Generator SPPD Kejaksaan Digital

Aplikasi berbasis web (Single Page Application) yang berjalan sepenuhnya di sisi klien (Client-Side) menggunakan **HTML5, CSS3 (Tailwind CSS), dan JavaScript (Vanilla JS)**. Aplikasi ini dirancang untuk memudahkan staf/operator Kejaksaan dalam menginput data, menghasilkan (*generate*), dan mengunduh Surat Perjalanan Dinas (SPD) secara instan dalam format cetak/PDF standar A4 yang presisi, sesuai dengan format Peraturan Menteri Keuangan Nomor 113/PMK.05/2012 dan templat resmi Kejaksaan Tinggi Maluku.

## Fitur Utama
1. **Formulir Input Dinamis**: Form isian terstruktur dari Poin 1-10 sesuai dokumen aslinya.
2. **Manifes Pengikut Dinamis**: Kemampuan menambah, mengedit, dan menghapus daftar pengikut (Poin 8) secara interaktif.
3. **Modul Preview Real-Time**: Tampilan dokumen langsung (*Live Preview*) yang membagi halaman menjadi Bagian Muka (Halaman 1) dan Lembar Visum/Pengesahan Belakang (Halaman 2).
4. **Fungsi Cetak & Unduh PDF**: Terintegrasi dengan sistem cetak browser native yang dikombinasikan dengan CSS Paged Media `@media print` untuk menghasilkan dokumen PDF A4 yang presisi dan bersih tanpa UI eksternal.
5. **Zero Backend**: Dapat di-host secara gratis dan instan di **GitHub Pages** karena tidak memerlukan server/database aktif.

## Panduan Hosting di GitHub Pages
1. Buat repositori baru di GitHub dengan nama `sppd-generator`.
2. Unggah file `index.html` ke repositori tersebut.
3. Buka menu **Settings** > **Pages** di repositori GitHub Anda.
4. Pada bagian **Build and deployment**, pilih *Source*: `Deploy from a branch`, lalu pilih branch `main` atau `master` dan folder `/ (root)`. Klik **Save**.
5. Aplikasi Anda akan live dalam beberapa menit di alamat: `https://<username_github>.github.io/sppd-generator/`.
