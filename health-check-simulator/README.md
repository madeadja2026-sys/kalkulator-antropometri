# Health Check Simulator

Aplikasi edukasi offline-first untuk simulasi angka pemeriksaan kesehatan.

## Fitur
- Input tekanan darah, berat, tinggi, lingkar perut, LiLA, gula darah, asam urat, kolesterol total.
- Kalkulasi IMT dan rentang berat matematis dewasa.
- Interpretasi edukatif dengan pembatasan khusus anak dan kehamilan.
- Grafik ringkasan, riwayat lokal, ekspor/impor JSON, kuis kasus.
- PWA dan cache offline.

## Publikasi
Folder ini dapat dipublikasikan sebagai subpath GitHub Pages dari repository induk:
https://madeadja2026-sys.github.io/kalkulator-antropometri/health-check-simulator/

Aktifkan GitHub Pages pada repository induk dengan source branch `main` dan folder `/(root)`.

## Penyempurnaan versi awal\n- Pilihan umur dalam tahun atau bulan penuh, hingga 19 tahun untuk transisi acuan WHO.\n- Koreksi posisi ukur panjang/tinggi 0,7 cm untuk anak sesuai ketentuan antropometri.\n- Validasi rentang masukan dan peringatan tekanan darah sangat tinggi/kehamilan.\n- Riwayat simulasi tetap lokal dan dapat dicadangkan/pulihkan.\n\n## Catatan keselamatan
Versi awal belum menghitung z-score WHO, persentil tekanan darah pediatrik, atau kenaikan berat badan kehamilan. Nilai anak dan ibu hamil harus dievaluasi dengan standar khusus. Aplikasi ini bukan alat diagnosis atau pengganti tenaga kesehatan.
