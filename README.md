Repository ini ini berisi hasil latihan untuk mempelajari dasar Git dan branch.

## 📌 Topik yang Dicakup

### 🔧 Konfigurasi Dasar
- Setup awal Git (username, email)
- Konfigurasi lokal

### 🔄 Workflow Fundamental
- Siklus kerja Git: working directory → staging area → repository
- Praktik commit yang efektif
- Teknik pembatalan perubahan:
  - Membatalkan modified file (`git checkout`)
  - Mengeluarkan file dari staging (`git reset`)
  - Revisi commit terakhir (`git commit --amend`)

### 🕵️‍♂️ Eksplorasi History
- Melihat log commit (`git log`)
- Navigasi ke commit spesifik (`git checkout <commit-hash>`)
- Melihat perubahan antar commit (`git diff`)

### 🌿 Branch Management
- Pembuatan dan navigasi branch
- Teknik penggabungan:
  - Merge 
  - Squash
  - rebase
- Resolusi conflict:
  - Identifikasi konflik
  - Membenarkan code yang konflik
  - Pembatalan merge

### 📦 Stash Management
- Penyimpanan sementara pada code yang belum siap di commit (`git stash`)

## 🛠 Cara Menggunakan
1. Clone repository:
   ```bash
   git clone https://github.com/username/git-dasar.git
