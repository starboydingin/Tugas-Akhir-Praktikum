🎨 Portfolio Website - Tugas Akhir Praktikum Pemrograman Web

Repositori ini merupakan project **Tugas Akhir Praktikum Pemrograman Web**, berisi website portfolio pribadi yang dibuat menggunakan **HTML** dan **CSS**.  
Proyek ini juga menjadi sarana latihan penggunaan **Git dan GitHub** untuk pengelolaan versi kode secara profesional.

🧱 Deskripsi Proyek

Website ini berisi tampilan portfolio sederhana yang mencakup:
- Halaman utama (`index.html`)
- Navigasi menu
- Styling menggunakan `style.css`
- Struktur folder rapi (HTML, CSS, dan assets/gambar)

Tujuan proyek ini adalah untuk memahami:
- Alur kerja Git (init, add, commit, branch, merge)
- Penggunaan GitHub sebagai remote repository
- Pengembangan website statis dengan HTML & CSS

⚙️ Langkah Instalasi & Setup Git

Langkah-langkah yang telah dilakukan untuk menginisialisasi dan mengelola project ini:

bash
1. Inisialisasi repository Git lokal
git init

2. Konfigurasi user lokal
git config --local user.name "username"
git config --local user.email "example@gmail.com"

3. Menambahkan file pertama (index.html)
git add index.html
git commit -m "Add index.html"

4. Menambahkan file CSS dan update index
git add style.css
git commit -m "Add style.css and update to index.html"

5. Menghubungkan ke repository GitHub
git remote add origin https://github.com/username-github/nama-repository-github.git

6. Push pertama ke branch master
git push -u origin master

7. Membuat branch baru untuk eksperimen navigasi
git branch navigation
git checkout navigation

8. Commit perubahan navigasi
git add .
git commit -m "add navigation menu"

9. Kembali ke branch utama dan merge hasil eksperimen
git checkout master
git merge navigation
git branch -d navigation

Notes: langkah-langkah di bawah bisa di skip aja jika baru pertama kali push ke repository baru

10. Sinkronisasi dengan branch main dari GitHub
git fetch origin main
git merge origin/main --allow-unrelated-histories

11. Ubah branch lokal dari master ke main
git branch -M main

12. Push branch main ke GitHub
git push -u origin main

13. Hapus branch master di GitHub
git push origin --delete master
