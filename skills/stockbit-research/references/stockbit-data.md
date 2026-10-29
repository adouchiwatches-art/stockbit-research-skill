# Peta data Stockbit dan pemeriksaan input

Nama menu dan akses paket bisa berubah; periksa tampilan yang benar-benar tersedia. Jangan menjanjikan ekspor jika belum terlihat.

| Kebutuhan | Tempat mulai | Pemeriksaan |
|---|---|---|
| Rasio dan snapshot | Keystats | Harga bertanggal, TTM/FY/annualized, definisi rasio |
| Riwayat laporan | Financials | Kuartalan/YTD/tahunan, satuan, restatement, konsolidasi |
| Peer | Comparison | Model bisnis dan periode selaras |
| Kandidat saham | Screener bila tersedia | Nama field dan operator yang ada; alasan setiap filter |
| Validasi material | Laporan emiten, investor relations, keterbukaan BEI | Halaman, periode, publikasi, catatan laporan |

Buat ledger: metrik | nilai | satuan | periode | tanggal publikasi/harga | sumber | status verifikasi. Harga historis harus dipasangkan dengan informasi yang telah tersedia pada tanggal tersebut untuk simulasi investasi.

Bedakan titik ribuan dan koma desimal; B/M/T atau miliar/juta/triliun harus dikonfirmasi. Rasio persen tidak sama dengan pecahan. Jangan menjumlahkan angka YTD antarkuartal. Kuartal tunggal Q2 = H1 − Q1; Q4 = FY − 9M, hanya jika basis sama. TTM = FY terakhir + YTD kini − YTD tahun lalu, dengan cakupan periode dan kebijakan akuntansi sebanding.

Jika angka Stockbit berbeda dengan laporan emiten, selidiki periode, pembulatan, penyesuaian, dan basis sebelum memilih angka. Laporkan selisih material. Laporan resmi mengutamakan pembuktian historis; harga pasar tetap memerlukan sumber bertanggal tersendiri.

Jangan memasukkan screenshot portofolio, identitas akun, atau data berlisensi pengguna ke repository publik. Repository skill berisi metode dan contoh sintetis saja.

Rujukan fitur resmi: https://snips.stockbit.com/edukasi/fitur-analisa-fundamental dan https://stockbit.com/info/pro-tools/keystats .
