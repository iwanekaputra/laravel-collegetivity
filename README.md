<h1 align="center">Selamat datang di Collegetivity! 👋</h1>

![Collegetivity Preview](https://github.com/iwanekaputra/laravel-collegetivity/blob/main/1.png?raw=true)

<p align="center">
<img src="https://img.shields.io/github/issues/iwanekaputra/laravel-collegetivity?style=flat-square">
<img src="https://img.shields.io/github/stars/iwanekaputra/laravel-collegetivity?style=flat-square"> 
<img src="https://img.shields.io/github/forks/iwanekaputra/laravel-collegetivity?style=flat-square">
<img src="https://img.shields.io/github/license/iwanekaputra/laravel-collegetivity?style=flat-square">
<img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=flat-square">
<img src="https://img.shields.io/github/followers/syauqi.svg?style=flat-square&label=Follow&maxAge=2592000">
</p>

### 🎓 Tentang Collegetivity
Website ini berperan sebagai 'workspace' yang ditujukan bagi para mahasiswa untuk menjadi lebih produktif dan terorganisir. Mempunyai banak fitur seperti mengorganisir jadwal, tugas, to-do list dan banyak lagi.

**Aplikasi ini dibuat dengan banyak kekurangan oleh karena itu mohon maaf jika terdapat banyak bug dan banyak hal yang dibuat dengan tidak menggunakan 'best practice'**


### ✨ Fitur yang Tersedia
- Landing page dan berbagai macam halaman yang bisa anda kustomisasi
- Fitur pengelolaan data akademik [jadwal pelajaran, tulisan & catatan, file manager & galeri serta foto]
- Fitur utility bagi para mahasiswa [to-do list, kalender & bookmark]
- Fitur penunjang produktifitas [whiteboard, audio relaxation, pomodoro timer & virtual meeting]
- Resources [journal & e-book]

### 🏠 Demo & Overview
Halaman demo dapat kalian akses di https://collegetivity-campus.herokuapp.com/ kalian cukup daftar dengan mengklik button di kanan atas masukan identitas dan voila selamat mencoba!


### 📆 Release Date
- v0.5.0 : 20 februari 2022


------------

 ### 🐱‍💻 Menjalankan di Localhost
	
	
Jalankan command git clone seperti contoh dibawah

`git clone https://github.com/iwanekaputra/laravel-collegetivity.git`

Kemudian jalankan command composer install, ini akan menginstall resources yang laravel butuhkan

`composer install`

Lakukan copy .evn dengan cara ketik command seperti dibawah 

`copy .env.example .env` atau `cp .env.example .env`

Generate key juga jangan lupa dengan command dibawah

`php artisan key:generate`

Jangan lupa migrate database dengan cara membuat database di phpmyadmin atau aplikasi lainnya yang kalian pakai, lalu jangan lupa untuk mengganti variable DB_DATABASE di file .env yang di folder project

`php artisan migrate`

Lalu jalankan aplikasi kalian dengan command dibawah

`php artisan serve`


------------

### 💾 Syarat yang Wajib Ada 
- PHP 8 & Web Server [XAMPP, LAMPP, MAMP]
- Web Browser [Chrome, Firefox, Safari & Opera]
- Internet [Karena menggunakan banyak CDN]
- Composer & Laravel 8

## 🤝 Contributing
Contributions, issues and feature requests sangat saya apresiasi karena aplikasi ini jauh dari kata sempurna. Jangan ragu untuk pull request dan membuat perubahan pada project ini.

**Berhubung Project ini saya selesaikan sendiri, namun banyak fitur dan banyak hal yang bisa diperbaiki maka bantuan kalian sangat saya apresiasi**


## 📝 License
- Copyright © 2022 IWAN EKA PUTRA
- **Collegetivity is open-sourced software licensed under the MIT license**


------------
**Made with ❤️ IWAN EKA PUTRA**
