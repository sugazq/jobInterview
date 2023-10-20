![My Products](https://github.com/sugazq/jobInterview/assets/115863742/819558e6-14d8-481f-a093-93ab2f1677a0)## 1.1 Latar Belakang

Online shop semakin berkembang melalui internet bahkan sekarang segala sesuatu pun menjadi praktis. Melalui perubahan gaya hidup yang terjadi disini saya berinisiatif untuk membuat sebuah toko online/e-commerce yang bertujuann untuk mempermudah seseorang ketika ingin berbelanja. Bahkan dengan toko online kita tidak hanya mencakup daerah sekitar saja tetapi juga luar daerah bahkan mencakup internasional yang tentunya ini seharusnya lebih efektif untuk menyebarluaskan produk yang kita jual.

Berbelanja secara online saat ini sudah menjadi trend modern yang dinikmati oleh sebagian besar masyarakat, karena mampu menarik dan menggoda bagi setiap masyarakat. Karena berbelanja tidak bisa lepas dari diri kehidupan kita, hampir tidak ada masyarakat yang tidak menyukai belanja, apalagi masyarakat modern yang sudah pasti kebanyakan memiliki internet. Hal ini yang menjadi alasan saya untuk membuat sebuah website e-commerce.

## 1.2. Deksripsi Teknologi Informasi

Pada pembuatan aplikasi kali ini saya menggunakan beberapa teknologi informasi diantaranya :
1. Database menggunakan ***Mysql*** untuk melakukan pengelolaan data pada website yang saya buat,
2. Bagian Frontend saya menggunakan beberapa kombinasi seperti ***CSS***, ***BOOTSTRAP***, dan ***JAVASCRIPT***,
3. Bagian Backendnya saya menggunakan PHP dibarengi dengan frameworknya yaitu ***LARAVEL***,
4. Untuk Design awal aplikasinya saya menggunakan ***FIGMA***,
5. Untuk Membuat programnya saya menggunakan aplikasi ***Visual Studio Code***. 

## 1.3. Branding

- Merk: Rstore
- Tagline: "Gaya Hidup dalam Satu Tempat"
- Campaign:  Tempat yang menggabungkan seluruh aspek gaya hidup Anda dalam satu tempat yang nyaman dan inspiratif. Kami yakin bahwa gaya -hidup Anda adalah refleksi dari siapa Anda, dan kami siap membantu Anda menjalani hidup yang lebih baik dan berwarna.
- Target user:
    - Usia 12+
    - Seorang yang senang up to date
    - Seorang yang senang mengeksplorasi hal baru
    - Seorang yang ingin memiliki suasana baru
    - Seorang yang ingin memiliki barang berkualitas
- User experience theme:
    - Sederhana
    - Konten mudah terbaca
    - Profesionalisme
    - warna: warna putih memiliki kesan kesederhanaan dan bersih dibalut aksen biru juga dapat memberikan kesan kepercayaan kepada pengguna
    - Inspirasi desain : ![Plant Shop Thumbnail](https://github.com/sugazq/jobInterview/assets/115863742/c86c80e6-201d-436b-bb14-3f4f9bd45a82)



## 2. User Story

sebagai | saya ingin bisa | sehingga | Prioritas
---|---|---|---
pengguna | melihat daftar produk tersedia | bisa memilih produk yang tersedia disetiap toko | ⭐⭐⭐⭐⭐
pengguna | mencari produk | bisa memudahkan saya dalam menemukan produk yang sedang dicari | ⭐⭐⭐⭐⭐
pengguna | memiliki keranjang | bisa menambahkan produk ke keranjang belanja saya | ⭐⭐⭐⭐⭐
pengguna | melihat keranjang | bisa melihat daftar produk yang telah saya tambahkan ke keranjang belanja | ⭐⭐⭐⭐⭐
pengguna | memasukan alamat | bisa  menentukan alamat pengiriman paket  | ⭐⭐⭐⭐⭐
pengguna | membeli produk | bisa  membawa pulang produk yang dipilih  | ⭐⭐⭐⭐⭐
pengguna | melihat detail produk | bisa  melihat produk yang dipilih secara menyeluruh  | ⭐⭐⭐⭐
pengguna | menghapus produk dari keranjang | bisa  diganti dengan produk lain dan tidak menumpuk  | ⭐⭐⭐⭐
pengguna | melihat ringkasan pesanan | sebelum mengkonfirmasi pembelian bisa dilakukan cek ulang | ⭐⭐⭐
pengguna | mendapatkan notif pesanan | bisa mengetahui pesanan sudah diproses atau belum | ⭐⭐⭐
pengguna | melihat reveiw produk | bisa melihat feedback dari yang sudah pernah pesan | ⭐⭐⭐


## 3. Struktur Data

Cara membuat aneka macam bentuk grafik menggunakan mermaid.js bisa lihat di [https://mermaid.js.org/syntax/entityRelationshipDiagram.html](https://mermaid.js.org/syntax/entityRelationshipDiagram.html) 

```mermaid
erDiagram
    RUJAK ||--o{ SAYUR : tersusun
    PEMBELI ||--|{ RUJAK : beli
```

## 4. Arsitektur Sistem

```mermaid
flowchart TD
    id1[(Database: MySQL)] <--> id2[Aplikasi Web Backend: Javascript - Laravel] <--> id3[Web Server: Javascript - Laravel]  
```

## 5. Teknologi, Library, dan Framework

Untuk teknologi pendukung saya menggunakan Visual Studio Code Sedangkan dalam pemrograman saya menggunakan Framework Laravel

## 6. Desain User Experience dan User Interface

# Design UI & UX Menggunakan Figma
## Link Figma
> https://www.figma.com/file/3W3UI6PfdxKsZ4kcWn42hB/RStore?type=design&node-id=22%3A489&mode=design&t=1iLHJnMXjgig2YmL-1
- **Landing Page**
> ![Landing](https://github.com/sugazq/jobInterview/assets/115863742/3fdf0923-2d2c-4e58-8630-0a3c22be1972)
- Sign **In**
> ![Sign In](https://github.com/sugazq/jobInterview/assets/115863742/55ec2662-a3ea-4e03-9460-28f8802b07ee)
- **Dashboard**
> ![Dashboard](https://github.com/sugazq/jobInterview/assets/115863742/1b5e5688-dd0b-4bc6-9c2e-11502b301676)
- **Admin Page**
> ![My Products](https://github.com/sugazq/jobInterview/assets/115863742/0fa7648e-185e-4922-b863-2f71f9e9e013)




## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini
