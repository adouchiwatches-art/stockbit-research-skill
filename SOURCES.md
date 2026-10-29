# Acuan dan keputusan desain

Ditinjau 29 Oktober 2026. Penilaian kecocokan, bukan sertifikasi profesional atau peringkat seluruh GitHub.

| Kandidat | Yang berguna | Batas untuk kebutuhan ini |
|---|---|---|
| [alirezarezvani/claude-skills — stock-analysis](https://github.com/alirezarezvani/claude-skills/blob/main/finance/skills/stock-analysis/SKILL.md) | Pembandingan sektoral, kualitas laba, pembuktian dokumen, skenario | Berorientasi India/global; perlu pemetaan BEI dan Stockbit |
| [OctagonAI/skills](https://github.com/OctagonAI/skills) | Rangkaian riset finansial terstruktur dan sumber data | Bergantung ekosistem Octagon MCP; terlalu berat untuk awal belajar Stockbit |
| [yennanliu/InvestSkill](https://github.com/yennanliu/InvestSkill) | Pemisahan alur fundamental, teknikal, valuasi | Berorientasi pasar AS; sumber dan konteks berbeda |

Acuan utama yang dipilih: stock-analysis dari alirezarezvani, berdasarkan kesesuaian metode dan kedalaman pemeriksaan, bukan jumlah bintang. Repository menampilkan lisensi MIT saat ditinjau. Skill lokal ditulis ulang secara mandiri dan tidak menyalin kode atau teks substansial dari kandidat. Jika kelak menyalin materi mereka, sertakan lisensi dan atribusi upstream yang berlaku.

Adaptasi: bahasa Indonesia, pembacaan data Stockbit, periode YTD/TTM, sektor BEI, latihan singkat, dan batas akses nyata. Isi upstream bukan bukti bahwa metode menghasilkan keuntungan.

Dokumentasi fitur resmi Stockbit:
- https://snips.stockbit.com/edukasi/fitur-analisa-fundamental
- https://stockbit.com/info/pro-tools/keystats

Validasi paket: pemeriksaan format skill dan kelengkapan referensi. Belum diuji terhadap sesi Stockbit langsung atau keputusan investasi nyata.
