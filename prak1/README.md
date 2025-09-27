# Praktikum Tugas 1
## Informasi Dosen
- Nama Dosen : Adi Wahyu Pribadi, S.Si., M.Kom
## Mahasiswa
- Nama : Waode Fairuzh Ramadhani Somandeno
- NPM  : 4523210111
##  Praktikum Tugas 1
### Langkah-Langkah Setup Git dan Push ke GitHub

1. Download Git
   ![Download Git](https://github.com/user-attachments/assets/811fe067-ec33-4354-8826-5672c4da6980)

2. Cek versi Git setelah selesai diinstal
   
   ![Cek Version](https://github.com/user-attachments/assets/ec5da2a7-3ab3-47c5-abfb-1b3cd45e3d0e)

4. Buat folder proyek

   * Buat folder dengan nama "PRAK PBW-A" di VS Code.
   * Di dalamnya, buat subfolder "praktikum1.git".
     
     ![Buat Folder](https://github.com/user-attachments/assets/29981064-c0b8-4a17-b900-222b17d1302c)

5. Inisialisasi Git dengan perintah:

   git init
   
   <img width="567" height="34" alt="git init" src="https://github.com/user-attachments/assets/1fb808f9-ee1b-4cc4-89fa-70a461cb82e5" />

6. Tambahkan file ke staging area:

   git add .

   <img width="397" height="18" alt="git add" src="https://github.com/user-attachments/assets/29d0c6ac-3375-4c8b-b389-92aab3980bbf" />

7. Buat commit pertama dengan pesan:

   git commit -m "commit 1"

   ![Commit](https://github.com/user-attachments/assets/a2a619c5-e8e3-496f-bf1f-0319143018d3)

8. Ganti nama branch menjadi `main`:

   git branch -M main

   ![Branch Main](https://github.com/user-attachments/assets/5f3442e9-d6d1-40d2-819b-48c8282502fe)

9. Hubungkan repository lokal dengan GitHub (remote):

   git remote add origin https://github.com/akunfairuzh/P-PBW-A.git

   ![Remote](https://github.com/user-attachments/assets/c7c6715e-311e-4867-9856-b9f84a3b788b)

10. Push commit ke GitHub:

   git push -u origin main

   ![Push](https://github.com/user-attachments/assets/9d7a7165-3fbe-4b2b-8989-f29537fe5b7e)
