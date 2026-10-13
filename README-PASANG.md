# Papua Field Notes v4 — GitHub Pages / iPhone

**Versi final tema modern | 58 profil distrik.** Paket ini siap dipasang di root repository GitHub Pages tanpa build / npm / server berbayar.

## Publikasikan
1. Ekstrak ZIP. Pilih **seluruh 9 file** di dalamnya, bukan ZIP saja.
2. Buka repository GitHub → **Add file → Upload files** dan taruh di root (`/`) repository.
3. Pastikan `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `favicon.svg`, `README-PASANG.md`, `TAMBAH_INFORMASI.md` terlihat di root.
4. Commit changes. Buka **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
5. Tunggu hingga tautan HTTPS Pages tersedia: `https://USERNAME.github.io/REPO/`.
6. Buka URL di **Safari iPhone** → Bagikan → **Add to Home Screen / Tambahkan ke Layar Utama**.

## User acceptance testing (UAT)
- Ganti tiga kabupaten (Mimika, Nabire, Asmat).
- Buka menu **Wilayah**, gunakan pencarian, lalu **ketuk distrik**. Pastikan profil yang terbuka berbeda untuk setiap distrik.
- Buka peta distrik (membutuhkan internet).
- Ketuk **Catat temuan** dan simpan informasi. Periksa catatan tersimpan setelah refresh.
- Periksa Beranda, Budaya, Jelajah, Panduan dan geser kiri/kanan.
- Instal melalui Safari dan periksa ikon serta tampilan layar penuh.

## Catatan data
- Profil mencakup 18 distrik Mimika, 15 distrik Nabire dan 25 distrik Asmat.
- Daftar kampung Mimika dan Nabire dari Wikipedia (status daftar Juli 2022): **cek pembaruan** sebelum digunakan untuk keperluan administratif.
- Daftar distrik Asmat mengikuti Pemkab Asmat. Pusat beberapa distrik tercantum secara selektif. Tidak ada angka penduduk distrik atau daftar fasilitas yang dibuat-buat.
- Mimika: penduduk dari Disdukcapil Semester I 2026. Nabire: estimasi tengah 2025 dari Wikipedia/BPS. Asmat: angka tingkat kabupaten dari Wikipedia 2024. Sumber utama tersedia dalam UI.
- Catatan dan checklist disimpan lokal di perangkat pengguna. Tidak tersinkron lintas ponsel/browser; ekspor catatan untuk backup.
- Service worker bekerja pada HTTPS / localhost dan mengutamakan cache file aplikasi. Tautan peta dan referensi eksternal tetap perlu internet.

## Update ke versi terbaru
Ganti file root dengan paket versi baru, commit, lalu muat ulang Safari (kadang perlu tutup-buka atau hapus data situs jika cache lama).

## Informasi proyek
Ruang modul PASTI-Papua dipersiapkan di halaman Panduan untuk fase selanjutnya. Tidak memuat data internal proyek dalam paket publik ini.
