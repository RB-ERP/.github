# RADAR BOGOR

Selamat datang di repository organisasi kami! Di sini, kami berkolaborasi dalam berbagai proyek yang berkaitan dengan Aplikasi manajemen pengelolaan barang untuk Radar Bogor.

## Struktur Proyek

- **master/main branch**: Branch utama yang selalu berisi versi stabil dari proyek.
- **feature branches**: Branch yang digunakan untuk pengembangan fitur baru atau perbaikan bug. Setiap fitur baru atau perbaikan harus dikembangkan di branch terpisah.

## Panduan Kontribusi

### 1. Clone Repository

Jika Anda belum memiliki repository di lokal, clone repository terlebih dahulu:

```bash
git clone https://github.com/RB-ERP/RB-ERP.git
cd RB-ERP
```

### 2. Update Perubahan dari Remote (Git Pull)

Sebelum memulai pekerjaan, pastikan repository Anda up-to-date dengan branch utama:

```bash
git pull origin main
```

> **Catatan**: Pastikan branch Anda adalah `main` atau `master` sesuai dengan branch utama repository.

### 3. Membuat Branch Baru

Jika Anda ingin menambahkan fitur atau memperbaiki bug, buatlah branch baru terlebih dahulu:

```bash
git checkout -b nama-branch-anda
```

> **Keterangan**: Nama branch harus jelas dan deskriptif, seperti `feature-tambah-login`, `bugfix-koreksi-tanggal`, dll.

![image](https://assets-global.website-files.com/622642781cd7e96ac1f66807/62d0ef2b68ea1652c722e7a6_image-10.png)<h1 align="center">Stuktur Branch</h1>

### 4. Pindah Branch

Jika Anda ingin berpindah ke branch lain, gunakan perintah:

```bash
git checkout nama-branch
```

### 5. Menambah Perubahan ke Staging Area

Setelah melakukan perubahan, tambahkan file yang berubah ke staging area dengan perintah:

```bash
git add .
```

> **Catatan**: Jangan lupa untuk memeriksa perubahan dengan `git status` sebelum melakukan commit.

### 6. Commit Perubahan

Setelah semua file yang relevan ditambahkan, buat commit dengan pesan yang jelas:

```bash
git commit -m "Deskripsi singkat tentang perubahan yang Anda buat"
```

### 7. Push Perubahan ke Remote

Untuk mengirimkan perubahan Anda ke remote repository, gunakan perintah:

```bash
git push origin nama-branch-anda
```

### 8. Membuat Pull Request

Setelah selesai, Anda dapat membuat Pull Request (PR) di GitHub untuk menggabungkan perubahan Anda ke branch utama.

---

## Catatan Tambahan

- Pastikan untuk selalu bekerja di branch baru agar branch `main`/`master` tetap bersih dan stabil.
- Selalu berikan deskripsi yang jelas saat membuat commit maupun PR.
- Periksa Pull Request orang lain dan berikan review jika diperlukan.

---
