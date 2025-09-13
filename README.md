# Instruksi Dasar Git dan GitHub

Repository ini berisi instruksi dasar mengenai penggunaan Git dan GitHub.

## 1. Git Dasar
- `git init` → Membuat repository Git baru di folder lokal.
- `git status` → Mengecek status perubahan file.
- `git add <file>` → Menambahkan file ke staging area.
- `git commit -m "pesan commit"` → Menyimpan perubahan ke repository lokal.
- `git log` → Melihat riwayat commit.

## 2. Bekerja dengan Remote Repository
- `git remote add origin <url>` → Menghubungkan repository lokal ke GitHub.
- `git branch -M main` → Mengubah nama branch menjadi `main`.
- `git push -u origin main` → Mengirim commit pertama ke GitHub.
- `git pull origin main` → Mengambil update terbaru dari GitHub.

## 3. Alur Kerja Dasar
1. Ubah / tambahkan file di lokal.
2. Simpan perubahan dengan `git add` dan `git commit`.
3. Dorong perubahan ke GitHub dengan `git push`.

## 4. Tips
- Gunakan commit message yang jelas agar riwayat mudah dipahami.
- Buat branch baru untuk fitur/pekerjaan berbeda (`git checkout -b nama-branch`).
- Lakukan `git pull` sebelum mulai bekerja agar sinkron dengan repo utama.
