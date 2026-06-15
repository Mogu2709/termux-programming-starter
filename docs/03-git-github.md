# 🌐 Git & GitHub Dasar

Git digunakan untuk melacak perubahan project.

GitHub digunakan untuk menyimpan project secara online.

---

## 👤 Konfigurasi Git

Ganti dengan data milikmu:

```bash
git config --global user.name "Nama Kamu"
git config --global user.email "email@example.com"
```

Cek konfigurasi:

```bash
git config --list
```

---

## 📁 Membuat Repository Baru

```bash
mkdir my-project
cd my-project
```

Inisialisasi Git:

```bash
git init
```

---

## ➕ Menambahkan File

Satu file:

```bash
git add README.md
```

Semua file:

```bash
git add .
```

---

## 💾 Commit

```bash
git commit -m "Initial commit"
```

---

## 🔗 Hubungkan ke GitHub

```bash
git remote add origin git@github.com:USERNAME/REPOSITORY.git
```

Verifikasi:

```bash
git remote -v
```

---

## 🚀 Push ke GitHub

```bash
git branch -M main
git push -u origin main
```

---

## 🔍 Cek Status

```bash
git status
```

Perintah ini adalah salah satu yang paling sering digunakan saat bekerja dengan Git.

---

## 📚 Selanjutnya

➡️ Lanjut ke:

```text
docs/04-github-ssh.md
```
