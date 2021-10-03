INSTALASI GIT
1. Mendownload git.
2. Menyiapkan editor teks karna saya menggunakan windows jadi saya memilih memakai visual studio code.
3. Melakukan instalasi git :
   -Setelah download Git, double click pada file yang di-download. Akan dimunculkan lisensi. Klik Next untuk lanjut.
   -Setelah itu, pilih lokasi instalasi. Secara default akan terisi C:\Program Files\Git. Ganti lokasi jika memang anda menginginkan lokasi lain, klik Next.
   -Memilih komponen. Tidak perlu diubah-ubah, sesuai dengan default saja. Klik pada Next.
   -Mengisi shortcut untuk menu Start. Saya tetap menggunakan default (Git).
   -Memilih editor yang akan digunakan bersama dengan Git, saya memilih menggunakan Visual studio code.
   -Memilih Let Git decide.
   -Memilih Git from the command line and also from 3rd party software.
   -Memilih Use bundled OpenSSH.
   -Memilih OpenSSL untuk HTTPS. Git menggunakan https untuk akes ke repo GitHub atau repo-repo lain (GitLab, Assembla).
   -Memilih checkout windows-style, commit unix-style line endings.
   -Meilih MinTTY(The default terminal of MSYS2.
   -Memilih Default (fast-forward or merge).
   -Memilih Git credential Manager core.
   -Memilih Enable file system caching.
   -Kemudian Next dan lakukan Install.
   -Setelah itu proses intall akan berlangsung.
   -Lalu akan muncul dialog Completting the Git Setup Wizard, klik Finish.
   -Setelah itu cari Git Bash dan di klik.
   -Kemudian kita ketikan $ pwd, lalu enter.
   -Lalu klik command prompt, setelah itu ketikan "git --version" untuk melihat apakah sudah terinstall  atau belum.
4. Membuat akun github :
  -Buka google lalu tuliskan join github.
  -Lalu kita akan diminta untuk mengisi username email dan password serta melakukan verifikasi.
  -Jika sudah maka akun github berhasil dibuat.

KONFIGURASI GIT
1. lakukan konfigurasi dengan membuka git bash lalu menuliskan:
   $ git config --global user.name "ElizabethChelsea"
   $ git config --global user.email chelseaeliza13@gmail.com
2. Lalu ketikan :
   $ git config –list
   Untuk melihat konfigurasi yang sudah ada.

MENGELOLA REPO SENDIRI
   	Membuat Repo
1. Membuat repo dengan membuka akun github yang tadi sudah dibuat kemudian klik tanda + lalu pilih 
   new repository.
2.	Mengisikan nama, keterangan, serta lisensi.
3.	Pilih repository ingin Public atau Private.
4.	Lalu klik creat repository.
    
    Clone Repo
1.	Menyiapkan folder untuk menyimpan hasil clone data.
2.	Kemudian klik kanan folder yang sudah disiapkan tadi.
3.	Lalu pilih Git Bash Here.
4.	Buka repository yang ingin di clone melalui GitHub.
5.	Lalu copy link repository tersebut.
6.	Kemudian buka Git Bash yang tadi, lalu ketikan :
    $ git clone https://github.com/ElizabethChelsea/01-git-github.git 
7.	Lalu klik enter.
8.	Karna repo yang saya masih kosong maka muncul peringatan bahwa repo tersebut kosong. Dalam 
    kasus seperti ini, biarkan saja, tidak masalah.
    $ git clone https://github.com/ElizabethChelsea/01-git-github.git
    Cloning into '01-git-github'...
    warning: You appear to have cloned an empty repository.

    Mengelola repo

1. Buka repository di github Lalu copy url dari repository tersebut.
2. Membuka folder yang ingin di push ke github melalui visual studio code.
3. Klik source control, lalu klik initialize repository.
4. Kemudian di bagian messeage, tuliskan first commit lalu klik tanda centang diatasanya.
5. Lalu nanti akan muncul dialog there are no staged changes to commit, klik yes.
6. Kemudian klik view, pilih command palette lalu ketik add remote.
7. Lalu paste url dari repository github tadi, lalu enter.
8. Ketikkan nama repository yang dituju, lalu enter.
9. Lalu klik simbol untuk publish perubahan dan proses push berhasil.