# 01-git-github
MDPL Praktikum Kelas IV (Pertemuan 1)
<br>Nama : Adyan Wahyu Pratama
<br>NIM : 5200411033
<br>
## Pengertian Git dan Github
<br>- Git dan GitHub merupakan dua platform yang didirikan oleh satu perusahaan dengan tujuan sama serta fitur yang berbeda. Namun kedua platform ini sangat membantu pekerjaan programmer dalam menyusun kode script secara tim. Seluruh pekerjaan dapat dipantau dan dievaluasi dengan mudah karena penggunaan kontrol sistem. Apa itu kontrol sistem atau yang biasa disebut VCS (Version Control System)? VCS adalah sebuah sistem atau teknologi yang menggunakan SCM (Source Code Management) yang fungsinya adalah untuk mengelola setiap perubahan yang terjadi. Karena adanya fitur ini para pengguna tidak perlu membuat duplikasi file di local yang dapat mengakibatkan bengkaknya penyimpanan (Storage). Dengan fitur VCS ini yang tersimpan hanyalah perubahan data yang terintegrasi dengan penyedia layanan.
<br>- Git adalah software berbasis VCS yang berfungsi untuk mencatat perubahan file atau data dari suatu project. Hampir semua programmer menggunakan git untuk mengembangkan aplikasi karena fungsinya yang bisa digunakan untuk tim dev. Untuk menginstall git anda dapat mendownload <a href='https://git-scm.com/downloads'>disini</a>.
<br>- Github sendiri adalah sebuah layanan cloud yang terintegrasi dengan git. Layanan cloud tersebut dapat digunakan untuk menyimpan file atau project. Karena adanya cloud storage ini akan meringankan penyimpanan lokal kita. 
## Langkah langkah Instalasi Git di Windows
<br>Karena saya hanya menggunakan OS Windows, jadi saya akan memberikan langkah langkah untuk instalasi Git di Windows. Berikut adalah langkah langkahnya =
<br>1. Download git terlebih dahulu <a href='https://git-scm.com/downloads'>disini</a>. Kalian juga dapat membaca documentation github <a href='https://git-scm.com/doc'>disini</a>.
  ![Download Git](https://user-images.githubusercontent.com/91451497/135682670-629813ff-26f6-44c6-b946-f0d8d2058e1f.png)
<br>Itu adalah potongan tampilan awal jika kalian ingin mendownload github. Sesuaikan dengan OS atau Sistem Operasi yang kalian gunakan, karena saya menggunakan windows maka saya akan download untuk Windows Version.
![Download Git 2](https://user-images.githubusercontent.com/91451497/135678764-56e2bacb-5ad5-45e9-8705-759b01d4f378.png)
<br>Jika sudah, maka kalian akan diminta untuk memilih versi 32 bit atau 64 bit. Sesuaikan dengan device yang digunakan. Untuk pilihan ada 2 juga, yang pertama adalah versi Installer atau setup dan yang kedua adalah versi portable dengan "thumbdrive edition". Silahkan download terlebih dahulu.
<br>2. Kemudian buka file installer nya. Akan muncul gambar seperti ini
![Install 1](https://user-images.githubusercontent.com/91451497/135689375-97963058-0a40-42be-8a98-2b3a3609e61d.png)
<br>3. Setup sudah dimulai silahkan klik next next saja dan sesuaikan dengan kebutuhan, tetapi saya sarankan sesuai default saja jika ragu atau tidak terlalu paham maksudnya. Bisa juga dengan searching google jika ingin tau maksudnya. Disini saya akan menjelaskan beberapa setup yang mungkin akan diganti.
![Install 2](https://user-images.githubusercontent.com/91451497/135689377-2f6a4860-faf7-4b9b-a179-ae181b67f6a5.png)
<br>4. Gambar di atas adalah setup file dari git dan git tersebut akan di install dimana. Misal : default = C:\Program Files\Git anda bisa menggantinya ke yang lain.
![Install 3](https://user-images.githubusercontent.com/91451497/135689378-f458cfd8-b926-4ce2-a5eb-647c8b41753f.png)
<br>5. Gambar di atas adalah Component yang akan terinstall di device kalian. Disini saya menambahkan centang ke Check Daily for Windows Update karena ingin mendapatkan update git ketika menyalakan Windows Update
![Install 4](https://user-images.githubusercontent.com/91451497/135689379-1008dfa5-d29e-4ea2-8adf-224baff5ada2.png)
<br>6. Gambar di atas adalah nama Menu Folder Startup, kalian bisa mengganti namanya. Menu Folder Startup ini adalah ketika kalian klik logo Windows yang ada di keyboard. 
![Install 5 (Default Vim)](https://user-images.githubusercontent.com/91451497/135689382-be8b195e-111f-4bd5-9b4d-3bc64b8de558.png)
<br>7. Disini adalah pemilihan Code Editor. Default nya adalah Vim tetapi saya ubah menjadi Visual Studio Code karena menurut saya lebih mudah. Jika vim biasa digunakan untuk Linux. Kalian bisa menyesuaikan dengan kebutuhan juga.
![Install 6](https://user-images.githubusercontent.com/91451497/135689384-3e6caad2-88af-4783-91d9-7b288d152b63.png)
<br>
![Install 7](https://user-images.githubusercontent.com/91451497/135689386-b60ac838-6661-4819-9b7f-abadeccacbbf.png)
<br>8. Konfigurasi selanjutnya adalah Setting SSH serta SSL. Jika tidak terlalu paham maksudnya saya sarankan untuk default saja. Saya disini setting Default semua
![Install 8](https://user-images.githubusercontent.com/91451497/135689388-3f156d38-fcaf-4e3a-a19a-c97f44b89c09.png)
<br>9. Gambar di atas adalah Experimental Configuration. Mungkin ini ditujukan untuk yang membutuhkan. 
![Install 9](https://user-images.githubusercontent.com/91451497/135689392-31499b6b-3250-4684-9bcb-f4610db24c64.png)
<br>10. Proses Instalasi
<br>
![Install 10](https://user-images.githubusercontent.com/91451497/135689393-ea56d0aa-92ef-4135-8da1-7f9fdd945791.png)
<br>11. Instalasi Selesai. Disarankan untuk Restart PC atau Device.
<br>Jika Instalasi selesai silahkan cek di Folder Startup dengan cara klik logo Windows. Akan ada beberapa aplikasi : Git Bash, Git Gui, Git CMD
<br>Untuk mengecek versi git kalian bisa buka CMD/Powershell atau Git CMD. Cara pemanggilan = git --version
![Ver Git](https://user-images.githubusercontent.com/91451497/135699266-2184b951-79bf-4671-9c08-b1ca7ccf2c51.png)
Itu adalah git yang terinstall di laptop saya. Sekian itulah instalasi Git.
## Mengkonfigurasi Akun Git
<br>Konfigurasi git dilakukan untuk memberitahu git siapa saja yang melakukan perubahan pada data atau repo pada git. Konfigurasi ini hanya diminta untuk username dan email. Konfigurasi ini cukup dilakukan sekali. Kecuali ingin merubah data username dan email. Dengan konfigurasi ini jika kita melakukan kegiatan secara kelompok atau membuat aplikasi secara kelompok akan lebih mudah siapa yang merubah atau mengganti script nya.
<br>Pertama tama buka Gitbash
![GitBash](https://user-images.githubusercontent.com/91451497/135702697-ed6045bc-7074-407d-acde-c3da7212fcda.png)
<br>Akan muncul tampilan seperti di atas>> Kemudian masukkan command sebagai berikut :
<br> $ git config --global user.name "Nama Anda di GitHub"
<br> $ git config --global user.email email@domain.tld
<br>Jika sudah, untuk cek email dan username yang terdaftar ketik
<br> $ git config --list 
![Gitbash 2](https://user-images.githubusercontent.com/91451497/135702761-05910995-c09a-4934-b4f4-00249f549383.png)
Akan muncul seperti di atas, ada keterangan Username dan Email.
<br>Untuk mengganti username dan email kalian dapat menemukan file .gitconfig di C:\Users\(Nama User)\.gitconfig
<br>Untuk mengedit username dan email dapat menggunakan Notepad++ atau Visual Studio Code ataupun Code Editor lainnya.
## Mengelola Repo
<br>Beberapa cara untuk mengelola repo adalah sebagai berikut =
<br>1. Membuat repositori kosong di github
<br>2. Upload file lokal ke repository github dengan git add dan git push
<br>3. Download file di repo github ke lokal dengan git clone
### 1. Membuat Repositori Kosong Di Github
<br>- Buka website github dan login ke akun github
<br>- Cari tanda + di bagian kanan atas (Letaknya bersebelahan dengan gambar Profile)
![New Repo](https://user-images.githubusercontent.com/91451497/135718382-31421810-8f30-4dfb-9bd6-586c92b11f5e.png)
<br>- Selanjutnya pilih New Repository atau jika bahasa Indonesia adalah Repositori Baru
<br>- Jika sudah akan muncul opsi seperti dibawah ini
![Create Repo 1](https://user-images.githubusercontent.com/91451497/135718501-3451f4d4-eb84-4d74-99b5-4b199190fafa.png)
<br>- Silahkan isikan nama repo dan deskripsi repo tersebut. Bisa di setting Public ataupun Private (Jika publik berarti data repo akan di publikasikan). Bisa juga menambahkan Lisensi. Ada juga .gitignore yang dapat mengabaikan file yang sudah kita masukan ke list .gitignore, Sebagai contoh ada seorang dev aplikasi yang menggunakan git dia ingin salah satu file nya tidak diketahui oleh orang yang mendownload repo atau untuk melihat repo tsb. Maka dengan gitignore kita dapat mengabaikan file tersebut agar tidak di track oleh orang lain.
<br>- Selanjutnya silahkan klik "Create Repository" dan tara repo baru berhasil dibuat
### 2. Upload File Ke Repository Github
<br>- Siapkan terlebih dahulu file yang ingin ditambah ke repo github
<br>- Cek terlebih dahulu dengan git status untuk mengecek status di repo github
![Git add](https://user-images.githubusercontent.com/91451497/135720101-2bf1fc73-9928-4543-89f5-682f8f537f67.png)
<br>- Terlihat dari gambar di atas berarti file index.html belum ada di repo github yang menandakan data tersebut belum diawasi.
<br>- Selanjutnya silahkan git add (nama file) atau bisa juga git add . (Ini berarti semua file yang ada di lokal akan di cek)
![Git add 2](https://user-images.githubusercontent.com/91451497/135720097-a9c04734-a1c5-45b6-9b72-ad48d432b7c3.png)
<br>- Silahkan cek kembali dengan git status, warna berubah menjadi hijau yang awalnya merah, berarti siap di commit 
<br>- Sekarang waktunya commit. Caranya adalah sebagai berikut : git commit -m "(Update Apa?)"
![Git commit 2](https://user-images.githubusercontent.com/91451497/135720094-a48f0bad-bb2c-4cf0-9f76-15f91c3df7a2.png)
<br>- Silahkan langsung git push dengan cara, git push origin (branch) default nya master atau main
![Git Push](https://user-images.githubusercontent.com/91451497/135720092-567f1c78-2a84-4b37-bbdb-e6c26caa5a43.png)
<br> Jika sudah berhasil seperti gambar di atas silahkan cek repo github.
### Download Repo dengan Git Clone
<br> Download repo ini berfungsi ketika kalian pindah device atau sedang bepergian dan menggunakan device lain kalian dapat mengikuti konfigurasi yang ada di github anda
<br>- Cari lokasi direktori di lokal terlebih dahulu, kemudian buka cmd atau powershell di direktori tsb
<br>- Cara untuk clone cukup mudah yaitu, git clone (link github). Bisa di cmd atau powershell atau yang lainnya.
![Git Clone](https://user-images.githubusercontent.com/91451497/135720574-aacb31e4-fe85-445d-97fe-cc8fda134d1a.png)
<br> Jika sudah maka akan muncul di direktori yang sudah kita tentukan.
<br> **Terima Kasih, Mohon Maaf bila ada kalimat yang kurang tepat dan penjelasan yang berbelit**