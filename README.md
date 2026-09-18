# SH4NDY V34 - GitHub Pack 9 File
Auto 17:00 WIB BEI fetch to bursa/main/saham.xlsx

## Isi ZIP (9 file utama + struktur)
- index.html - V34 2 halaman placeholder (ganti dengan final HTML di /mnt/data/sh4ndy-v24-stable-hp-pwa-final_agentic_artifact_37_aad4c88844a1.html)
- master_1.txt 321 kode, master_2.txt 287 kode, master_3.txt 0 kode - total 608 actual real BEI tickers
- fetch-bei.py - batch 30 jeda 15 menit col 10 HARGA penutupan
- .github/workflows/auto.yml - cron 0 10 * * 1-5 = 17:00 WIB
- manifest.json + sw.js + icon-192.png + icon-512.png - PWA S hijau #22C55E on black #0A0A0A
- bursa/main/.gitkeep - folder output saham.xlsx

## Cara pakai
1. Extract ZIP, push ke repo sh4ndy/bursa
2. Ganti index.html dengan V34 final HTML lengkap (2 halaman)
3. Aktifkan Actions - auto.yml akan jalan 17:00 WIB tiap Senin-Jumat
4. Raw URL: https://raw.githubusercontent.com/sh4ndy/bursa/main/saham.xlsx

Hitam doff #0A0A0A #161616 rounded 18px signal glow hijau #22C55E merah #EF4444 blank 0 data.length actual
JSZip CDN: https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js
FileSaver CDN: https://cdnjs.cloudflare.com/ajax/libs/FileSaver.js/2.0.5/FileSaver.min.js (runtime CDN ok)
