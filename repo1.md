<h2>Instalasi Git.<br></h2>
Git tersedia untuk berbagai sistem operasi. Precompiled binaries bisa diperoleh di halaman dowbload Git untuk 3 sistem operasi utama: Linux, Mac OS X, dan Windows. Git bisa menggunakan antarmuka grafis (GUI) maupun CLI (command line interface). Pada materi ini, kita akan banyak menggunakan antarmuka CLI melalui shell (Linux / Mac OS X) atau command prompt / PowerShell di Windows. Setelah instalasi, periksa keberhasilan instalasi dengan menggunakan:
Windows<br>
1. Pertama kita harus download Git terlebih dahulu. <img src="https://user-images.githubusercontent.com/91447664/134845967-2d0d6a22-8290-4d4a-8297-b0171f0921cf.png"> 
2. Kedua setelah download, buka file yang sudah didownload lalu muncul lisensi dan klik next.  <img src="https://user-images.githubusercontent.com/91447664/134846522-891e462c-368d-4c0a-a0e6-e81cb24ff5ce.png"> 
3. Ketiga pilih lokasi instalasi lalu klik next. <img src="https://user-images.githubusercontent.com/91447664/134866738-5b39dce3-202e-4297-af03-87b0ad0b4ac4.png">
4. setelah itu pilih komponen lalu klik next. <img src="https://user-images.githubusercontent.com/91447664/134866922-a762e2ae-7c9c-4afd-8dff-46b9acf4d8c7.png">
5. selanjutnya mengisi shortcut untuk menu Start dan gunakan default Gif. <img src="https://user-images.githubusercontent.com/91447664/134867448-76cf12fc-89a2-4d12-95a2-43263348fb3f.png">
6. lalu pilih editor yang akan digunakan bersama dengan Git. Pada pilihan ini, saya menggunakan visual studio code. <img src="https://user-images.githubusercontent.com/91447664/134867818-1bd678ad-77a7-4a23-b1b8-2645001bf885.png">
7. pilih Git to name the initial branch. <img src="https://user-images.githubusercontent.com/91447664/134868241-de3cb1c9-3425-4ae3-944f-7d6087bbd388.png">
8. lalu pilih path environment.<br> <img src="https://user-images.githubusercontent.com/91447664/134868357-5a0ae75b-28f7-4e1f-a9d9-1321f41c0cd5.png">
9. pilih openSSH untuk ssh.<br> <img src="https://user-images.githubusercontent.com/91447664/134869716-fb0ab8fd-789d-4c49-9498-9a26ef5059e8.png">
10. pilih openSSL untuk HTTPS.<br> <img src="https://user-images.githubusercontent.com/91447664/134869871-9ba8e62d-233f-4ff6-9812-6991cd1a03cd.png">
11. Pilih opsi pertama untuk konversi akhir baris (CR-LF). <img src="https://user-images.githubusercontent.com/91447664/134870061-19bb8fd1-d416-45b0-95a0-2a36447d2b42.png">
12. Selanjutnya pilih PuTTY untuk terminal yang digunakan untuk mengakses Git Bash.<img src="https://user-images.githubusercontent.com/91447664/134870259-78866053-38da-455f-9859-7152b23a5921.png">
13. Lalu pilih default.<br> <img src="https://user-images.githubusercontent.com/91447664/134870942-acf6c1bd-47d8-4162-b78f-b520fa328624.png">
14. selanjut nya pilih Git Credential manager core. <img src="https://user-images.githubusercontent.com/91447664/134871106-e5cad55a-5e8a-4ac5-b7da-2e9bde42c6f2.png">
15. Untuk opsi ekstra, pilih serta aktifkan enable file system caching. <img src="https://user-images.githubusercontent.com/91447664/134871289-a5ee41c1-64c3-4aeb-b4f8-2719d32d6b01.png">
16. setelah itu klik install.
17. setelah proses install selesai, lalu klik finish. <img src="https://user-images.githubusercontent.com/91447664/134871733-3943b7f4-a176-4ad9-8f77-3f7abe615e8b.png">
18. Untuk mencoba dari command prompt, masuk ke command prompt, setelah itu eksekusi "git --version" untuk melihat apakah sudah terinstall atau belum. Jika sudah terinstall dengan benar, makan akan muncul hasil berikut: <img src="https://user-images.githubusercontent.com/91447664/134872313-13572626-0d2f-4f97-bfb8-8f4e4334b05f.png">
<br>
<br>
<h2>Konfigurasi Git<br></h2>
Secara minimal, user harus memberitahu Git tentang username serta email yang digunakan setiap kali terjadi perubahan pada repo Git. Username serta email ini yang akan dimasukkan oleh Git ke catatan perubahan di repo. Di sistem operasi Linux atau sejanis (UNIX), konfigurasi ini nantinya akan disimpan di $HOME/.gitconfig. Untuk sistem operasi Windows, konfigurasi ini akan disimpan di C:\Document and Settings\NamaUser dengan nama file .gitconfig. Secara minimal, ada 2 hal yang perlu dikonfigurasi yaitu username dan email. Gunakan perintah berikut:<br> <img width="708" alt="Screenshot 2021-09-27 175339" src="https://user-images.githubusercontent.com/91447664/134895285-495d5981-c5e8-4835-a7c2-2d755f75ab10.png">

 <br>
Langkah ini cukup dilakukan sekali saja, kecuali jika ingin melakukan perubahan nama dan email.
Pertama, tinjauan singkat: Git menggunakan bermacam-macam konfigurasi berkas untuk menentukan perilaku non-bawaan yang Anda inginkan. Tempat pertama Git mencari nilai-nilai tersebut adalah di berkas /etc/gitconfig, yang berisi nilai-nilai untuk setiap pengguna di sistem dan semua repositori-repositori mereka. Jika Anda memberikan pilihan --system ke git config, maka pilihan tersebut akan membaca dan menulis dari berkas ini secara khusus.

Tempat selanjutnya yang akan dilihat oleh Git adalah berkas ~/.gitconfig (atau ~/.config/git/config), yang khusus untuk setiap pengguna. Anda bisa membuat Git membaca dan menulis pada berkas ini dengan memberikan pilihan --global.

Akhirnya, Git akan mencari nilai-nilai konfigurasi di dalam berkas konfigurasi yang berada di direktori Git (.git/config) untuk repositori apapun yang sedang Anda gunakan. Nilai-nilai tersebut hanya untuk satu repositori tersebut.
<br>
<br>
<h2>Mengelola Repo Sendiri</h2><br>
