# Papua Field Notes v6 — Modern Comparison Edition

PWA untuk GitHub Pages: **5 menu** (Beranda, Wilayah, Banding, Budaya, Jelajah). Bagian **Banding** menyediakan pilihan 2–3 kabupaten, 7 indikator kuantitatif, 18 aspek kualitatif, filter kelompok, tampilan ringkas/detail, interpretasi, dan tautan sumber.

## Memperbarui repository

1. Ekstrak ZIP ini. Unggah **seluruh isi folder** ke root repository `elakukua/Papua_Field_Notes` (bukan ZIP).
2. Timpa `index.html`, `sw.js`, `manifest.webmanifest`; **tambahkan `comparison-data.js`** (wajib). Ikon yang sudah ada boleh tetap.
3. Commit ke branch `main`, cek Actions > pages build and deployment sukses.
4. Uji `https://elakukua.github.io/Papua_Field_Notes/` di Safari. Bila versi lama muncul, muat ulang halaman agar service worker v6 mengaktifkan cache baru.

## Memperbarui konten dari GitHub

- `comparison-data.js`: tabel 18 aspek, pembahasan dua/tiga wilayah, IPM laki-laki/perempuan 2025, daftar sumber. **Perbarui fakta dengan sumber dan tahun rujukan.**
- `index.html`: UI, daftar 58 distrik, data dan profil kabupaten.
- `sw.js`: jika ada perubahan versi besar dan iPhone menyajikan konten lama, naikkan versi cache.

## Catatan metodologis

- Jumlah penduduk tidak memiliki tahun yang sama (Mimika 2026, Nabire 2025, Asmat 2024). Jangan memakai perbedaan angka ini untuk menyimpulkan tren pertumbuhan.
- IPM menurut jenis kelamin berasal dari tabel resmi BPS tahun 2025 dan **bukan IPM keseluruhan**.
- Analisis kondisi akses dan layanan adalah sintesis kualitatif, bukan peringkat mutu, survei biaya, atau informasi keamanan real-time.
- Tidak ada fitur edit data, panduan, maupun formulir tambahan di aplikasi; perbarui konten melalui GitHub saja.
