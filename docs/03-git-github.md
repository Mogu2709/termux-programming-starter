Git dan GitHub Dasar

Konfigurasi Git

Ganti dengan nama dan email GitHub milikmu.

git config --global user.name "Nama Kamu"
git config --global user.email "email@example.com"

Cek konfigurasi:

git config --list

Membuat Repository Baru

Masuk ke folder project:

mkdir my-project
cd my-project

Inisialisasi Git:

git init

Menambahkan File

git add README.md

Atau semua file:

git add .

Commit

git commit -m "Initial commit"

Menghubungkan ke GitHub

Tambahkan remote repository:

git remote add origin git@github.com:USERNAME/REPOSITORY.git

Cek remote:

git remote -v

Push ke GitHub

git branch -M main
git push -u origin main

Cek Status Repository

git status

Perintah ini sangat sering digunakan untuk melihat perubahan file sebelum melakukan commit.
