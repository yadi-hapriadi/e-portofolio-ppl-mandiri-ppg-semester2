# E-Portfolio PPL Mandiri Semester 2 — Yadi Hapriadi

Website statis untuk dijalankan di **localhost** atau dipublikasikan melalui **GitHub → Cloudflare Pages**. Seluruh foto profil, sampul artefak, dokumentasi kegiatan, dan PDF perangkat pembelajaran yang ditampilkan secara lokal berada di folder `assets/`.

## Menjalankan di localhost
1. Buka folder proyek ini di Visual Studio Code.
2. Buka `index.html`.
3. Jalankan melalui ekstensi **Live Server** (klik kanan → **Open with Live Server**).
4. Website akan terbuka pada alamat localhost, biasanya `http://127.0.0.1:5500`.

Alternatif: jika sudah memiliki server pengembangan lokal, arahkan root server ke folder ini. Situs juga dapat dibuka langsung dengan klik dua kali `index.html`, tetapi beberapa fitur preview lebih konsisten melalui localhost.

## Publikasi GitHub → Cloudflare Pages
1. Buat repository baru di GitHub.
2. Unggah seluruh isi folder proyek ke root repository sehingga `index.html` berada di root.
3. Di Cloudflare Pages pilih **Connect to Git** dan repository tersebut.
4. Framework preset: **None**; Build command: kosong; Build output directory: `.`.
5. Deploy. Jangan hanya mengunggah `index.html`; folder `assets/` wajib ikut.

## Struktur isi portofolio
- Beranda: foto profil asli Yadi Hapriadi, identitas PPG Informatika, dan ringkasan PPL Semester 2.
- Dokumen utama: tautan ke laporan PPL Semester 2 di Google Docs: https://docs.google.com/document/d/1RT-3-GqBexNJ8dyHcQocZVe_Bh5Qncd1qmfcTJwHZPY/edit?usp=drive_link.
- Observasi: survei karakteristik kelas X-C (43 respons) dan asesmen diagnostik (41 respons).
- Tiga grand materi: (1) Berpikir Komputasional yang mencakup Berpikir Komputasional, Searching, dan Sorting; (2) Pemanfaatan Internet yang mencakup media sosial, etika digital, dan proyek konten digital; (3) Aplikasi Perkantoran yang mencakup Microsoft Word.
- Pilihan praktik terbaik: Siklus 1 — Sorting (video praktik mengajar tersedia); Siklus 2 — PjBL Kreasi Konten Digital (modul yang disusun Yadi, LKPD empat pertemuan, dokumentasi, dan enam karya video murid).
- Siklus 4: dua praktik Microsoft Word (cover dan daftar isi otomatis) serta Live Challenge Google Meet sebagai refleksi/penguatan PJJ setelah camping pramuka.
- Dokumentasi lapangan: galeri pembelajaran X-C, piket perpustakaan, upacara, kepramukaan, penataan Labkom, pengawasan ujian praktik, bimbingan Guru Pamong/DPL, dan sosialisasi Proyek Kepemimpinan.
- Artefak: sampul preview lokal, PDF modul, tautan Canva, video Sorting, galeri Drive proyek murid, dan laporan PPL.
- Refleksi: umpan balik murid tentang pemerataan perhatian kepada murid yang duduk di bagian belakang dan kaitannya dengan pengembangan Ruang Informatika.

## Atribusi perangkat ajar
Perangkat ajar dikerjakan melalui pembagian tugas kelompok sehingga nama penyusun berbeda antar-modul. Nama yang tertulis pada sampul dipertahankan. Modul PjBL Media Sosial dan Kreasi Konten Digital adalah perangkat yang disusun oleh Yadi Hapriadi; modul lain ditampilkan sebagai perangkat kelompok sesuai atribusi pada sampul masing-masing.

## Bukti video dan proyek
- Video Sorting: rekaman praktik mengajar Yadi di kelas X-C, ditampilkan sebagai bukti praktik terbaik Siklus 1.
- Proyek konten digital: folder Drive berisi karya murid, ditampilkan sebagai produk pembelajaran PjBL; karya murid bukan rekaman praktik mengajar guru.
- Folder Drive harus diberi izin akses yang memungkinkan penilai membuka file.
- Laporan dibuka melalui Google Docs. Akses dokumen mengikuti pengaturan berbagi Google Docs pemilik dokumen.

## Animasi dan aksesibilitas
Situs memakai latar cahaya/aurora dan garis bergerak, grid perspektif, scroll reveal, progress bar, animasi hover artefak, tombol aksi bergaya visual, serta lightbox galeri foto dengan navigasi keyboard. Preferensi `prefers-reduced-motion` dihormati.

## Identitas visual browser
- Favicon khusus portofolio tersedia di `favicon.ico` dan `assets/brand/favicon.svg` beserta PNG fallback.
- Foto hero memakai `assets/images/yadi-hapriadi-hero.webp` dengan ruang kepala tambahan; avatar navigasi tetap memakai foto asli `yadi-hapriadi.webp`.
