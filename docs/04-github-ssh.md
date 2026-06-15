# 🔐 GitHub SSH Setup

SSH memungkinkan kamu menggunakan GitHub tanpa perlu login setiap kali melakukan push.

---

## ✨ Keuntungan SSH

- ✅ Tidak perlu memasukkan password berulang kali
- ✅ Lebih aman
- ✅ Lebih nyaman digunakan

---

## 🔑 Generate SSH Key

Jalankan:

```bash
ssh-keygen -t ed25519 -C "email@example.com"
```

Contoh:

```bash
ssh-keygen -t ed25519 -C "moguoffical.id@gmail.com"
```

Tekan Enter untuk menggunakan lokasi default.

---

## 📋 Lihat Public Key

```bash
cat ~/.ssh/id_ed25519.pub
```

Contoh output:

```text
ssh-ed25519 AAAAXXXXXXXXXXXXX email@example.com
```

> Salin seluruh output tersebut.

---

## 🌐 Tambahkan ke GitHub

1. Buka GitHub
2. Masuk ke Settings
3. Pilih SSH and GPG Keys
4. Klik New SSH Key
5. Paste public key
6. Klik Add SSH Key

---

## 🧪 Test Koneksi

```bash
ssh -T git@github.com
```

Jika berhasil:

```text
Hi USERNAME! You've successfully authenticated, but GitHub does not provide shell access.
```

---

## ⚠️ Jangan Pernah Membagikan Private Key

❌ Jangan bagikan:

```bash
~/.ssh/id_ed25519
```

✅ Yang aman dibagikan:

```bash
~/.ssh/id_ed25519.pub
```

---

## 🛠 Troubleshooting

<details>
<summary>Software caused connection abort</summary>

Jika muncul error:

```text
ssh_dispatch_run_fatal:
Connection to xx.xx.xx.xx port 22:
Software caused connection abort
```

Kemungkinan port 22 diblokir oleh ISP.

Buat file:

```bash
nvim ~/.ssh/config
```

Isi:

```text
Host github.com
    Hostname ssh.github.com
    Port 443
    User git
```

Lalu test kembali:

```bash
ssh -T git@github.com
```

</details>

---

## ✅ Checklist

- [ ] SSH Key dibuat
- [ ] Public Key ditambahkan ke GitHub
- [ ] SSH berhasil terhubung
- [ ] Push GitHub berhasil

---

## 🎉 Selesai

GitHub SSH berhasil dikonfigurasi.
