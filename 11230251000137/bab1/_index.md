## BAB 1
### LATAR BELAKANG

Perpustakaan modern saat ini tidak hanya berupa buku fisik, tetapi juga mencakup jurnal, artikel elektronik, dan berbagai sumber informasi digital yang terus berkembang. Untuk memberikan akses yang cepat dan akurat kepada pengguna, perpustakaan harus melakukan katalogisasi bahan pustaka secara sistematis. Katalogisasi merupakan proses penciptaan dan pengorganisasian informasi bibliografis sehingga bahan pustaka dapat diketahui, ditemukan, dan diakses dengan mudah berdasarkan berbagai unsur seperti judul, pengarang, subjek, atau klasifikasi. Sistem catalog ini menjadi fondasi utama dalam layanan informasi perpustakaan karena tanpa katalogisasi, koleksi bahan pustaka akan sulit dipahami dan diambil manfaatnya oleh pengguna. Katalogisasi tradisional biasanya disusun dalam bentuk record yang mencerminkan elemen metadata standar yang kompleks dan saling berelasi satu sama lain. Proses ini menjadi semakin penting di era digital, di mana volume dan ragam bahan pustaka berkembang dengan cepat sehingga membutuhkan sistem penyimpanan yang lebih efisien dan adaptif. Dengan demikian, katalogisasi tidak hanya sebuah aktivitas administratif, tetapi juga merupakan prasyarat bagi layanan informasi yang efektif dan responsif terhadap kebutuhan pengguna perpustakaan.

Secara umum, katalogisasi perpustakaan tradisional sangat bergantung pada sistem penyimpanan data relasional berbasis tabel yang memiliki skema tetap. Model database relasional mensyaratkan struktur kolom, tabel, dan hubungan kunci asing yang rigid, sehingga setiap perubahan struktur data seringkali memerlukan desain ulang skema. Namun dengan meningkatnya kompleksitas data—termasuk metadata kategori baru atau format digital yang tidak terstruktur—sistem relasional konvensional menjadi kurang efisien. Ketika perpustakaan mulai menyimpan data jenis baru seperti e-book, audio, atau materi multimedia, kebutuhan akan fleksibilitas menjadi semakin penting. Hal ini menimbulkan pertanyaan: apakah struktur tabel relasional masih relevan untuk kebutuhan katalogisasi saat ini, atau diperlukan pendekatan baru yang lebih adaptif? Seiring perkembangan teknologi penyimpanan data, model database non-relasional seperti NoSQL semakin dipertimbangkan karena kemampuannya menangani struktur data yang tidak terikat skema. Kebutuhan akan alternatif ini menjadi semakin mendesak seiring semakin kompleksnya kebutuhan layanan perpustakaan modern.

Database sebagai entitas teknologi informasi berperan sebagai penyimpanan terorganisir yang memungkinkan akses, pemutakhiran, dan pengambilan data secara efisien. Secara teknis, database merupakan kumpulan data yang disusun sedemikian rupa sehingga mendukung operasi penyimpanan dan pencarian dalam volume besar secara efektif dan konsisten. Kegunaan database menjadi sangat penting dalam berbagai sistem informasi termasuk e-commerce, manajemen akademik, dan yang paling relevan bagi penelitian ini, katalog perpustakaan. Basis data tradisional seperti MySQL telah digunakan secara luas di banyak lembaga karena kemampuan mereka dalam mengelola transaksi yang konsisten dan terstruktur. Namun karena tuntutan data tidak terstruktur yang semakin besar, database konvensional ini seringkali memerlukan modifikasi skema yang kompleks atau redundansi data untuk dapat mengakomodasi kebutuhan baru. Dalam konteks perpustakaan, metadata yang kerap bersifat semi-terstruktur dan berubah-ubah membuat tantangan ini semakin terkait dengan kebutuhan teknologi penyimpanan yang fleksibel tanpa mengorbankan efisiensi pencarian dan akses.

