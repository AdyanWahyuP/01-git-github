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
<br>Setup sudah dimulai silahkan klik next next saja dan sesuaikan dengan kebutuhan, tetapi saya sarankan sesuai default saja jika ragu atau tidak terlalu paham maksudnya. Bisa juga dengan searching google jika ingin tau maksudnya. Disini saya akan menjelaskan beberapa setup yang mungkin akan diganti.
![Install 2](https://user-images.githubusercontent.com/91451497/135689377-2f6a4860-faf7-4b9b-a179-ae181b67f6a5.png)
<br>Gambar di atas adalah setup file dari git dan git tersebut akan di install dimana. Misal : default = C:\Program Files\Git anda bisa menggantinya ke yang lain.
![Install 3](https://user-images.githubusercontent.com/91451497/135689378-f458cfd8-b926-4ce2-a5eb-647c8b41753f.png)
<br>Gambar di atas adalah Component yang akan terinstall di device kalian. Disini saya menambahkan centang ke Check Daily for Windows Update karena ingin mendapatkan update git ketika menyalakan Windows Update
![Install 4](https://user-images.githubusercontent.com/91451497/135689379-1008dfa5-d29e-4ea2-8adf-224baff5ada2.png)
<br>Gambar di atas adalah nama Menu Folder Startup, kalian bisa mengganti namanya. Menu Folder Startup ini adalah ketika kalian klik logo Windows yang ada di keyboard. 
![Install 5 (Default Vim)](https://user-images.githubusercontent.com/91451497/135689382-be8b195e-111f-4bd5-9b4d-3bc64b8de558.png)
<br>Disini adalah pemilihan Code Editor. Default nya adalah Vim tetapi saya ubah menjadi Visual Studio Code karena menurut saya lebih mudah. Jika vim biasa digunakan untuk Linux. Kalian bisa menyesuaikan dengan kebutuhan juga.
![Install 6](https://user-images.githubusercontent.com/91451497/135689384-3e6caad2-88af-4783-91d9-7b288d152b63.png)
<br>
![Install 7](https://user-images.githubusercontent.com/91451497/135689386-b60ac838-6661-4819-9b7f-abadeccacbbf.png)
<br>Konfigurasi selanjutnya adalah Setting SSH serta SSL. Jika tidak terlalu paham maksudnya saya sarankan untuk default saja. Saya disini setting Default semua
![Install 8](https://user-images.githubusercontent.com/91451497/135689388-3f156d38-fcaf-4e3a-a19a-c97f44b89c09.png)
<br>Gambar di atas adalah Experimental Configuration. Mungkin ini ditujukan untuk yang membutuhkan. 
![Install 9](https://user-images.githubusercontent.com/91451497/135689392-31499b6b-3250-4684-9bcb-f4610db24c64.png)
<br>Proses Instalasi
<br>
![Install 10](https://user-images.githubusercontent.com/91451497/135689393-ea56d0aa-92ef-4135-8da1-7f9fdd945791.png)
<br>Instalasi Selesai. Disarankan untuk Restart PC atau Device.