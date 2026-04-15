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

Peneliti melihat tidak adanya sistem otomasi perpustakaan yang stabil dalam menghadapi lonjakan permintaan akses pada perpustakaan.

1. Distribusi Trafik yang Tidak Merata: Terjadinya penumpukan beban kerja hanya pada server tertentu, sementara sumber daya pada server lain tidak termanfaatkan secara optimal.
2. Penurunan Performa Sistem: Munculnya kendala berupa respon aplikasi yang lambat atau latensi tinggi, terutama pada saat terjadi lonjakan jumlah pengguna secara bersamaan.
3. Rendahnya Ketersediaan Layanan (Availability): Risiko terjadinya layanan yang tidak dapat diakses (downtime) apabila salah satu server mengalami gangguan, karena belum adanya mekanisme pengalihan beban otomatis yang andal.
4. Manajemen Sumber Daya yang Tidak Efisien: Penggunaan infrastruktur teknologi informasi yang belum mampu beradaptasi secara dinamis terhadap fluktuasi trafik harian.
5. Kurangnya Optimalisasi Strategi Penyeimbangan Beban: Belum digunakannya algoritma distribusi beban yang tepat untuk menangani karakteristik trafik spesifik yang ada pada organisasi.
6. Gangguan Operasional Organisasi: Terhambatnya aktivitas kerja staf dan pelayanan kepada pihak eksternal akibat ketidakstabilan sistem pada jam-jam sibuk.

## Batasan Masalah

Berdasarkan identifikasi masalah yang telah dipaparkan, maka batasan masalah dalam penelitian ini adalah:

1. Penelitian ini hanya berfokus pada ruang lingkup perpustakaan Organisasi N. 
2. Penelitian ini hanya berfokus pada implementasi teknologi load balancer.
3. Penelitian ini hanya berfokus pada pengujian metode penyeimbangan beban server.
4. Parameter pengujian pada penelitian ini hanya berfokus pada ketersediaan layanan

## Rumusan Masalah

Berdasarkan identifikasi masalah yang telah ditetapkan, maka rumusan masalah dalam penelitian ini adalah:

1. Bagaimana cara mengimplementasikan mekanisme Load Balancing pada infrastruktur jaringan di Organisasi N untuk mengatasi ketidakseimbangan distribusi beban kerja antar server?
2. Sejauh mana penggunaan algoritma Load Balancing dapat meningkatkan performa sistem saat terjadi lonjakan trafik di Organisasi N?
3. Bagaimana efektivitas Load Balancer dalam menjamin ketersediaan layanan (High Availability) jika salah satu node server mengalami kegagalan pada sistem informasi Organisasi N?

## Tujuan Penelitian

Tujuan yang ingin dicapai melalui penelitian ini adalah sebagai berikut:
1. Mengimplementasikan mekanisme Load Balancing pada infrastruktur jaringan di Organisasi N untuk menciptakan distribusi beban kerja yang lebih merata dan efisien antar server.
2. Menguji tingkat ketersediaan layanan (High Availability) guna memastikan sistem tetap dapat diakses oleh pengguna meskipun salah satu node server mengalami gangguan atau kegagalan teknis.

## Manfaat Penelitian

Adapun tujuan dan manfaat penelitian yang ingin dicapai oleh peneliti berdasarkan permasalahan yang telah dijelaskan sebelumnya adalah sebagai berikut: 

1. Manfaat Teoritis
Manfaat Teoritis merupakan kegunaan hasil penelitian yang bertujuan untuk pengembangan ilmu pengetahuan serta memperkuat teori-teori yang sudah ada dalam bidang akademis. Manfaat ini diharapkan dapat menjadi pijakan bagi penelitian selanjutnya agar memiliki dasar literatur yang lebih luas mengenai optimasi jaringan.
a. Memberikan kontribusi ilmiah dalam pengembangan studi mengenai implementasi Load Balancing pada arsitektur Cloud Computing.
b. Menjadi referensi akademik bagi peneliti lain yang ingin mendalami perbandingan efektivitas berbagai algoritma distribusi beban kerja.
c. Memperkaya literatur mengenai strategi menjaga High Availability pada infrastruktur jaringan digital modern.