Teknologi database NoSQL muncul sebagai salah satu solusi untuk tuntutan data yang lebih dinamis dan beragam. NoSQL sendiri mengacu pada kumpulan teknologi database non-relasional yang memungkinkan penyimpanan data dalam format lain selain tabel tradisional, seperti dokumen, key-value, kolom lebarnya luas, atau basis graf. Konsep NoSQL yang fleksibel memungkinkan aplikasi untuk menyimpan data tanpa terlebih dahulu menentukan skema yang kaku, sehingga adaptasi terhadap perubahan struktur data menjadi lebih mudah dilakukan dalam operasi sehari-hari. Salah satu contoh teknologi NoSQL yang paling populer adalah MongoDB, sebuah database dokumen yang menggunakan format BSON (Binary JSON) untuk menyimpan data yang kaya atribut dan hierarkis. Sifat dokumen ini menjadikannya cocok untuk menyimpan objek metadata yang kompleks seperti yang ditemukan dalam katalog bibliografis perpustakaan. Keuntungan fleksibilitas skema ini juga didukung oleh kemampuan MongoDB untuk mengelola query tekstual, indeks, replikasi, dan skalabilitas yang tinggi, membuatnya menarik sebagai kandidat teknologi untuk aplikasi katalog modern.

MongoDB pertama kali diperkenalkan pada tahun 2009 sebagai basis data open-source yang ditujukan untuk penyimpanan data yang tidak terikat oleh struktur tabel relasional tradisional. Seiring waktu, MongoDB telah berkembang menjadi salah satu basis data NoSQL yang paling banyak digunakan di dunia untuk aplikasi yang memerlukan fleksibilitas struktur data dan kemampuan skalabilitas tinggi. Komunitas pengguna yang besar serta dokumentasi yang lengkap juga membantu menjadikan MongoDB populer di kalangan pengembang perangkat lunak dan insinyur database dalam lingkungan aplikasi modern. Teknologi ini memiliki dukungan fitur seperti replikasi data, sharding untuk distribusi beban kerja, serta agregasi kompleks yang memudahkan pengembangan aplikasi berskala besar. Faktor-faktor ini mengindikasikan bahwa MongoDB bukan sekadar alternatif sementara, tetapi potensi arsitektur database masa depan untuk kebutuhan aplikasi data dinamis. Relevansi teknologi dokument-oriented seperti MongoDB dengan katalog perpustakaan yang kompleks semakin penting dalam lingkungan big data yang terus berkembang saat ini.

Data bibliografis dalam konteks akademik sendiri mencakup sekumpulan referensi tertulis yang disusun secara teratur sehingga memudahkan akses dan penelusuran. Secara lebih luas, suatu bibliographic database adalah kumpulan terorganisir dari catatan bibliografis yang mencerminkan karya-karya publikasi seperti artikel, buku, prosiding, laporan, dan lainnya. Kumpulan data ini menyimpan elemen metadata yang kaya seperti penulis, judul, tahun publikasi, subjek, dan kata kunci yang memungkinkan pencarian efektif dan relevan. Struktur metadata yang kompleks dan sering kali tidak seragam ini menjadi tantangan tersendiri dalam perancangan sistem penyimpanan data tradisional karena setiap koleksi dapat memiliki atribut yang berbeda-beda. Di sinilah pendekatan basis data dokument berbasis BSON seperti yang digunakan oleh MongoDB berpotensi menawarkan pendekatan yang lebih adaptif dengan menyimpan setiap record sebagai dokumen tunggal yang merepresentasikan seluruh informasi bibliografis tanpa perlu banyak tabel dan join. Pendekatan ini menjadi semakin signifikan dalam konteks perpustakaan digital saat ini yang tidak hanya menyimpan koleksi cetak, tetapi juga koleksi digital multiformat.

