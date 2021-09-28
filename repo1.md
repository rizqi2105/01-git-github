<h2>Instalasi Git.<br></h2>
Git adalah version control system yang digunakan para developer untuk mengembangkan software secara bersama-bersama. Fungsi utama git yaitu mengatur versi dari source code program anda dengan mengasih tanda baris dan code mana yang ditambah atau diganti.Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja. Git tersedia untuk berbagai sistem operasi. Precompiled binaries bisa diperoleh di halaman dowbload Git untuk 3 sistem operasi utama: Linux, Mac OS X, dan Windows. Git bisa menggunakan antarmuka grafis (GUI) maupun CLI (command line interface). Pada materi ini, kita akan banyak menggunakan antarmuka CLI melalui shell (Linux / Mac OS X) atau command prompt / PowerShell di Windows.<br> 
berikut langkah-langkah menginstall Git sebagai berikut:<br>
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
Secara minimal, user harus memberitahu Git tentang username serta email yang digunakan setiap kali terjadi perubahan pada repo Git. Username serta email ini yang akan dimasukkan oleh Git ke catatan perubahan di repo. Di sistem operasi Windows, konfigurasi ini akan disimpan di C:\Document and Settings\NamaUser dengan nama file .gitconfig. Secara minimal, ada 2 hal yang perlu dikonfigurasi yaitu username dan email. <br>
langkah untuk konfigurasi Git sebagai berikut: <br>
1. buka CMD di komputer/laptop.<br>
2. lalu ketik "git config --global user.name "Nama Anda di GitHub"", ini berguna untuk mengatur username pada git, setelah itu enter.<br>
3. lalu ketik "git config --global user.email email@domain.tld", ini digunakan untuk menatur email pada git, setelah itu enter.<br>
4. Untuk melihat konfigurasi yang sudah ada ketik"git config --list", lalu enter.<br>
5. ini adalah contoh hasil konfigurasi pada perubahan email dan nama pada Git.<img width="708" alt="Screenshot 2021-09-27 175339" src="https://user-images.githubusercontent.com/91447664/134895285-495d5981-c5e8-4835-a7c2-2d755f75ab10.png">
<br>
Langkah ini cukup dilakukan sekali saja, kecuali jika ingin melakukan perubahan nama dan email.

<br>
<br>
<h2>Mengelola Repo Sendiri</h2><br>
 <ul><h4>• Mengelola Repo Sendiri di Account Sendiri.</h4><br>
 Langkah-langkah untuk membuat repo sendiri yaitu :<br>
 1. pertama buka github.com lalu jika tidak mempunyai akun harus membuat terlebih dahulu, setelah itu login.<br>
 2. lalu klik tanda + pada bagian atas, setelah itu pilih New repository<br> <img src="https://user-images.githubusercontent.com/91447664/135107184-401aff7d-ae03-4610-999d-97d04ef38a36.png"><br>
 3. setelah itu isikan nama, deskripsi, type repo, serta lisensi. <img src="https://user-images.githubusercontent.com/91447664/135108039-ed8b2e8b-465f-43f6-8044-63283027dcf2.png"><br>
 4. lalu klik <b>Create Repository.</b><br>
 
 <h4>• Clone repo</h4>
 Proses clone adalah proses untuk menduplikasikan remote repo di GitHub ke komputer lokal. Untuk melakukan proses clone digunakan langkah-langkah yaitu:<br>
 1. pertama buka Github dan login terlebih dahulu.<br>
 2. lalu pilih lokasi penyimpanan/folder untuk penyimpanan clone repo yang akan disimpan. <img src="https://user-images.githubusercontent.com/91447664/135113978-9ebf2ca6-130f-466d-bf7d-2b15db2528f3.png"><br><br>
 3. setelah itu klik kanan pada folder yang mau disimpan, setelah itu pilih Git bash here.<img src="https://user-images.githubusercontent.com/91447664/135114578-de420357-85a2-4956-8585-266ba56a7ca4.png"><br><br>
 4. lalu buka kembali Github dan pilih repo yang akan disimpan.<br>
 5. kemudian klik tombol <b>Code<b/> dan copy paste link https nya.<img src="https://user-images.githubusercontent.com/91447664/135115601-a32bab8e-f292-4935-afd6-b3172157ce2f.png"><br><br>
 6. buka kembali Git bash (cmd), lalu ketik "git clone https://github.com/rizqi2105/01-mppl.git" setelah itu enter dan seperti ini hasil nya: <img src="https://user-images.githubusercontent.com/91447664/135117806-13ddfefb-2ae6-486a-86da-9240ce7a7389.png">
</ul>


 
 
 