2. Manfaat Praktis
Manfaat Praktis adalah kegunaan hasil penelitian yang dapat diterapkan secara langsung untuk memecahkan masalah nyata di lapangan atau organisasi. Manfaat ini berfokus pada solusi aplikatif yang memberikan dampak positif bagi jalannya operasional sebuah instansi.
a. Bagi Penulis: Menambah wawasan dan keahlian teknis dalam merancang serta mengonfigurasi sistem distribusi beban pada lingkungan server yang kompleks.
b. Bagi Pengguna: Meningkatkan kenyamanan pengguna dalam mengakses layanan informasi di Organisasi N karena sistem menjadi lebih responsif dan minim gangguan.

## Tinjauan Penelitian Terdahulu

Beberapa penelitian terdahulu yang relevan dengan rancangan load balancer pada sistem otomasi perpustakaan adalah sebagai berikut:

1. Irawan et al. (2020) yang membahas tentang implementasi mekanisme penyeimbangan beban menggunakan metode Round Robin pada infrastruktur server berbasis Cloud. Dalam abstraknya, penelitian ini menjelaskan bahwa pendistribusian trafik secara merata mampu menurunkan beban kerja CPU pada server utama dan mencegah terjadinya crash saat trafik memuncak. Persamaan penelitian ini dengan penelitian yang penulis lakukan terletak pada penggunaan teknologi Cloud Computing sebagai fondasi infrastruktur dan fokus utama pada optimasi distribusi trafik. Namun, perbedaannya adalah Irawan et al. hanya menguji satu algoritma statis, sedangkan penulis akan melakukan komparasi beberapa algoritma untuk menemukan solusi yang paling adaptif bagi Organisasi N.
2. Saputra dan Nugroho (2021) yang mengevaluasi performa sistem load balancing untuk mendukung layanan web di sebuah instansi pendidikan. Inti dari penelitian ini adalah bagaimana menjaga ketersediaan layanan (high availability) agar tetap stabil meskipun terjadi lonjakan akses pengguna secara serentak. Kesamaan dengan penelitian penulis adalah adanya objek organisasi yang memiliki karakteristik trafik fluktuatif pada jam-jam sibuk tertentu. Adapun perbedaannya terletak pada ruang lingkup infrastrukturnya, di mana Saputra dan Nugroho melakukan implementasi pada jaringan lokal (On-Premise), sementara penulis berfokus pada implementasi di lingkungan Cloud.
3. Pratama (2022) yang mengkaji efisiensi algoritma Least Connection dibandingkan dengan Round Robin pada arsitektur server virtual. Hasil penelitian menunjukkan bahwa algoritma Least Connection memiliki performa yang lebih unggul dalam menangani trafik dinamis karena mempertimbangkan jumlah koneksi aktif di setiap server. Persamaan dengan penelitian penulis adalah digunakannya metode komparatif antar algoritma untuk menentukan parameter performa terbaik. Perbedaan mendasarnya adalah Pratama melakukan pengujian pada lingkungan simulasi laboratorium, sedangkan penulis melakukan studi kasus nyata yang diimplementasikan langsung pada kebutuhan operasional Organisasi N.
4. Fahmi et al. (2023) mengenai strategi optimalisasi infrastruktur awan untuk layanan publik di sektor pemerintahan. Dalam abstraknya, penelitian ini menekankan bahwa integrasi antara penyeimbang beban dan skalabilitas otomatis sangat penting untuk menjaga integritas data dan kecepatan akses. Persamaan dengan penelitian penulis adalah tujuan untuk meningkatkan kualitas layanan digital bagi pemangku kepentingan dalam sebuah organisasi. Perbedaannya adalah penelitian Fahmi et al. lebih menitikberatkan pada fitur auto-scaling (penambahan server otomatis), sedangkan penulis lebih fokus pada manajemen distribusi beban kerja pada node server yang tersedia.
5. Wijaya dan Lestari (2024) membahas tentang implementasi penyeimbang beban pada teknologi Software Defined Network (SDN) untuk meminimalkan kegagalan pengiriman paket data. Hasil pengujian menunjukkan peningkatan throughput yang signifikan setelah arus trafik dikelola secara terpusat oleh kontroler. Persamaan dengan penelitian penulis adalah penggunaan parameter throughput dan response time sebagai indikator utama keberhasilan sistem. Namun, perbedaan yang menonjol adalah Wijaya dan Lestari menggunakan arsitektur SDN yang bersifat kompleks dan eksperimental, sementara penulis menggunakan arsitektur Cloud yang lebih aplikatif dan relevan dengan kondisi infrastruktur di Organisasi N saat ini.
