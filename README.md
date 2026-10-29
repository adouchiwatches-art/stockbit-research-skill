# Stockbit Research Skill

Skill bahasa Indonesia untuk belajar menganalisis data Stockbit dan emiten BEI. Berisi alur fundamental, pemeriksaan data, peer comparison, valuasi berskenario, serta latihan. Tidak memerlukan API key; belum memiliki integrasi langsung Stockbit.

## Pemakaian

Salin folder `skills/stockbit-research` ke folder skill Codex yang digunakan lingkunganmu. File instruksi utamanya adalah `SKILL.md`. Paket ini belum otomatis memasang skill pada perangkat.

Contoh prompt:

> Pakai $stockbit-research. Bantu aku belajar membaca Keystats BBCA dari tabel yang kuberikan. Jelaskan tiga rasio terpenting, cek periode, lalu beri satu latihan.

> Bandingkan dua emiten konsumer dari data ini. Bedakan fakta dan asumsi, periksa arus kas, dan tunjukkan data yang belum cukup.

> Uji tesis “P/E rendah berarti murah” untuk emiten batubara ini menggunakan laba normalisasi.

Mulai dengan screenshot/tabel Keystats dan Financials, tanggal harga, serta periode laporan. Analisis dapat diperdalam menggunakan laporan resmi. Contoh latihan dalam paket memakai data fiktif.

Lihat [SOURCES.md](SOURCES.md) untuk perbandingan acuan dan keputusan adaptasi. Paket siap diunggah sebagai repository `stockbit-research-skill`.
