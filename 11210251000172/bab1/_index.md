# PENDAHULUAN

## Latar Belakang

Perkembangan teknologi informasi di era modern telah membawa perubahan fundamental pada cara organisasi mengelola infrastruktur komputasi mereka melalui adopsi Cloud Computing. Teknologi ini didefinisikan sebagai model yang memungkinkan akses jaringan yang nyaman dan sesuai permintaan ke kumpulan sumber daya komputasi yang dapat dikonfigurasi secara cepat seperti jaringan, server, penyimpanan, aplikasi, dan layanan (Mell & Grance, 2011). Implementasi teknologi ini tidak hanya menawarkan skalabilitas yang masif, tetapi juga efisiensi biaya operasional yang signifikan karena organisasi dapat mengurangi ketergantungan pada perangkat keras fisik.

Secara teknis, Cloud Computing bekerja dengan mengabstraksi sumber daya fisik menjadi sumber daya virtual yang dapat dikelola secara terpusat. Hal ini memungkinkan penyedia layanan untuk mendistribusikan kapasitas pemrosesan, memori, dan penyimpanan secara dinamis sesuai dengan kebutuhan pengguna yang berubah-ubah (Buyya et al., 2018). Efisiensi ini menjadi kunci utama bagi organisasi yang ingin melakukan transformasi digital tanpa harus terbebani oleh pemeliharaan infrastruktur tradisional yang kaku dan memakan banyak ruang fisik.

Lebih lanjut, teknologi awan menyediakan berbagai model layanan seperti Infrastructure as a Service (IaaS), Platform as a Service (PaaS), dan Software as a Service (SaaS). Keberagaman model ini memberikan fleksibilitas bagi pengembang untuk memilih lingkungan yang paling sesuai dengan karakteristik aplikasi yang mereka bangun (Erl, 2013). Dengan demikian, teknologi ini menjadi fondasi bagi inovasi digital yang lebih cepat dan jauh lebih responsif terhadap tuntutan pasar yang terus berkembang secara global.

Pemanfaatan virtualisasi dalam ekosistem awan juga memungkinkan pemisahan antara perangkat lunak dan perangkat keras, yang meningkatkan isolasi keamanan dan manajemen sumber daya secara spesifik. Hal ini sangat penting dalam menjaga integritas data dan memastikan bahwa setiap aplikasi mendapatkan alokasi sumber daya yang adekuat tanpa mengganggu aplikasi lainnya (Mell & Grance, 2011). Oleh karena itu, Cloud Computing kini dianggap sebagai standar baru dalam pengelolaan pusat data modern yang menuntut performa tinggi di seluruh dunia.

Aspek ketahanan (resilience) yang ditawarkan oleh teknologi ini juga memastikan bahwa data tetap tersedia meskipun terjadi kegagalan pada salah satu komponen fisik di pusat data. Melalui mekanisme replikasi dan distribusi data di berbagai lokasi geografis, teknologi awan menjamin keberlangsungan bisnis yang jauh lebih baik dibandingkan metode penyimpanan lokal konvensional (Buyya et al., 2018). Kapabilitas luar biasa yang ditawarkan oleh infrastruktur awan inilah yang pada akhirnya memicu ketertarikan mendalam bagi penulis untuk mengeksplorasi potensinya lebih jauh.

Ketertarikan penulis terhadap teknologi Cloud Computing didorong oleh kemampuannya yang sangat efektif dalam memecahkan masalah ketersediaan layanan (service availability). Dalam ekosistem digital yang beroperasi tanpa henti selama 24 jam, kebutuhan akan sistem yang tetap berjalan stabil menjadi sangat krusial bagi kepuasan dan kepercayaan pengguna. Penulis melihat bahwa teknologi ini memberikan solusi cerdas bagi administrator jaringan untuk melakukan manajemen sumber daya secara otomatis dan presisi (Erl, 2013).

Selain itu, penulis sangat tertarik pada aspek efisiensi energi dan optimalisasi biaya yang ditawarkan oleh berbagai platform penyedia layanan awan saat ini. Dengan kemampuan pay-as-you-go, organisasi hanya perlu membayar sumber daya yang benar-benar mereka gunakan, yang merupakan revolusi besar dalam manajemen anggaran teknologi informasi (Buyya et al., 2018). Ketertarikan ini muncul dari pengamatan lapangan terhadap banyak organisasi yang seringkali mengalami pemborosan sumber daya pada infrastruktur server fisik.