Meski begitu, banyak perpustakaan hingga saat ini masih bergantung pada sistem relasional seperti MySQL atau PostgreSQL untuk kebutuhan katalogisasi bahan pustaka mereka. Ketergantungan ini sebagian besar disebabkan oleh sejarah panjang penggunaan RDBMS dalam sistem informasi sejak awal dikembangkan, serta kebutuhan akan konsistensi tinggi dalam transaksi data. RDBMS juga dikenal kuat dalam menangani data terstruktur dengan aturan yang ketat seperti ACID (Atomicity, Consistency, Isolation, Durability). Namun hal tersebut sering kali tidak mencerminkan kebutuhan metadata perpustakaan yang terus berkembang seiring dengan perubahan standar katalog seperti MARC21, Dublin Core, atau RDA. Ketika standar katalog berkembang, penyesuaian skema dalam RDBMS menjadi pekerjaan yang memakan waktu dan biaya tinggi bagi lembaga perpustakaan. Karena sifat rigid ini, perubahan kebutuhan metadata kerap membuat RDBMS menjadi kurang responsif terhadap tuntutan pengembangan sistem layanan perpustakaan modern.

Selain keterbatasan teknis pada skema, katalog perpustakaan juga menghadapi tantangan operasional seperti integrasi data dari berbagai sumber, pencarian teks penuh pada berbagai atribut bibliografis, serta penggabungan metadata dari koleksi lokal dan global. Tantangan ini semakin jelas ketika perpustakaan ingin menyediakan akses langsung kepada pengguna melalui OPAC (Online Public Access Catalog) di mana respons cepat dan relevan menjadi harapan utama pengguna. Dalam konteks ini, kemampuan teknologi database untuk menangani pencarian teks penuh dan indeks dokumen menjadi sangat penting. MongoDB menawarkan fitur indeks teks dan pipeline agregasi yang mampu menyelesaikan beberapa tantangan ini dengan efisien tanpa mengorbankan fleksibilitas struktur data. Penggunaan fitur-fitur ini telah diteliti dalam konteks pengelolaan data akademik dan informasi dinamis lainnya, meskipun belum banyak studi yang secara spesifik membahas penerapan dalam katalog perpustakaan.

### IDENTIFIKASI MASALAH
1. Ketergantungan yang masih kuat pada MySQL untuk katalog perpustakaan
Banyak perpustakaan hingga kini masih menggunakan MySQL atau RDBMS serupa untuk menyimpan record katalog mereka, padahal struktur metadata perpustakaan sering bersifat semi-terstruktur dan berubah-ubah. Model skema tetap dalam RDBMS membuat penyesuaian terhadap kebutuhan metadata baru memerlukan waktu dan sumber daya yang cukup besar. Hal ini juga berdampak pada kebutuhan pengembangan sistem ketika standar katalog berubah atau format data baru muncul. Kemampuan MySQL dalam menangani data tidak terstruktur sangat terbatas dibanding database NoSQL. Kondisi ini menimbulkan pertanyaan tentang sejauh mana MySQL masih relevan dalam konteks katalog modern.

2. Minimnya penelitian penerapan MongoDB dalam katalog perpustakaan
Sejauh kajian pustaka yang ada, belum banyak ditemukan penelitian yang secara eksplisit membahas implementasi MongoDB untuk katalogisasi bahan pustaka. Studi yang tersedia lebih banyak membandingkan MongoDB dengan RDBMS secara umum atau dalam domain lain seperti e-commerce. Karena itu, terdapat gap pengetahuan tentang bagaimana MongoDB dapat diadaptasi untuk kebutuhan katalog perpustakaan secara spesifik. Tanpa penelitian yang membahas aspek ini secara detail, perpustakaan sulit menilai manfaat nyata dari teknologi tersebut. Hal ini membuka peluang penelitian untuk mengisi kekosongan pengetahuan tersebut.

3. Kebutuhan akan fleksibilitas struktur metadata yang tidak terakomodasi baik oleh sistem yang ada
Struktur metadata perpustakaan yang kompleks dan beragam sering kali tidak tertangkap secara efisien oleh skema tabel relasional. Hal ini menyebabkan redundansi data, kebutuhan join yang banyak, serta kompleksitas query yang tinggi. Perubahan standar katalog seperti MARC21 atau Dublin Core memerlukan modifikasi skema yang tidak sederhana dalam RDBMS. Kebutuhan fleksibilitas ini menjadi lebih penting ketika perpustakaan ingin menggabungkan metadata digital yang tidak terstruktur dengan metadata tradisional. Tanpa solusi yang adaptif, perpustakaan menghadapi kesulitan dalam mengembangkan layanan baru kepada pengguna.

