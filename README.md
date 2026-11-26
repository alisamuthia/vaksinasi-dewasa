# Vaksinasi Dewasa

Jadwal vaksinasi dewasa di Indonesia, sesuai rekomendasi Satgas Imunisasi Dewasa PAPDI, baik vaksinasi rutin maupun on-demand, beserta indikasi dan kontraindikasi, pilihan vaksin pengganti, dan jadwal catch-up vaccination.

Aplikasi web satu halaman untuk Poli Vaksinasi dewasa: jadwal rutin & sesuai indikasi, pengingat dosis berikut/booster, catch-up mendesak (umrah/haji, perjalanan, studi/kerja), kondisi khusus (imunosupresan, splenektomi), opsi vaksin pengganti, kontraindikasi, efek samping & tatalaksana, serta penilaian dan alur pelaporan KIPI.

## Cara pakai
- **Lokal:** unduh `index.html`, buka di Chrome/Edge.
- **GitHub Pages:** Settings → Pages → Source: *Deploy from a branch* → `main` / root. Aplikasi dapat dibuka di `https://<username>.github.io/vaksinasi-dewasa/`.

## Data pasien
- Data **tidak** tersimpan di repo ini maupun di server mana pun. Semua data tersimpan di `localStorage` browser yang membukanya (per perangkat, per browser).
- Lakukan **Ekspor JSON** rutin (tab Pasien). **Jangan pernah commit file ekspor JSON** ke repo ini — berisi data pribadi pasien (UU 27/2022 PDP). `.gitignore` sudah memblokir `*.json`.
- Untuk pemakaian multi-komputer dengan database bersama, diperlukan backend terpisah yang dikelola IT RS (lihat Permenkes 24/2022 tentang Rekam Medis Elektronik).

## Rujukan klinis
Jadwal Imunisasi Dewasa Satgas Imunisasi Dewasa PAPDI 2025; ACIP/CDC Adult Schedule 2025; WHO position papers; Health Requirements Umrah/Hajj 1447H (MoH KSA); Permenkes 12/2017 & pedoman KIPI Kemenkes; EULAR 2019 (vaksinasi AIIRD); ACR 2022 (vaksinasi RMD); IDSA 2013 (host imunokompromais).

Daftar produk disesuaikan dengan izin edar di Indonesia (diverifikasi klinik, Nov 2026). Gunakan *Kelola produk* di tab Katalog bila ketersediaan berubah.

## Disklaimer
Alat bantu keputusan klinis. Tidak menggantikan penilaian klinis, label produk, dan regulasi terbaru.

## Versi
Lihat [CHANGELOG.md](CHANGELOG.md).