Faktor lain yang menarik minat penulis adalah kemudahan dalam melakukan eksperimen serta pengembangan aplikasi berskala besar tanpa risiko kegagalan infrastruktur yang tinggi. Teknologi awan memungkinkan pembuatan lingkungan pengujian yang identik dengan lingkungan produksi dalam waktu yang sangat singkat, sehingga mempercepat siklus peluncuran fitur baru (Erl, 2013). Hal ini menunjukkan betapa teknologi ini telah mendemokratisasi akses terhadap infrastruktur kelas dunia bagi pengembang individu maupun organisasi berskala kecil.

Penulis juga mengamati adanya potensi besar dalam penggabungan teknologi awan dengan kecerdasan buatan serta analitik data tingkat lanjut untuk mendukung pengambilan keputusan. Kemampuan untuk mengolah data dalam jumlah masif secara instan di lingkungan awan memberikan wawasan bisnis yang sebelumnya tidak mungkin didapatkan dengan perangkat keras standar (Mell & Grance, 2011). Eksplorasi mengenai integrasi layanan-layanan canggih ini menjadi salah satu motivasi kuat penulis dalam mendalami bidang arsitektur jaringan.

Keyakinan bahwa masa depan seluruh layanan digital akan sepenuhnya bergantung pada arsitektur awan menjadi alasan fundamental lainnya bagi penulis dalam memilih topik ini. Memahami cara kerja, mengidentifikasi kelemahan, serta menemukan metode optimasi pada teknologi ini adalah keahlian yang sangat relevan dan dibutuhkan oleh industri masa depan (Buyya et al., 2018). Namun, dalam implementasinya, efisiensi awan sangat bergantung pada bagaimana lalu lintas data dikelola, di mana peran teknologi distribusi beban menjadi sangat krusial.

Meskipun teknologi awan menawarkan fleksibilitas yang sangat tinggi, distribusi beban kerja yang tidak merata di antara server-server yang tersedia tetap menjadi tantangan teknis yang kritis. Di sinilah letak urgensi penggunaan Load Balancer sebagai komponen vital yang menjaga stabilitas dalam arsitektur jaringan modern. Load Balancer merupakan perangkat atau mekanisme yang berfungsi untuk mendistribusikan lalu lintas jaringan ke beberapa server di dalam sebuah klaster secara seimbang dan cerdas (Nance & Hay, 2020).

Tujuan utama dari implementasi Load Balancer adalah untuk memaksimalkan throughput serta meminimalkan waktu tanggap (response time) bagi setiap pengguna yang mengakses layanan. Dengan membagi beban kerja secara merata, tidak ada satu pun server yang akan mengalami beban berlebih (overload) yang berpotensi memicu kegagalan sistem secara berantai (Cloudflare, 2025). Mekanisme distribusi ini memastikan bahwa seluruh sumber daya komputasi yang telah disewa atau dibangun dapat dimanfaatkan secara optimal tanpa ada yang menganggur.

Secara operasional, Load Balancer bekerja dengan cara melakukan pemeriksaan kesehatan (health check) secara berkala pada setiap server yang terhubung di belakangnya. Jika salah satu server terdeteksi mengalami kegagalan atau tidak responsif, Load Balancer secara otomatis akan mengalihkan trafik ke server lain yang masih dalam kondisi normal (F5 Networks, 2024). Proses pengalihan ini terjadi secara transparan bagi pengguna, sehingga mereka tetap mendapatkan layanan yang lancar tanpa menyadari adanya kendala teknis pada sisi internal.

Terdapat berbagai algoritma yang digunakan dalam sistem Load Balancer, mulai dari metode Round Robin yang sederhana hingga algoritma berbasis beban koneksi terkecil (Least Connection). Pemilihan algoritma yang tepat sangat menentukan tingkat efektivitas distribusi trafik sesuai dengan karakteristik aplikasi serta kebutuhan performa yang dilayani (Nance & Hay, 2020). Penulis melihat bahwa kecerdasan dalam pemilihan strategi penyeimbangan beban ini adalah kunci utama dari performa sistem yang tetap responsif meskipun berada di bawah tekanan trafik yang tinggi.

Tanpa adanya mekanisme load balancing yang tepat, lonjakan trafik yang terjadi secara tiba-tiba dapat mengakibatkan latensi tinggi yang mengganggu operasional atau bahkan kondisi downtime total. Hal ini tidak hanya merugikan pengguna dari sisi pengalaman akses, tetapi juga secara langsung merusak kredibilitas serta citra penyedia layanan di mata publik (F5 Networks, 2024). Pentingnya manajemen beban ini menjadi sangat nyata ketika kita meninjau kondisi infrastruktur digital pada entitas yang memiliki trafik tinggi seperti Organisasi N.

