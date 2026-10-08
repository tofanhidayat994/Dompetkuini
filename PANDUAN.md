# Dompetku - paket unggah GitHub (versi rata, tanpa folder)

Semua file ada di SATU tingkat. Seret semuanya sekaligus ke repo.

File: index.html, manifest.json, sw.js, icon-192.png, icon-512.png, maskable-512.png,
apple-touch-icon.png, _config.yml, cek.html, PANDUAN.md

1. GitHub -> repo Anda -> Add file -> Upload files -> seret SEMUA file -> Commit changes.
   (Jika file lama bernama sama sudah ada, GitHub akan menimpanya.)
2. Settings -> Pages -> Deploy from a branch -> main / (root).
3. Buka <alamat-aplikasi>/cek.html di Chrome. Semua baris harus berawalan centang.
4. Baru setelah semua centang, analisis alamat <alamat-aplikasi>/ di pwabuilder.com.
5. Setelah APK jadi, buat .well-known/assetlinks.json di repo <username>.github.io
   (Add file -> Create new file, nama: .well-known/assetlinks.json, isi dari zip PWABuilder).
