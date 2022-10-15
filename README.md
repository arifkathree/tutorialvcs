<p align="center">
  <a href="https://www.pelitabangsa.ac.id/">
      <img width="200" src="https://www.pelitabangsa.ac.id/wp-content/uploads/2019/09/LOGO_UPB_NEW-1.png">
  </a>
</p>  

# 🖥 Latihan VCS Step By Step 

<p align="center">
  <a href="https://github.com">
      <img width="1000" src="https://ids.ac.id/wp-content/uploads/2022/06/github1.png">
  </a>
</p>

> ## Download Git Bash
> Sebelum kalian memulai Tutorialnya, kalian wajib **Download** Programnya terlebih dahulu.
>- [Git Bash](https://git-scm.com/downloads)

![image1](images/1.png)

## 🤖 Konfigurasi Nama Device dan E-mail
Hal ini perlu kalian lakukan agar tidak terjadi error saat kalian melakukan perintah ***git commit***.
> ***$ git config --global user.name "UsernameAnda"***
> 
> ***$ git config --global user.email "email anda"***

![image config](images/config.png)

## 🌐Buat Akun di **Github**
Buat Akun atau ***Sign In*** [GitHub](https://github.com)

![image2](images/2.png)

## 📔Buat Repository Baru
Setelah berhasil membuat akun baru dan sudah Login ke [GitHub](https://github.com) Anda bisa membuat Repository dengan mengklik Button ***'New'*** pada tampilan awal [GitHub](https://github.com) Anda.

![image3](images/3.png)

Kemudian Kalian akan diarahkan pada halaman untuk membuat Repository baru.

![images4](images/4.png)

## :floppy_disk: Buat Folder Baru
Lalu kalian buat folder di Local Disk komputer kalian.

![imagefolder](images/5.png)

> ## :warning: SEDUH KOPI DAN BELI ROKOK :warning:
> Sebelum lanjut, disarankan untuk membuat kopi dan rokok dulu. Karena tahap dibawah memiliki beberapa efek samping, seperti:
> - Kepala Bergetar
> - Nyeri Dibagian Badan Belakang
> - Kedutan Bahkan Kejang 

Setelah kalian buat folder baru **Klik Kanan** pada **Folder** tersebut lalu klik **Git Bash Here** maka akan muncul Pop-up aplikasi Git Bash

![imagegitbash](images/6.png)

Buat **Folder Baru** dan mengarahkan **Git Bash** pada directory file tersebut
>$mkdir latihan1
>
>$cd latihan1

![imagemkdir](images/7.png)

Tambahkan Judul atau **Header** ke dalam file **README.md** yang nantinya akan dimasukkan ke dalam **Repository** yang telah kita buat
>$echo "#LatihanVCS" >> README.md

![image](images/8.png)

Kemudian buaat Repository lokal menggunakan perintah ***git init***
>$ git init

![imageinit](images/9.png)

Masukkan file **README.md** yang beri judul tadi ke dalam **Repository** menggunakan perintah ***git add***
>$git add README.md

![images10](images/10.png)

Setelah ditambahkan, kalian harus menyimpan dan mengkonfirmasi perubahan dengan komentar menggunakan perintah ***git commit -m "contoh commit"***
>$ git commit -m "Commit Pertama"

![imagecommit](images/11.png)

Setelah itu menambahkan remote repository. remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user. dengan menggunakan perintah ***git remote add 'nama' 'url'***
>$git remote add origin https://github.com/arifkathree/tutorialvcs.git

![imageremote](images/12.png)

Dan untuk mengirim perubahan pada local Repository ke server gunakan perintah ***git push -u 'nama' 'branch'***
>$git push -u origin master

![imagepush](images/13.png)

Terakhir kita bisa cek di Repository pada Website [Github](https://github.com)

## Roadmap
- [x] Login / Sign Up
- [x] Buat Repository
- [x] Buat Folder dan Bash Here
- [x] Buat Folder dan Arahkan Directory
- [x] Buat Judul Pertama (echo "#Bla Bla Bla" >> README.md)
- [x] Inisialiasi .git (git init)
- [x] git add README.md
- [x] Keterangan Konfirmasi (git commit -m "sample commit")
- [x] Menghubungkan Repository (git remote add origin url)
- [x] Upload Perubahan (git push -u origin master)
  



