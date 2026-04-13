# Landasan Teori 
Keamanan Informasi (CIA Triad)
CIA Triad dikemukakan oleh Michael E.  Whitman menekankan adanya tiga prinsip yaitu confidentiality, Integrity, dan Availability dalam keamanan informasi yang dimana prinsip ini diterapkan di berbagai aspek keamanan informasi, mulai dari pengamanan informasi di penyimpanan (disk) hingga saat data sedang ditransmisikan melalui jaringan (Saputra et al., 2023). CIA Triad bertujuan untuk membentuk prinsip dasar yang digunakan untuk melindungi dan mengelola data atau informasi dalam sistem keamanan. 

Secara umum, CIA Triad bertujuan untuk membentuk prinsip dasar yang digunakan dalam melindungi dan mengelola data atau informasi dalam suatu sistem keamanan. Dengan adanya prinsip ini, organisasi atau perusahaan dapat memahami aspek-aspek penting yang harus diperhatikan dalam menjaga keamanan informasi. Hal ini menjadi sangat penting di era digital saat ini, di mana pertukaran informasi terjadi secara cepat dan rentan terhadap berbagai risiko keamanan.

Setiap prinsip dalam teori ini memiliki peran yang sangat penting dan saling melengkapi untuk memastikan bahwa data aman, kualitasnya terjaga, dan dapat diakses dengan cara yang sah. Keamanan informasi dalam CIA Triad memiliki tiga prinsip yaitu (Harahap et al., 2023):

## Confidentiality (Kerahasiaan) 
Prinsip confidentiality (kerahasiaan) berfokus pada upaya menjaga agar informasi hanya dapat diakses oleh pihak yang berwenang. Penerapan prinsip ini umumnya dilakukan melalui mekanisme seperti enkripsi data, autentikasi pengguna, serta pengendalian akses (access control).
## Integrity (Integritas)
prinsip integrity (integritas) menekankan bahwa data harus tetap akurat, konsisten, dan tidak mengalami perubahan tanpa izin selama proses penyimpanan maupun transmisi.Apabila integritas tidak terjaga, maka informasi yang dihasilkan dapat menjadi tidak valid dan berpotensi menimbulkan kesalahan dalam pengambilan keputusan.
## Availability (Ketersediaan)
Adapun prinsip availability (ketersediaan) memastikan bahwa data dan sistem dapat diakses oleh pengguna yang berhak kapan pun dibutuhkan.Ketersediaan yang baik akan mendukung kelangsungan operasional suatu organisasi atau perusahaan, karena pengguna dapat memperoleh informasi secara tepat waktu. Oleh sebab itu, keseimbangan antara ketiga prinsip CIA Triad menjadi kunci utama dalam menciptakan sistem keamanan informasi yang efektif dan komprehensif.

# Tinjauan Kajian Terdahulu  
Peneliti menggunakan penelitian terdahulu yang tepat sebagai bahan rujukan dan sebagai referensi dalam penelitian yang digunakan sebagai acuan dasar pertimbangan dan perbandingan bagi peneliti sebagai bahan analisis untuk menyusun penelitian. Berikut merupakan beberapa kajian terdahulu yang tepat dengan penelitian:
1. Penelitian dengan judul “Implementasi Secure Storage Menggunakan Metode Full Disk Encryption dan Tamper Proof pada Cloud Storage” yang ditulis oleh Barok Rizqi dan Andriani Adi Lestari. Penelitian ini bertujuan untuk memberikan prototipe keamanan perangkat fisik pada pangkalan data cloud storage. Penelitian ini menggunakan metode System Development Life Cycle (SDLC) dengan pendekatan waterfall yang memiliki empat tahap yaitu planning (perencanaan), analysis (analisis), design (desain), dan implementation (implementasi) dalam pembuatan sistem. Hasil penelitian ini menunjukkan bahwa setelah penerapan enkripsi disk penuh dengan Linux Unified Key Setup (LUKS), kecepatan write data pada disk turun dari 19,87 Mb/s menjadi 15,75 Mb/s. Ini menunjukkan bahwa penerapan penyimpanan aman berdampak pada kinerja penyimpanan cloud. Kesamaan antara kedua penelitian adalah bahwa topik penelitian terkait dengan sistem keamanan untuk perangkat fisik penyimpanan data pada peladen atau server, Selain itu penelitian ini juga berfokus pada peningkatan keamanan data. Sedangkan perbedaan terletak pada metode penelitian yang digunakan dan implementasi full enkripsi pada penelitian ini digunakan untuk cloud server.

2. Artikel jurnal dengan judul “Embedded LUKS (E-LUKS): A Hardware Solution to IoT Security” karya German Cano-Quiveu, Paulino Ruiz-de-clavijo-Vazquez, Manuel J. Bellido, Jorge Juan-Chico, Julian Viejo-Cortes, David Guerrero-Martos, dan Enrique Ostua-Aranguena .Penelitian yang diterbitkan pada tahun 2021 ini bertujuan untuk memberikan solusi untuk keamanan data  pada sumber daya perangkat maupun biaya yang terbatas pada perangkat Internet of Things (IoT) dengan menggunakan E-LUKS. Penelitian ini menggunakan design and development research yaitu dengan uji coba antara partisi disk yang tidak terenkripsi dengan partisi disk yang terenkripsi E-LUKS. Hasil penelitian ini adalah bahwa terbukti dengan valid, partisi yang telah dienkripsi E-LUKS lebih efisien secara fungsional. Partisi yang diuji dengan ukuran 4 kb, 8 kb, dan 16 kb. Pada partisi yang terenkripsi E-LUKS memiliki persentase waktu yang lebih kecil dalam membaca data daripada partisi yang tanpa terenkripsi. Persamaan antara penelitian ini dengan penelitian yang dilakukan merupakan topik mengenai disk yang ter enkripsi LUKS pada perangkat penyimpanan dan menggunakan metode penelitian design and development research. Perbedaan antara penelitian ini dengan penelitian yang dilakukan adalah penelitian ini uji coba untuk perangkat penyimpanan dan keamanan IoT sedangkan penelitian yang dilakukan peneliti yaitu  perangkat penyimpanan untuk data arsip digital.