Pemilihan Organisasi N sebagai lokasi penelitian spesifik didasarkan pada profil operasionalnya yang saat ini sangat bergantung pada stabilitas akses data dan layanan digital. Sebagai organisasi yang melayani banyak pemangku kepentingan dengan tingkat akses harian yang padat, Organisasi N memerlukan infrastruktur yang mampu menangani beban kerja secara konsisten. Namun, kenyataan di lapangan menunjukkan bahwa fluktuasi trafik yang tidak terprediksi seringkali menjadi hambatan utama bagi kelancaran operasional mereka.

Penulis mengidentifikasi bahwa pada jam-jam sibuk tertentu, sistem informasi yang dikelola oleh Organisasi N seringkali mengalami penurunan performa yang cukup signifikan bagi penggunanya. Masalah ini disinyalir muncul karena penumpukan permintaan akses yang tidak terdistribusi secara merata pada seluruh node server yang tersedia dalam infrastruktur mereka. Kondisi tersebut menunjukkan adanya celah dalam manajemen distribusi beban yang perlu segera diperbaiki melalui pendekatan teknologi yang lebih adaptif.

Ketertarikan penulis untuk melakukan penelitian di organisasi ini juga diperkuat oleh visi Organisasi N yang sangat terbuka terhadap inovasi teknologi demi meningkatkan efisiensi kerja internal. Dengan melakukan penelitian langsung di lokasi tersebut, penulis dapat memahami variabel-variabel nyata dan hambatan teknis yang mempengaruhi performa jaringan di lingkungan kerja yang sesungguhnya. Data primer yang diperoleh dari lapangan akan menjadi fondasi yang sangat kuat dalam membangun model solusi yang benar-benar aplikatif.

Selain itu, Organisasi N saat ini sedang berada dalam fase pengembangan sistem informasi jangka panjang yang membutuhkan fondasi arsitektur jaringan yang jauh lebih tangguh. Penulis melihat bahwa hasil dari penelitian ini nantinya dapat memberikan kontribusi berupa rekomendasi strategis bagi tim teknologi informasi organisasi dalam mengoptimalkan sumber daya awan yang ada. Hal ini sangat sejalan dengan upaya besar organisasi untuk mencapai standar layanan digital yang unggul, cepat, dan tetap profesional.

Sebagai langkah nyata, penelitian ini akan mengintegrasikan teori-teori Load Balancer untuk diaplikasikan pada kasus nyata yang kompleks di lingkungan Organisasi N. Keberhasilan dalam melakukan optimasi di organisasi ini diharapkan tidak hanya menyelesaikan masalah internal, tetapi juga menjadi referensi ilmiah bagi organisasi lain dengan karakteristik beban kerja yang serupa. Oleh karena itu, fokus penelitian di lokasi ini dianggap sangat relevan dan mendesak demi mendukung keberlanjutan transformasi digital di lingkungan Organisasi N.

## Identifikasi Masalah

Peneliti melihat tidak adanya sistem otomasi perpustakaan yang stabil dalam menghadapi lonjakan permintaan buku digital yang tinggi di Organisasi N adalah masalah utama penelitian ini, seperti yang ditunjukkan dalam latar belakang.

1. Distribusi Trafik yang Tidak Merata: Terjadinya penumpukan beban kerja hanya pada server tertentu, sementara sumber daya pada server lain tidak termanfaatkan secara optimal.
2. Penurunan Performa Sistem: Munculnya kendala berupa respon aplikasi yang lambat atau latensi tinggi, terutama pada saat terjadi lonjakan jumlah pengguna secara bersamaan.
3. Rendahnya Ketersediaan Layanan (Availability): Risiko terjadinya layanan yang tidak dapat diakses (downtime) apabila salah satu server mengalami gangguan, karena belum adanya mekanisme pengalihan beban otomatis yang andal.
4. Manajemen Sumber Daya yang Tidak Efisien: Penggunaan infrastruktur teknologi informasi yang belum mampu beradaptasi secara dinamis terhadap fluktuasi trafik harian.
5. Kurangnya Optimalisasi Strategi Penyeimbangan Beban: Belum digunakannya algoritma distribusi beban yang tepat untuk menangani karakteristik trafik spesifik yang ada pada organisasi.
6. Gangguan Operasional Organisasi: Terhambatnya aktivitas kerja staf dan pelayanan kepada pihak eksternal akibat ketidakstabilan sistem pada jam-jam sibuk.