### BATASAN MASALAH
Sehubungan dengan identifikasi masalah di atas, penelitian ini dibatasi pada hal-hal berikut untuk memastikan fokus kajian yang lebih tajam:

1. Penerapan MongoDB sebagai database katalog perpustakaan
Penelitian tidak mengkaji seluruh fitur MongoDB, tetapi fokus pada penerapan arsitektur database dokument-oriented dalam konteks menyimpan dan mengelola metadata katalog perpustakaan.

2. Perbandingan aspek katalogisasi antara MongoDB dan model relasional tradisional
Analisis akan dibatasi pada bagaimana MongoDB menangani struktur data katalog dibanding MySQL tanpa mengevaluasi performa teknis secara mendalam seperti benchmark.

3. Fokus pada metadata bibliografis internal perpustakaan
Penelitian tidak mencakup integrasi metadata dari database bibliografis global yang berskala besar seperti OpenAlex atau Web of Science, meskipun implikasi teoritisnya dibahas secara konseptual.

### RUMUSAN MASALAH
Berdasarkan identifikasi dan pembatasan masalah di atas, penelitian ini dirumuskan dalam bentuk pertanyaan ilmiah berikut:

1. Bagaimana penerapan database MongoDB dalam menyimpan dan mengelola katalogisasi bahan pustaka di perpustakaan?

2. Apa kelebihan dan keterbatasan penggunaan MongoDB dibandingkan dengan MySQL dalam konteks katalog perpustakaan?

3. Bagaimana struktur data dokumen dalam MongoDB dapat merepresentasikan metadata perpustakaan dengan lebih fleksibel?

### TUJUAN PENELITIAN
Tujuan utama penelitian ini adalah:

1. Mengkaji penerapan MongoDB untuk katalog perpustakaan
Penelitian bertujuan untuk memahami bagaimana MongoDB dapat diimplementasikan untuk menyimpan dan mengelola metadata katalog secara efektif dan adaptif.

2. Mengidentifikasi kelebihan dan keterbatasan MongoDB terkait katalog perpustakaan
Analisis ditujukan untuk menilai perbedaan antara model dokument-oriented dan model relasional dalam mengelola struktur metadata perpustakaan.

3. Mendeskripsikan struktur data dokumen sebagai representasi metadata katalog
Penelitian akan mengeksplorasi cara merepresentasikan elemen penting katalog perpustakaan secara fleksibel dalam dokumen MongoDB.

### MANFAAT PENELITIAN
Manfaat penelitian ini untuk teoritis dan praktisi sebagai berikut:

#### Manfaat Teoretis
1. Memberikan kontribusi ilmiah dalam bidang Library and Information Science mengenai penerapan teknologi database NoSQL dalam katalog perpustakaan.

2. Menjadi referensi teoritis tentang bagaimana teknologi dokument-oriented dapat mengakomodasi metadata yang kompleks.

3. Menambah kajian akademik terkait adaptasi sistem informasi perpustakaan dengan perkembangan teknologi database terkini.

4. Mendorong penelitian lanjutan di bidang integrasi metadata lain seperti data bibliografis global.

5. Memberikan landasan bagi pengembangan teori database non-relasional dalam domain perpustakaan.

#### Manfaat Praktisi
1. Memberi panduan kepada pengembang sistem perpustakaan tentang alternatif teknologi database yang lebih adaptif.

2. Membantu perpustakaan dalam memilih model database yang sesuai dengan kebutuhan metadata yang dinamis.

3. Mempercepat proses pengembangan OPAC yang responsif terhadap perubahan kebutuhan pengguna.

4. Mengurangi kebutuhan modifikasi skema yang kompleks pada sistem katalog konvensional.

5. Memberikan praktik terbaik terhadap pemanfaatan struktur data dokumen dalam penyimpanan katalog.