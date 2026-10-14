# Kalkulator Antropometri Puskesmas

PWA statis untuk BBI, IMT, LPT/ BSA, diagram rentang IMT dewasa dan hitung matematis dosis berbasis LPT. Perhitungan dilakukan di browser; identitas pasien tidak dikumpulkan.

## Fitur
- Responsif untuk HP, tablet dan laptop.
- BBI Devine hanya untuk dewasa dengan tinggi minimal 152,4 cm.
- IMT dan kategori skrining umum dewasa; untuk usia di bawah 20 tahun menampilkan peringatan.
- LPT dengan rumus Mosteller.
- Hasil matematis LPT × dosis mg/m², dengan batas maksimum opsional.
- Diagram IMT, cetak, PWA dan cache offline setelah aplikasi dibuka online.
- Tidak ada database atau penyimpanan rekam medis.

## Publikasi
GitHub Pages harus diaktifkan di Settings → Pages. Pilih Deploy from a branch, branch main, folder /(root), lalu Save. Situs biasanya tersedia di https://madeadja2026-sys.github.io/kalkulator-antropometri/.

## Keselamatan
Alat bantu hitung, bukan sistem pendukung keputusan klinis tervalidasi. Dosis berbasis LPT hanya untuk obat/protokol yang secara eksplisit memakai mg/m². Batas maksimum yang diinput hanya diterapkan secara matematis dan tidak diverifikasi. Sebelum digunakan pada pelayanan pasien, validasi oleh dokter/apoteker dan ikuti pedoman, formularium serta informasi produk yang berlaku.