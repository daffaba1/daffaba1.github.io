PANDUAN WEBSITE PORTOFOLIO GIS — GITHUB PAGES
============================================

ISI FOLDER
- index.html  : Satu file website lengkap (HTML, CSS, JavaScript)
- README.txt  : Panduan singkat

CARA PUBLISH PALING MUDAH
1. Buka https://github.com dan buat akun jika belum punya.
2. Klik tanda + > New repository.
3. Nama repository: USERNAME.github.io (ganti USERNAME dengan username GitHub Anda).
4. Set repository Public lalu Create repository.
5. Klik Add file > Upload files, pilih file index.html ini.
6. Klik Commit changes.
7. Buka Settings > Pages.
8. Di bagian Build and deployment, pilih Source: Deploy from a branch.
9. Pilih branch main, folder /(root), lalu Save.
10. Setelah proses deployment selesai, buka https://USERNAME.github.io.

CARA MENGGANTI INFORMASI
- Buka index.html di editor seperti Notepad atau VS Code.
- Cari teks [NAMA ANDA], [EMAIL ANDA], dan [USERNAME ANDA].
- Cari komentar GANTI: untuk menemukan bagian yang harus dipersonalisasi.
- Empat gambar thumbnail saat ini berupa ilustrasi SVG, bukan peta hasil proyek nyata.
- Untuk hasil yang lebih profesional, ganti bagian <div class="thumb"> pada kartu
  proyek dengan <img src="assets/namafile.jpg" alt="..."> setelah file gambar
  diunggah ke folder assets/.
- Ubah deskripsi proyek agar sesuai pekerjaan yang boleh dipublikasikan.
- Setelah perubahan, unggah ulang index.html dan lakukan Commit changes.

CATATAN
- GitHub Pages menyajikan file website statis; tidak menjalankan backend Python.
- Bisa menambahkan WebGIS (misalnya Leaflet atau MapLibre) pada tahap berikutnya.
- Jangan mengunggah data klien, koordinat sensitif, atau file proyek yang bersifat rahasia.
