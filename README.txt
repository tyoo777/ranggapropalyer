PANDUAN MEMBUKA WEB PORTOFOLIO RANGGA PRASETIO
==============================================

1. Ekstrak (unzip) file ZIP ke sebuah folder, misalnya "rangga-web".
   Pastikan file index.html berada langsung di dalam folder itu,
   bukan di dalam folder lain yang bertumpuk.

2. Buka VS Code, pilih menu File > Open Folder, lalu pilih folder "rangga-web".

3. Pasang extension "Live Server" (Ritwick Dey) jika belum ada.

4. Klik kanan index.html di panel Explorer, lalu pilih
   "Open with Live Server". Browser akan terbuka di http://127.0.0.1:5501/index.html
   (port 5501 sudah diatur di folder .vscode/settings.json).
   Alamat harus diakhiri index.html atau kosong, jangan diakhiri garis miring "/".

5. Semua halaman bisa dibuka lewat menu atau lewat tombol Ctrl+K (cari halaman).

Struktur folder:
  index.html ........... beranda
  tentang.html ......... halaman tentang (poster profil)
  belajar.html ......... daftar modul 1-6 (penjelasan dan video)
  modul-1.html s/d modul-6.html ... materi tiap modul
  portofolio.html, jurnal.html, kalkulator.html, simulator.html,
  glosarium.html, kuis.html, risiko.html, kontak.html
  assets/ ............... CSS, JavaScript, gambar, font, dan kartu kontak (.vcf)

Catatan:
- Gambar, grafik, dan font sudah disimpan di dalam folder assets, jadi tidak perlu koneksi internet untuk tampilannya.
- Tombol video membuka YouTube, sehingga butuh koneksi internet.
- Jika Live Server tidak dipakai, index.html juga bisa dibuka langsung dengan
  klik dua kali di browser, tetapi fitur tertentu lebih lancar lewat Live Server.
