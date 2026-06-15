Install Termux

Kenapa Termux?

Termux memungkinkan kita menjalankan lingkungan Linux langsung di Android tanpa root.

Dengan Termux kita bisa:

- Belajar programming
- Menggunakan Git dan GitHub
- Menjalankan Python
- Menjalankan NodeJS
- Menggunakan Neovim atau LazyVim

Jangan Install dari Play Store

Versi Play Store sudah lama dan tidak lagi diperbarui.

Gunakan versi terbaru dari F-Droid atau halaman resmi Termux.

Update Package

Setelah membuka Termux untuk pertama kali:

pkg update && pkg upgrade -y

Berikan Izin Storage

termux-setup-storage

Pilih Allow ketika muncul permintaan izin.

Verifikasi

Pastikan folder storage berhasil dibuat:

ls ~/storage

Jika muncul beberapa folder seperti downloads, shared, dcim, maka setup berhasil.
