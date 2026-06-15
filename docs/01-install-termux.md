# 📱 Install Termux

Selamat datang!

Repository ini dibuat untuk membantu siapa saja belajar programming hanya dengan HP Android.

---

## 🤔 Kenapa Termux?

Termux adalah terminal Linux untuk Android yang memungkinkan kita:

- 🐍 Belajar Python
- 🌐 Menggunakan Git & GitHub
- ⚡ Menjalankan NodeJS
- 📝 Menggunakan Neovim / LazyVim
- 🚀 Membangun project langsung dari HP

---

## ⚠️ Jangan Download dari Play Store

Versi Play Store sudah tidak diperbarui.

Gunakan salah satu sumber berikut:

- F-Droid
- GitHub Release Resmi Termux

---

## 🔄 Update Package

Jalankan:

```bash
pkg update && pkg upgrade -y
```

---

## 📂 Aktifkan Storage

```bash
termux-setup-storage
```

Pilih **Allow** saat muncul permintaan izin.

---

## ✅ Verifikasi

Cek apakah storage berhasil dibuat:

```bash
ls ~/storage
```

Output biasanya berisi:

```text
downloads
shared
dcim
movies
music
```

---

## 📚 Selanjutnya

➡️ Lanjut ke:

```text
docs/02-basic-packages.md
```
