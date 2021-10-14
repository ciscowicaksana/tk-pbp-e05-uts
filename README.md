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
Pada era COVID seperti sekarang perjalanan antar daerah menemui banyak restriksi dan regulasi. Namun, bukan berarti perjalanan antar daerah harus dihentikan sepenuhnya. Banyak kehidupan orang yang bergantung dari kedatangan para pendatang. Oleh karena itu diperlukan suatu cara agar perjalanan dapat dilakukan dengan tetap memenuhi protokol kesehatan yang telah ditetapkan oleh pemerintah secara efektif. 
Aplikasi kami hadir agar memudahkan baik pihak pemerintah daerah maupun pengunjung yang baru datang ke daerah yang dituju. Aplikasi ini berfungsi sebagai pusat integrasi baik administrasi data pengunjung beserta tempat penting seperti penginapan untuk melakukan karantina dan tempat yang menyediakan vaksin bagi pengunjung, juga sarana pendaftaran bagi para pengunjung ke daerah tersebut dan pendaftaran ke penginapan karantina dan tempat vaksin.
Ketika mengakses aplikasi kami pengguna pertama kali akan dihadapkan dengan menu autentikasi berupa login atau daftar akun baru yang kemudian akan memberikan mereka authorization seberapa banyak yang dapat mereka lakukan pada aplikasi kami. Kemudian berdasarkan authorization yang telah diberikan, pengguna jika merupakan seorang admin pemerintah dapat menambahkan data baru tempat karantina dan vaksin yang tersedia di suatu daerah. Sementara untuk seorang pengunjung setelah mendapatkan authorizationnya, ia akan diarahkan untuk mendaftar agar dirinya teregistrasi pada daerah tersebut melalui sebuah form pendaftaran. Jika pada form pendaftaran tersebut ditemukan bahwa sang pengunjung sudah melakukan vaksinasi maka mereka akan langsung ditujukan untuk memilih dan mendaftar ke tempat karantina yang tersedia. Jika belum melakukan vaksinasi maka pengunjung akan terlebih dahulu diarahkan untuk mendaftar ke tempat vaksinasi yang tersedia. 


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