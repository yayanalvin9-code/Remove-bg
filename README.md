# 🪄 BG Remover HD

Aplikasi web penghapus latar belakang otomatis. Hasil **resolusi asli (HD)**, PNG transparan, diproses **di browser** (privat, tanpa server).

## Fitur
- Hapus background otomatis dengan AI (model ISNet, kualitas tertinggi)
- Output sama dengan resolusi foto asli, tanpa diperkecil
- Ganti latar: transparan, putih, hitam, warna kustom
- Download PNG HD
- Gratis & tanpa backend → bisa di-host di GitHub Pages

## Jalankan di GitHub Pages
1. Upload semua file ke repo GitHub
2. **Settings → Pages → Branch: main → / (root) → Save**
3. Buka `https://USERNAME.github.io/NAMA-REPO/`

## Jalankan lokal
```bash
python -m http.server 8000
```
Lalu buka http://localhost:8000

## Teknologi
[@imgly/background-removal](https://github.com/imgly/background-removal-js) (ONNX Runtime Web)

## Lisensi
Kode: MIT. Perhatikan lisensi library/model @imgly untuk penggunaan komersial.