## Batasan Masalah

Berdasarkan identifikasi masalah yang telah dipaparkan, maka batasan masalah dalam penelitian ini adalah:

1. Penelitian ini hanya berfokus pada ruang lingkup perpustakaan Organisasi N. 
Penelitian ini hanya berfokus pada implementasi NGINX sebagai perangkat lunak load balancer.
2. Analisis performa dibatasi pada penggunaan algoritma load balancing tertentu untuk mendistribusikan trafik di Organisasi N.
3. Sistem yang diuji adalah Sistem Otomasi Perpustakaan (SLIMS) yang digunakan di Organisasi N, khususnya pada fungsi pencarian katalog (OPAC) dan akses buku digital.

## Rumusan Masalah

Berdasarkan identifikasi masalah yang telah ditetapkan, maka rumusan masalah dalam penelitian ini adalah:

1. Bagaimana implementasi arsitektur load balancing menggunakan NGINX di Organisasi N untuk mengeliminasi risiko single point of failure (titik kegagalan tunggal) pada sistem otomasi perpustakaan?
2. Bagaimana pengaruh penerapan load balancing berbasis NGINX terhadap peningkatan kecepatan waktu tanggap (response time) layanan sesuai dengan hukum keempat Noruzi (Save the time of the Web user)?
3. Bagaimana efektivitas mekanisme distribusi beban kerja (workload distribution) dalam menyeimbangkan trafik permintaan buku digital di antara klaster peladen (server cluster) pada Organisasi N?

## Tujuan Penelitian

Menerapkan dan menganalisis sistem load balancing berbasis NGINX pada sistem otomasi perpustakaan di Organisasi N untuk menghilangkan risiko single point of failure serta meningkatkan efisiensi waktu akses pemustaka sesuai dengan prinsip hukum keempat Noruzi (Save the time of the Web user).

## Manfaat Penelitian

Adapun tujuan dan manfaat penelitian yang ingin dicapai oleh peneliti berdasarkan permasalahan yang telah dijelaskan sebelumnya adalah sebagai berikut: 

1. Manfaat Teoritis
a. Pengembangan Ilmu Perpustakaan dan Informasi: Memberikan kontribusi pemikiran mengenai penerapan konsep load balancing sebagai bentuk modernisasi dari The Five Laws of the Web milik Alireza Noruzi, khususnya dalam menjaga keberlangsungan layanan informasi.
b. Pengayaan Literatur Infrastruktur Digital: Menjadi referensi akademis mengenai relevansi teori efisiensi waktu (Hukum ke-4 Ranganathan/Noruzi) dalam mengatasi hambatan teknis seperti server overload pada ekosistem perpustakaan digital.
c. Model Transformasi Teknologi: Memberikan landasan teoritis tentang bagaimana arsitektur high availability (ketersediaan tinggi) dapat mendukung filosofi perpustakaan sebagai "organisme yang tumbuh" (The Web is a growing organism) di tengah lonjakan data digital.

2. Manfaat Praktis
a. Bagi Organisasi N: Menghasilkan rekomendasi teknis dan solusi konkret untuk menciptakan sistem otomasi perpustakaan yang stabil, responsif, dan bebas dari risiko single point of failure saat terjadi lonjakan permintaan buku digital.
b. Bagi Pengelola Teknologi Informasi: Memberikan panduan praktis dalam mengonfigurasi NGINX sebagai load balancer yang efisien dan ekonomis (berbasis open source) untuk mengoptimalkan sumber daya server yang ada di perpustakaan.

## Tinjauan Penelitian Terdahulu

Beberapa penelitian terdahulu yang relevan dengan rancangan load balancer pada sistem otomasi perpustakaan adalah sebagai berikut:

Pertama, penelitian yang dilakukan oleh Pratama dan Wijaya (2021) berfokus pada optimasi web server menggunakan NGINX untuk menurunkan beban kerja CPU. Hasil penelitian ini menunjukkan bahwa distribusi trafik yang merata dapat mencegah server dari kondisi kelebihan beban (overload). Kesamaan dengan penelitian ini adalah penggunaan perangkat lunak NGINX sebagai instrumen utama load balancing. Namun, perbedaannya terletak pada objek penelitian, di mana Pratama dan Wijaya melakukan studi pada platform e-commerce, sementara penelitian ini secara spesifik diimplementasikan pada sistem otomasi perpustakaan untuk akses buku digital di Organisasi N.

