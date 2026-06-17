Masuk Folder
cd ~/OneDrive/Desktop/BELAJARGIT

~ = folder home user.

Lihat Isi Folder
ls

Lihat semua file termasuk tersembunyi:

ls -a

Contoh:

.git
Readme.md

.git = folder yang dibuat Git.

Buat Repository Git
git init

Membuat repository Git di folder saat ini.

Cek Status
git status

Perintah yang paling sering dipakai.

File Baru (Untracked)
Untracked files:
    Readme.md

Artinya Git melihat file, tapi belum melacaknya.

Masukkan ke Staging Area
git add .

. = semua file.

Cek Lagi
git status

Contoh:

Changes to be committed:
    new file: Readme.md

Artinya siap di-commit.

Simpan ke Riwayat Git (Commit)
git commit -m "Init readme"

Contoh:

git commit -m "Fix value in readme file"
Lihat Riwayat
git log --oneline

Contoh:

1160a51 Fix value in readme file
ad82d44 Init readme
Alur Kerja Git
Buat/Ubah File
      ↓
git status
      ↓
git add .
      ↓
git commit -m "pesan"
      ↓
git log --oneline
3 Status File Git
Untracked  → belum dilacak Git
Staged     → sudah git add
Committed  → sudah git commit

Contoh:

Readme.md
↓
git add .
↓
Staged
↓
git commit -m "Init readme"
↓
Committed