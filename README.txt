# PWA Bendahara Pemuda Al-Jihad

PWA ini memakai logo Pemuda Al-Jihad yang kamu kirim sebagai icon aplikasi.

## Isi
- `index.html` — halaman PWA yang membuka aplikasi Google Apps Script.
- `manifest.webmanifest` — konfigurasi instalasi PWA.
- `sw.js` — service worker untuk app shell.
- `icons/` — icon 192px, 512px, dan Apple Touch Icon.

## URL aplikasi
https://script.google.com/macros/s/AKfycbxvo8-4ZBnl3crEgv20AfhsyLH-sM3Q07WXNS5IoR2FaZGXld63w_wWXRe4S84qeZIb/exec

## Cara pasang di GitHub Pages
1. Buat repository baru di GitHub.
2. Upload **isi folder PWA ini** (bukan folder pembungkusnya).
3. Masuk `Settings` → `Pages`.
4. Pilih `Deploy from a branch`.
5. Pilih branch `main` dan folder `/ (root)`.
6. Simpan dan buka alamat GitHub Pages yang diberikan.
7. Di Chrome Android/desktop, pilih **Install app / Instal aplikasi**.

## Catatan
PWA ini adalah wrapper yang menampilkan aplikasi Google Apps Script di dalam iframe. Jadi fungsi aplikasi Bendahara tetap berasal dari script yang sekarang.