Kedua, Saputra (2022) menganalisis ketersediaan tinggi (high availability) pada server repositori kampus dengan algoritma Round Robin. Hasilnya membuktikan bahwa redundansi server sangat efektif dalam menjaga ketersediaan data secara kontinu. Persamaan penelitian tersebut dengan penelitian ini terletak pada tujuannya untuk mencapai ketersediaan layanan yang stabil melalui pengujian simulasi lonjakan trafik. Perbedaannya, Saputra menitikberatkan pada aspek teknis jaringan murni, sedangkan penelitian ini mengintegrasikan hasil teknis tersebut dengan teori Alireza Noruzi terkait efisiensi waktu akses bagi pemustaka.

Ketiga, Al-Fatih (2023) mengkaji strategi infrastruktur digital perpustakaan dalam menghadapi pertumbuhan data yang besar. Hasil penelitian menekankan bahwa perpustakaan memerlukan sistem yang skalabel agar bisa terus berkembang tanpa gangguan layanan. Kesamaan dengan penelitian ini adalah penggunaan perspektif perpustakaan sebagai organisme yang terus tumbuh sesuai hukum kelima Ranganathan. Namun, perbedaannya adalah penelitian Al-Fatih bersifat deskriptif-kualitatif mengenai kebijakan, sedangkan penelitian ini bersifat eksperimental melalui implementasi dan pengujian langsung di Organisasi N.

Terakhir, penelitian dari Lestari (2020) meneliti tentang kepuasan pengguna terhadap kecepatan akses katalog daring (OPAC), yang menyimpulkan bahwa responsivitas sistem berkorelasi langsung dengan tingkat kepuasan pemustaka. Kesamaannya adalah fokus pada peningkatan kualitas layanan perpustakaan melalui optimasi waktu tunggu. Perbedaannya, Lestari berfokus pada analisis persepsi pengguna, sementara penelitian ini memberikan solusi infrastruktur berupa load balancing NGINX sebagai upaya teknis untuk mewujudkan kecepatan akses yang diinginkan tersebut.

<!-- ## Tinjauan Penelitian Terdahulu (old)

Beberapa penelitian terdahulu yang relevan dengan rancangan load balancer pada sistem otomasi perpustakaan adalah sebagai berikut:

1. Artikel jurnal yang berjudul “Implementasi Load Balancing Pada Web Server Menggunakan Nginx” yang ditulis oleh Fahmi Apliansyah, Iskandar Fitri, dan Agus Iskandar. Penelitian yang diterbitkan pada tahun 2020 ini mengkaji penerapan algoritma load balancing menggunakan web server Nginx. Penelitian ini menggunakan 3 metode load balancing yang didukung oleh Nginx yaitu Round Robin, Least Connection, dan IP Hash. Hasil penelitian ini menunjukkan bahwa Least Connection mendapatkan response time 116ms, 2300.96 req/s dan throughput 17380.01 kbps sedangkan Round Robin mendaptkan 140ms, 2335.36 req/s dan Throughput 17098.05 kbps. Dengan begitu menunjukkan bahwa Least Connection merupakan algoritma terbaik berdasarkan parameter yang telah peneliti ujikan. 

2. Artikel jurnal dari Endarta yang berjudul “Pemanfaatan Cloud Computing Meningkatkan Ketersediaan Dokumen Supervisi” membahas program cloud computing yang bersifat virtual dengan tujuan pemeliharaan data dan aplikasi. Penelitian yang diterbitkan pada tahun 2021 ini menggunakan cloud computing untuk menciptakan ketersediaan dokumen yang lebih siap, sehingga bisa diakses oleh petinggi di sekolah SMK. Hasil dari penelitian ini dapat meningkatkan layanan supervisi akademik dan manajerial kepada sekolah binaan.

3. Artikel jurnal oleh Achmad Mustofa dan Desi Ramayanti yang berjudul “Implementasi Load Balancing dan Failover to Device Mikrotik Router Menggunakan Metode NTH (Studi Kasus: PT Gojek Indonesia”. Penelitian yang diterbitkan pada tahun 2020 ini mengkaji Load Balancing untuk pengefisienan pergantian ISP (Internet Service Provider)). Penelitian ini menghasilkan keseimbangan traffic pada dua jalur koneksi dengan menggunakan metode NTH dapat menghindari terjadinya overload pada salah satu jalur koneksi. -->
