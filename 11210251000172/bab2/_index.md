# LANDASAN TEORI

## Teknologi Informasi 

Menurut Bambang Warsita (2008:135) teknologi informasi adalah sarana dan prasarana (hardware, software, useware) sistem dan metode untuk memperoleh, mengirimkan, mengolah, menafsirkan, menyimpan, mengorganisasikan, dan menggunakan data secara bermakna. Hal yang sama juga diungkapkan oleh Lantip dan Riyanto (2011:4) teknologi informasi diartikan sebagai ilmu pengetahuan dalam bidang informasi yang berbasis komputer dan perkembanganya sangat pesat. Hamzah B. Uno dan Nina Lamatenggo (2011:57) juga mengemukakan teknologi informasi adalah suatu teknologi yang digunakan untuk mengolah data. Pengolahan itu termasuk memproses, mendapatkan, menyusun, menyimpan, memanipulasi data dalam berbagai cara untuk menghasilkan informasi yang berkualitas, yaitu informasi yang relevan, akurat, dan tepat waktu.

## High Availability

Kebutuhan akan kecepatan dan efisiensi internet yang terus meningkat mendorong perusahaan untuk memodernisasi strategi pemasaran mereka, baik seseorang yang membayar tagihannya, pemberi kerja yang menyimpan dokumen karyawannya, atau rumah sakit yang mengakses catatan kesehatan pasien secara online, semuanya membutuhkan aplikasi web yang siap digunakan hanya dengan menekan sebuah tombol. studi beban web yang sedang berlangsung menunjukkan bahwa di bawah beban yang berat, ketersediaan dan kinerja situs web menjadi sangat berkurang (Backlinko, 2018). Untuk mengurangi beban pada aplikasi web, perlu untuk meningkatkan efisiensi dan kecepatannya. 

Solusi penyeimbangan beban membantu memenuhi permintaan layanan yang meningkat secara lebih efisien dan menjalankan fungsi-fungsi berikut: 

a. Effectively mendistribusikan permintaan pelanggan atau beban jaringan ke beberapa server. 
b. Ensures ketersediaan dan keandalan server dengan mengirimkan permintaan hanya ke server yang aktif pada saat ini.
c. Flexibly menambah atau menghapus server ketika permintaan membutuhkannya.

Algoritma penyeimbangan beban ini dapat menggunakan tiga bentuk pengendalian yang berbeda: terpusat, terdistribusi, atau semi terdistribusi.  Strategi transfer menggunakan:

a. Least Connections adalah solusi, ketika memeriksa server mana yang memiliki jumlah koneksi paling sedikit yang terbuka pada saat itu dan mengirim lalu lintas ke server tersebut, diasumsikan bahwa semua koneksi membutuhkan daya pemrosesan yang kurang lebih sama; 
b. Weighted Least Connections adalah solusi di mana administrator memberikan bobot yang berbeda untuk setiap server, dengan asumsi bahwa beberapa server dapat memproses lebih banyak koneksi daripada yang lain. 

Strategi informasi diterapkan dalam solusi waktu respons tertimbang, di mana waktu respons rata-rata dari setiap server dan jumlah koneksi yang terbuka menentukan kemana harus mengirim aliran data.

## Perpustakaan

Perpustakaan adalah institusi pengelola koleksi karya tulis, karya cetak, dan/atau karya rekam secara profesional dengan sistem yang baku guna memenuhi kebutuhan pendidikan, penelitian, pelestarian, informasi, dan rekreasi para pemustaka (UU No. 43 Tahun 2007). Dalam konteks modern, perpustakaan bukan lagi sekadar tempat penyimpanan fisik, melainkan pusat akses informasi digital yang harus tersedia secara terus-menerus (high availability).

Menurut Reitz (2004), perpustakaan digital merupakan perpustakaan di mana sebagian besar koleksinya tersedia dalam format yang dapat dibaca mesin (machine-readable format), yang diakses melalui komputer dan jaringan. Keberhasilan manajemen perpustakaan modern sangat bergantung pada sistem otomasi yang memastikan setiap materi perpustakaan tercatat, aman, dan dapat ditemukan kembali (retrieved) dengan cepat. Hal ini sejalan dengan pendapat Lasa Hs (2009) yang menyatakan bahwa perpustakaan merupakan suatu sistem informasi yang mengintegrasikan sumber daya manusia, sarana prasarana, dan teknologi informasi untuk mendayagunakan koleksi bagi masyarakat.

Seiring dengan meningkatnya kebutuhan akses daring, manajemen koleksi digital dalam perpustakaan memerlukan infrastruktur teknologi yang stabil. Sesuai dengan prinsip akuntabilitas dan layanan publik, perpustakaan harus menjamin bahwa sistem informasi yang digunakan mampu menangani lonjakan beban kerja (workload) pemustaka tanpa mengalami kegagalan akses (downtime). Oleh karena itu, penerapan strategi teknologi seperti load balancing pada server pangkalan data perpustakaan menjadi sangat krusial untuk menjaga performa layanan perpustakaan digital di era keterbukaan informasi saat ini.

## SLiMS

Senayan Library Management System atau SLiMS adalah perangkat lunak sistem manajemen perpustakaan (Library Management System) sumber terbuka yang dirancang untuk memenuhi kebutuhan otomasi perpustakaan, mulai dari skala kecil hingga besar. Menurut Wardiana (2011), SLiMS merupakan solusi teknologi informasi yang komprehensif untuk mengelola pangkalan data bibliografi dan kegiatan sirkulasi secara efisien. Sistem ini dibangun menggunakan bahasa pemrograman PHP dan pangkalan data MySQL, yang memungkinkan fleksibilitas tinggi dalam pengembangan dan integrasi infrastruktur.

Sebagai platform berbasis web, SLiMS memiliki fitur-fitur utama yang mendukung operasional perpustakaan modern, antara lain:
a. OPAC (Online Public Access Catalog): Antarmuka publik untuk pencarian koleksi secara daring.
b. Manajemen Sirkulasi: Modul untuk proses peminjaman dan pengembalian koleksi.
c. Manajemen Bibliografi: Standar penginputan data buku menggunakan format metadata yang baku.
d. Keanggotaan: Pengelolaan data pemustaka secara terpusat.


Menurut Mulyadi (2016), implementasi SLiMS bertujuan untuk meningkatkan kualitas layanan perpustakaan melalui percepatan temu kembali informasi (information retrieval). Namun, karena SLiMS diakses melalui protokol HTTP/HTTPS, performa sistem ini sangat bergantung pada stabilitas server web dan database. Ketika jumlah akses pemustaka ke halaman OPAC meningkat tajam, server tunggal yang menjalankan SLiMS berisiko mengalami overload. Oleh karena itu, dalam konteks ketersediaan tinggi (High Availability), infrastruktur SLiMS memerlukan mekanisme distribusi beban seperti load balancing untuk memastikan layanan perpustakaan tetap dapat diakses tanpa kendala teknis (Sutarno, 2020).

