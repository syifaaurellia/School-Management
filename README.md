# School-Management

## Anggota Kelompok <br>

| Nama                      | NIM       | Kelas     | Mata Kuliah                 |
| ------------------------- | --------- | --------- | --------------------------- |
| Syifa Aurellia Rahma      | 312210009 | TI.22.A1  | Object Oriented Programming |
| Tiara Putri               | 312210064 | TI.22.A1  | Object Oriented Programming |
| Fathia Wardah S.Djawas    | 312210196 | TI.22.A1  | Object Oriented Programming |
| Aas Novitasari            | 312210167 | TI.22.A1  | Object Oriented Programming |


## Daftar Isi <br>

| No  | Description             | Link                                                    |
| --- | ----------------------- | ------------------------------------------------------- |
| 1   | Introduction            | [Click Here](#introduction)                             |
| 2   | Fitur-fitur Website     | [Click Here](#fitur-fitur-website) |
| 3   | What is used            | [Click Here](#what-is-used)                            |
| 4   | How to run this project | [Click Here](#how-to-run-this-project)                  |

### Introduction
**Website SchoolManagement adalah sistem platform inovatif yang didesain untuk memudahkan pengelolaan sekolah secara efisien dan terpadu.** Dengan School Management, website SchoolManagement membawa pengalaman pendidikan ke tingkat yang lebih tinggi, mendukung efektivitas, transparansi, dan kemudahan akses dalam mengelola berbagai aspek kegiatan sekolah seperti administrasi sekolah, manajemen siswa, keuangan dan lain-lain.

Website SchoolManagement yang dibuat dengan **Python**, **Django**, dan **sqlite** memiliki beberapa kelebihan, yaitu :
> Tampilan website yang mudah dipahami dan Transparansi

> Komunikatif dan Efektivitas

> Lebih cepat dan efisien

> Interaktif


Website ini menggunakan database **db.sqlite3** yaitu sebuah file database yang umumnya digunakan oleh aplikasi berbasis Python yang menggunakan SQLite sebagai sistem manajemen basis data (DBMS). SQLite adalah library C yang memberikan fungsi lengkap sebuah basis data SQL tanpa memerlukan server terpisah dan pengaturan konfigurasi yang kompleks. SQLite adalah DBMS self-contained yang dapat digunakan dengan mudah dan ringan. Dalam konteks Django sebuah framework web Python, **db.sqlite3** biasanya muncul sebagai file database default ketika kita membuat proyek baru. Django menggunakan SQLite sebagai database default karena kemudahan konfigurasi dan kecocokan dengan banyak proyek kecil hingga menengah. 

### Fitur-fitur website:

> **Admin**
- Admin dapat mendaftarkan akun mereka sendiri tanpa persetujuan dari pihak lain. Setelah akun berhasil dibuat, admin dapat melakukan login untuk mengakses sistem.

- Admin dapat mengelola jumlah siswa dan jumlah guru yang ingin mendapatkan pekerjaan/penerimaan di sekolahnya.

- Admin dapat menyetujui dan menghapus/membatalkan permintaan pendaftaran siswa/guru.

- Admin dapat memperbarui detail siswa/guru mana pun.

- Admin dapat mengumumkan pemberitahuan.


> **Guru**

- Guru akan melamar/mendaftar pekerjaan. Jika terpilih maka akun akan dibuat dan disetujui oleh admin.

- Guru dapat mengakses dashboard website SchoolManagement.

- Guru dapat mencatat kehadiran kelas mana pun dan melihat kehadiran mereka nanti.

- Guru dapat mempublikasikan/mengumumkan pemberitahuan kepada siswa seperti penyerahan tugas.


> **Siswa**

- Siswa akan mengambil penerimaan/pendaftaran.

- Siswa dapat mengakses dashboard website SchoolManagement, jika akun nya sudah disetujui oleh admin.

- Siswa dapat melihat detail seperti kehadiran.


### What is used

1. **Django**
   
   Django adalah sebuah framework web berbasis Python yang dirancang untuk mempermudah pengembangan aplikasi web. Django menyediakan sejumlah alat dan fitur bawaan untuk mempercepat pembuatan aplikasi web dengan
   menyederhanakan tugas-tugas umum.

   Dalam sistem SchoolManagement, Django digunakan untuk membuat struktur aplikasi web, membuat model database dan mempermudah penggunaan aplikasi web.


2. **Python**

    Python adalah bahasa pemrograman tingkat tinggi yang sangat populer, dirancang untuk menyediakan sintaksis yang jelas dan mudah dibaca. Dalam sistem OnlineQuiz, Python digunakan sebagai bahasa pemrograman utama untuk membuat aplikasi web.


3. **SQLite**
   
   
   SQLite adalah sistem manajemen basis data (DBMS) yang bersifat serverless, self-contained, dan bersifat transaksional. Ini berarti SQLite tidak memerlukan server terpisah untuk mengelola basis data, dan seluruh basis
   data disimpan dalam satu file tunggal yang dapat diakses langsung dari program aplikasi.

   Dalam sistem SchoolManagement, SQLite digunakan sebagai database untuk menyimpan data pengguna, jumlah siswa, guru dan kelas, data kehadiran dan lain-lain.


4. **VSCode**


   Untuk mengedit code, kami menggunakan Visual Studio Code (VSCode). Visual Studio Code (VSCode) adalah editor kode sumber sumber terbuka dan ringan yang dikembangkan oleh Microsoft. Visual Studio Code sering digunakan oleh para pengembang perangkat lunak untuk proyek-proyek pengembangan perangkat lunak, pemrograman web, dan pengembangan aplikasi lintas platform. Kelebihan dalam ekstensibilitas dan ekosistem ekstensi yang kaya menjadikannya pilihan populer di komunitas pengembangan perangkat lunak.
   

6. **Bootstrap**


   Bootstrap adalah sebuah kerangka kerja (framework) sumber terbuka yang digunakan untuk pengembangan situs web dan aplikasi seluler. Diciptakan oleh tim pengembang Twitter, Bootstrap menyediakan kumpulan alat dan gaya desain yang memudahkan pengembang dalam membuat tata letak yang responsif dan menarik secara visual.


7. **jQuery**


   jQuery adalah sebuah pustaka JavaScript yang ringan dan cepat yang menyederhanakan manipulasi dokumen HTML, penanganan peristiwa, animasi, dan berbagai tugas pengembangan web lainnya. Dengan menyediakan antarmuka yang mudah digunakan dan lintas peramban, jQuery membantu pengembang dalam membuat situs web yang responsif dan dinamis dengan lebih efisien.

   

### How To Run This Project

- Unduh Python dari situs resminya : https://www.python.org/downloads/
  
- Saat instalasi, pastikan untuk memberi centang pada kotak "Add Python to PATH". Ini akan memudahkan kita dalam menjalankan Python melalui perintah di terminal.
  
- Open Terminal (cmd) dan Jalankan perintah berikut:

```
 python -m pip install -r requirements.txt 
```

- Silahkan clone repository di bawah ini atau download ZIP, kemudian extract file ZIP tersebut ke sebuah folder.

```
https://github.com/syifaaurellia/SchoolManagement.git
```
  
- Pindah ke folder project di terminal. Kemudian jalankan perintah berikut :
  
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```

- Sekarang masukkan URL berikut di Browser yang terpasang di PC anda (Chrome, Firefox, Edge dan lain-lain)

```
http://127.0.0.1:8000/
```

- Setelah itu web tampilan project django sudah berjalan dan tampil pada browser anda.


## Semoga Bermanfaat, Terima Kasih 

### - Kelompok 5 -