3. Penelitian dengan judul “Teknik Pengamanan Data At Rest Menggunakan Bitlocker dan Veracrypt” karya Akhmad Nur Ghazi dan Ghofar Taufiq. Tujuan penelitian ini untuk memberikan instruksi tentang cara menggunakan bitlocker dan veracrypt untuk mengamankan data. Hasil penelitian ini adalah bitlocker hanya dapat digunakan dengan sistem operasi windows, sedangkan veracrypt lebih fleksibel dan disediakan secara gratis. Metode penelitian yang digunakan adalah observasi dan studi pustaka. Kedua penelitian sama-sama bertujuan untuk melindungi data dari akses tidak sah dengan menerapkan mekanisme enkripsi pada media penyimpanan. Perbedaan terletak pada sistem keamanan yang digunakan yaitu bitlocker dan veracrypt, sedangkan sistem keamanan yang digunakan penelitian yang dilakukan adalah network bound disk encryption. Selain itu metode pengumpulan data penelitian yang digunakan yaitu observasi dan studi pustaka, sedangkan metode pengumpulan data penelitian yang dilakukan yaitu wawancara dan uji coba laboratorium.

# Kajian Teoritis
## Arsip Digital
Arsip digital merupakan data elektronik yang diproduksi dan dikelola melalui infrastruktur teknologi informasi. Menurut Setyarto (2025), sistem ini tidak hanya berfungsi sebagai medium penyimpanan, tetapi juga sebagai platform strategis untuk meningkatkan efisiensi manajerial dan kemudahan akses data.

Koleksi dalam arsip digital terdiri dari dokumen yang lahir dalam format elektronik (born digital) maupun hasil alih media dari dokumen fisik. Fleksibilitas media ini menuntut adanya sistem manajemen yang terstandarisasi untuk menjaga autentisitas dan ketersediaan informasi, dengan tetap mengikuti siklus hidup arsip yang baku. Mulai dari tahap pembuatan, pemanfaatan, hingga retensi atau penyusutan.

Keunggulan utama teknologi ini terletak pada penggunaan metadata yang mampu mempercepat proses penemuan kembali dokumen secara akurat. Namun, efisiensi tersebut diikuti oleh sejumlah risiko teknis, seperti ancaman keamanan siber, kerusakan perangkat keras, hingga potensi hilangnya data secara permanen. Oleh karena itu, Farahdiba et al. (2024) menekankan pentingnya proses alih media yang presisi menggunakan pemindai (scanner) guna memastikan informasi dan karakteristik asli dokumen tetap terjaga saat beralih ke format digital.

Mengingat kompleksitas problematika dalam praktik di lapangan, pengelolaan arsip digital memerlukan ketelitian tingkat tinggi. Perusahaan atau organisasi diwajibkan menyusun kebijakan tata kelola yang komprehensif, mencakup strategi pemulihan data pasca bencana (disaster recovery) serta proteksi siber yang ketat. Selain regulasi internal, penguatan kompetensi sumber daya manusia melalui pelatihan teknologi informasi yang relevan menjadi faktor penentu keberhasilan manajemen kearsipan modern.

## Keamanan Arsip Digital

## Enkripsi
Enkripsi merupakan metode pengamanan data dengan cara menyandikan informasi asli melalui algoritma khusus (Alfirdaus et al., 2023). Proses ini mengubah data menjadi format yang tidak dapat terbaca, sehingga kerahasiaan informasi tetap terjaga dari pihak yang tidak berwenang selama proses pengiriman.Proses enkripsi pada dasarnya bertumpu pada sinergi antara algoritma kriptografi sebagai prosedur matematis transformasi data dan kunci (key) sebagai parameter kendali outputnya.
 
Secara klasifikatif, Stallings (2017) membedakan metode ini menjadi enkripsi simetris yang menggunakan kunci tunggal, serta enkripsi asimetris yang mengandalkan pasangan kunci publik dan privat. Dalam praktik keamanan informasi modern, fungsi enkripsi telah berkembang melampaui aspek kerahasiaan (confidentiality) hingga mencakup jaminan integritas data dan autentikasi melalui integrasi teknik hash function serta tanda tangan digital (Whitman & Mattord, 2018).

Seiring dengan eskalasi ancaman siber, evolusi algoritma seperti Advanced Encryption Standard (AES) menjadi representasi ketangguhan proteksi data yang kini telah diimplementasikan secara luas pada infrastruktur cloud computing dan perangkat seluler (Kahn, 2016). Dalam cakupan manajemen arsip digital, penerapan enkripsi menjadi instrumen vital untuk memitigasi risiko kebocoran informasi dan manipulasi ilegal. Oleh karena itu, integrasi teknologi penyandian ke dalam sistem pengarsipan merupakan langkah strategis untuk memperkuat pilar keamanan informasi yang meliputi kerahasiaan, integritas, dan ketersediaan data secara berkelanjutan.
## Luks

## NBDE


# Kerangka Pemikiran 
Untuk memberikan arahan yang jelas dalam melaksanakan penelitian ini, penulis membuat kerangka berpikir sebagai berikut untuk penelitian ini.

![kerangkaberfikir](../bab2/assets/images/kerangkat%20berfikir%20fix%20(1).png)
Gambar 1: Kerangka Berpikir
