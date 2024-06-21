# Pengenalan BLKK Al-Ittifaq: Website Dinamis dengan Golang

## CHAPTER 1: PENDAHULUAN

### 1.1 WEBSITE BERBASIS CLOUD

Website berbasis cloud adalah jenis website yang menggunakan layanan cloud computing untuk menyediakan infrastruktur dan platform yang diperlukan untuk menjalankan aplikasi web. Cloud computing menawarkan berbagai keuntungan, termasuk skalabilitas, fleksibilitas, ketersediaan tinggi, dan pengurangan biaya operasional. Dengan menggunakan cloud, perusahaan dapat dengan mudah menyesuaikan sumber daya mereka sesuai dengan kebutuhan tanpa harus menginvestasikan banyak uang dalam infrastruktur fisik [Mell & Grance, 2011].

Layanan cloud computing biasanya disediakan oleh penyedia layanan seperti Amazon Web Services (AWS), Google Cloud Platform (GCP), dan Microsoft Azure. Layanan ini mencakup berbagai komponen seperti server virtual, penyimpanan, jaringan, dan basis data yang semuanya dapat dikelola melalui internet. Dengan demikian, pengembang dapat fokus pada pengembangan dan peningkatan aplikasi mereka tanpa khawatir tentang manajemen infrastruktur yang mendasarinya [Armbrust et al., 2010].

Cloud computing juga mendukung model pembayaran berbasis penggunaan (pay-as-you-go), yang berarti perusahaan hanya membayar untuk sumber daya yang mereka gunakan. Ini sangat berguna untuk mengelola anggaran IT dan mengurangi biaya overhead [Armbrust et al., 2010].

### 1.2 PENGENALAN GOLANG

Golang, atau yang dikenal juga sebagai Go, adalah bahasa pemrograman yang dikembangkan oleh Google. Bahasa ini pertama kali dirilis pada tahun 2009 dan dirancang untuk memenuhi kebutuhan pemrograman modern, terutama dalam hal pengembangan aplikasi yang memerlukan kinerja tinggi, efisiensi, dan skalabilitas [Donovan & Kernighan, 2015].

Golang memiliki sintaks yang sederhana dan mudah dipelajari, serta mendukung concurrency sebagai fitur utama. Dengan model concurrency yang kuat melalui goroutines dan channels, Golang memungkinkan pengembang untuk menulis aplikasi yang dapat menangani banyak tugas secara bersamaan tanpa mengorbankan kinerja [Cox-Buday, 2017].

Keunggulan lain dari Golang adalah kompiler yang cepat dan dukungan untuk kompilasi statis, yang menghasilkan binary executable yang efisien dan dapat dijalankan di berbagai platform tanpa ketergantungan tambahan. Hal ini membuat Golang sangat cocok untuk pengembangan aplikasi web, sistem terdistribusi, dan layanan microservices [Donovan & Kernighan, 2015].

Selain itu, komunitas Golang yang aktif dan dukungan dari Google memastikan bahwa bahasa ini terus berkembang dengan fitur-fitur baru dan peningkatan performa [Donovan & Kernighan, 2015].

1.3 PENGENALAN MONGODB
MongoDB adalah basis data NoSQL yang bersifat open-source dan didesain untuk menyimpan data dalam format dokumen JSON (JavaScript Object Notation). Dikembangkan oleh MongoDB Inc., basis data ini dirancang untuk menangani volume data yang besar, memberikan performa tinggi, serta menawarkan fleksibilitas dalam pengelolaan data yang tidak terstruktur [Chodorow, 2013].

Tidak seperti basis data relasional tradisional yang menggunakan tabel dan baris, MongoDB menggunakan koleksi dan dokumen. Setiap dokumen dalam MongoDB adalah sebuah objek JSON yang dapat memiliki struktur yang bervariasi. Hal ini memungkinkan penyimpanan data yang kompleks dan dinamis tanpa memerlukan skema yang kaku [Chodorow, 2013].

MongoDB mendukung berbagai fitur canggih seperti replikasi untuk ketersediaan tinggi, sharding untuk skalabilitas horizontal, dan indexing untuk query yang cepat [Banker, 2011]. Dengan dukungan untuk berbagai bahasa pemrograman dan platform, MongoDB menjadi pilihan populer untuk pengembangan aplikasi web modern yang memerlukan penyimpanan data yang scalable dan fleksibel [Banker, 2011].

Penggunaan MongoDB sangat luas dalam berbagai aplikasi, termasuk analitik big data, manajemen konten, katalog produk, dan layanan lokasi. MongoDB juga dikenal karena kemampuannya untuk menangani data yang terdistribusi di beberapa server, sehingga memastikan ketersediaan data dan toleransi kesalahan yang tinggi [Chodorow, 2013].

## CHAPTER 2 PERSIAPAN LINGKUNGAN PENGEMBANGAN

### 2.1 INSTALASI VISUAL STUDIA CODE

Visual Studio Code adalah sebuah
teks editor ringan dan handal yang dibuat
oleh Microsoft untuk sistem operasi
multiplatform, artinya tersedia juga untuk
versi Linux, Mac, dan Windows.
langkah-langkah untuk menginstalnya:

1. Kunjungi situs resmi Visual Stusio Code. Anda bisa menikuti tautan ini https://code.visualstudio.com/
2. Pilih versi yang sesuai dengan sistem operasi Anda (Windows, macOS, atau Linux).

### 2.2 INSTALASI GOLANG

Golang adalah bahasa pemrograman yang akan digunakan untuk mengembangkan backend website.
Cara instalasinya berbeda-beda untuk tiap jenis sistem operasi. Panduan instalasi Golang sebenarnya sudah disediakan, bisa dilihat di situs officialnya http://golang.org/doc/install#install.

### 2.3 INSTALASI GIT

Git adalah sistem kontrol versi yang akan membantu Anda mengelola kode sumber proyek. Berikut adalah langkah-langkah untuk menginstalnya:
1.. Download Git: kunjungi situs resmi Git https://www.git-scm.com/downloads 2. Pilih versi yang sesuai dengan sistem operasi Anda.

## CHAPTER 3 MENYIAPKAN DATABASW DENGAN MONGODB

### MEMBUAT AKUN MONGODB

## Chapter 4: Membuat Proyek

### 4.1 Inisialisasi Proyek

### 4.2 Struktur Direktori Proyek

### 4.3 Menggunakan Modul dan Paket

## Chapter 6: Pengembangan Frontend

### 6.1 PMembuat Tampilan Dasar dengan HTML dan CSS

### 6.2 Interaksi Dinamis dengan JavaScript

## Chapter 6: Pengembangan Backend

### 6.1 Membuat Server dengan net/http

### 6.2 Implementasi Routing Dasar

### 6.3 Operasi CRUD dengan MongoDB
