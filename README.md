# Termux Programming Starter

Panduan belajar programming menggunakan HP Android dengan Termux.

Repository ini berisi dokumentasi setup, troubleshooting, dan workflow yang digunakan untuk belajar dan membuat project langsung dari Android.

---

## Contents

- Install Termux
- Basic Packages
- Git & GitHub
- GitHub SSH
- LazyVim
- Python
- NodeJS
- Troubleshooting

---

## Documentation

| File | Description |
|--------|--------|
| `01-install-termux.md` | Instalasi dan setup awal Termux |
| `02-basic-packages.md` | Package dasar yang diperlukan |
| `03-git-github.md` | Dasar penggunaan Git dan GitHub |
| `04-github-ssh.md` | Konfigurasi SSH untuk GitHub |
| `05-lazyvim.md` | Setup LazyVim |

---

## Quick Start

Update package:

```bash
pkg update && pkg upgrade -y
```

Aktifkan storage:

```bash
termux-setup-storage
```

Install package dasar:

```bash
pkg install git curl wget unzip zip neovim python -y
```

---

## Learning Path

Ikuti dokumentasi secara berurutan:

1. `docs/01-install-termux.md`
2. `docs/02-basic-packages.md`
3. `docs/03-git-github.md`
4. `docs/04-github-ssh.md`
5. `docs/05-lazyvim.md`

---

## Troubleshooting

Masalah umum dan solusinya tersedia di:

```text
docs/troubleshooting/
```

---

## Status

- [x] Install Termux
- [x] Basic Packages
- [x] Git & GitHub
- [x] GitHub SSH
- [ ] LazyVim
- [ ] Python Setup
- [ ] NodeJS Setup

---

## License

MIT
