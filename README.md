# Buku Nota — Android APK

Proyek Android WebView untuk membungkus `Buku_Nota_v14.html` menjadi APK.

## Build otomatis di GitHub

1. Buat repository baru di GitHub.
2. Upload seluruh isi folder proyek ini ke repository.
3. Masuk ke tab **Actions**.
4. Jalankan workflow **Build APK Buku Nota**.
5. Setelah selesai, buka hasil workflow dan unduh artifact **BukuNota-debug-apk**.
6. Di dalam ZIP artifact terdapat `app-debug.apk`.

Workflow juga berjalan otomatis setiap kali push ke branch `main` atau `master`.

## Fitur native

- HTML berjalan offline dari Android WebView.
- `localStorage` tetap digunakan untuk menyimpan data nota/pengaturan.
- Input file gambar untuk logo dan tanda tangan didukung melalui pemilih file Android.
- Tombol `window.print()` dari HTML dialihkan ke Android Print Framework sehingga **Cetak / Simpan PDF** dapat digunakan dari aplikasi.
