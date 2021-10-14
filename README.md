# tk-pbp-e05-uts
### Tugas Kelompok Pemrograman Berbasis Platform UTS Kelompok E05 TA 2021-2022

Anggota Kelompok
1. Cisco Salya Wicaksana (2006596604)
2. Arga Christian Roymansa (2006596554)
3. Farel Musyaffa Arya Putra Majesta (2006596472)
4. Achmad Hafiz (2006536681)
5. Sultan Fahrezy Syahdwinata Nugraha (2006533811)
6. Muhammad Rifqi Praditya (2006596346)

Link Heroku App : https://git.heroku.com/tk-pbp-e05-uts.git

**Ide Aplikasi**
Pada era COVID seperti sekarang perjalanan antar daerah menemui banyak restriksi dan regulasi. Aplikasi kami hadir agar memudahkan baik pihak pemerintah daerah ataupun pengunjung yang baru datang ke daerah yang dituju. Aplikasi ini berfungsi sebagai pusat integrasi baik administrasi data pengunjung beserta tempat penting seperti penginapan untuk melakukan karantina dan tempat yang menyediakan vaksin bagi pengunjung, juga sarana pendaftaran bagi para pengunjung ke daerah tersebut dan pendaftaran ke penginapan karantina dan tempat vaksin.

Ketika mengunjungi aplikasi ini 

**Persona**
Daftar Modul Models : Account (Name, Password, etc); Lokasi (Rumah Sakit/Hotel Karantina/Lokasi Vaksin) Modules: Login, Bikin Akun, Daftar Vaksin, Daftar Karantina

Setelah setahun lebih melaksanakan karantina dan social distancing, A merasa bosan dan ingin pergi ke tempat-tempat wisata untuk refreshing. A mengerti mengenai pentingnya vaksinasi dalam mencegah penyebaran Covid-19, dan ia juga peduli mengenai protokol kesehatan dalam melaksanakan pariwisata. A mencari suatu website yang dapat membantu dia melaksanakan wisata, serta dapat menjaga dirinya dari bahayanya penyebaran Covid-19.

Dengan protokol kesehatan yang dilaksanakan selama pandemi, bisnis pariwisata mengalami kemunduran yang besar. Sekarang, pihak pemerintah daerah ingin merevitalisasi perokonomian daerah, termasuk dalam sektor pariwisata, serta mengontrol laju penyebaran Covid-19. Oleh karena itu, pemerintah mencari berbagai macam solusi yang dapat membantu pihak pemerintahan daerah dalam mengejar dua tujuan tersebut.
=======

**Daftar Modul**
Models
- *Account* (Name, Password, etc)
- Lokasi (Rumah Sakit/Hotel Karantina/Lokasi Vaksin)

Modules
- *Create Account*

    Berisi nama lengkap, *e-mail*, *Account ID*, *password*, dan tanggal lahir.

- *Login*

    Memintakan *Account ID* (atau *e-mail*) dan *password* yang sudah terdaftar.
    Memiliki pilihan [Lupa *password*]

- Lupa *password*

    Memintakan *e-mail* yang sudah terdaftar.

- Daftar Vaksin

    Memberikan daftar pilihan tanggal dan lokasi vaksinasi yang tersedia.

- Daftar Karantina

    Memberikan daftar pilihan tanggal dan lokasi karantina yang tersedia.