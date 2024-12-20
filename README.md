# **EAS-KPPL**

**Nama**: Adyuta Prajahita Murdianto

**NRP**: 5025221186

**Kelas**: KPPL E

![alt text](<Resource/Gambar WhatsApp 2024-12-11 pukul 10.29.18_733bbe6a.jpg>)

## **Problems**

1. Dalam Pengembangan Perangkat Lunak ada fase Analisis dan Desain. 
   - Terangkan aktivitas yang dilakukan dalam fase Analisis dan Desain
   - Apa Output dari aktivitas tersebut untuk mendukung pengembangan perangkat lunak.

2. Dalam model Waterfall, setiap tahap memiliki fungsi spesifik. Jelaskan lima tahap utama dalam model ini, serta sebutkan kelebihan dan kekurangan dari model tersebut dalam konteks proyek besar yang memiliki persyaratan tetap.

3. Jelaskan perbedaan antara architectural design dan detailed design. Mengapa kedua jenis desain tersebut diperlukan dalam proses pengembangan perangkat lunak?

4. Studi Kasus:
   
   Sebuah perusahaan membutuhkan sistem e-commerce untuk menjual produk digital seperti foto, video, desain poster, ebook. Saat ini transaksi dihandle dengan WhatsApp. Namun seiring dengan perkembangan bisnis tools tersebut tidak mampu menangani lonjakan transaksi. Buatkan sistem / aplikasi yang mampu menangani lonjakan transaksi pada musim tertentu. Jelaskan pendekatan rekayasa perangkat lunak yang akan Anda gunakan untuk merancang, membangun, dan menguji sistem tersebut agar memenuhi kebutuhan klien.

## **No. 1**

### **Aktivitas Fase Analisis**

- **Pengumpulan Kebutuhan**

  Pada fase ini kita akan melakukan survey, pengumpulan informasi, serta ide tentang konsep aplikasi yang akan kita buat. Biasanya dilakukan dengan melakukan survey kondisi pasar saat ini atau juga dapat dengan melakukan survey terhadap calon user.

- **Analisis Kebutuhan**
  
  Dari konsep dan ide yang sudah didapat pada fase sebelumnya, disini kita akan mengumpulkan semua kebutuhan untuk membangun aplikasi.

- **Spesifikasi Kebutuhan**

  Lalu, disini kita akan mendokumentasikan kebutuhan dalam bentuk spesifikasi formal seperti `Software Requirement Specification (SRS)`.

- **Validasi Kebutuhan**
  
  Terakhir, kita harus memvalidasi bahwa kebutuhan yang terdefinisi dapat dipenuhi dengan teknologi yang tersedia dan sesuai dengan tujuan bisnis.

### **Aktivitas Fase Desain**

- **Desain Arsitektur**

  Pada fase ini, pertama kita akan merancang struktur tinggi dari sistem, termasuk pemilihan teknologi, pola arsitektur, dan komponen utama. Hal ini penting, agar kedepannya saat proses developing semuanya sudah terencara dan terorganisir dengan rapi.

- **Desain Basis Data**

  Pada tahap ini kita akan mendesain bagaimana struktur pengelolaan data dari sistem kita. 

- **Desain Antarmuka**

  Lalu kita juga merancang antarmuka sistem yang akan ditampilkan ke user. Biasanya hal ini dilakukan oleh `UI/UX`.

- **Desain Komponen Detil**

  Pada tahap ini kita merancang algoritma logika bisnis yang akan diterapkan oleh sistem. Hal ini dilakukan oleh `Backend`.

### **Output**

- **Analisis**: Dokumen yang berisi analisis aplikasi, contohnya `SRS`.

- **Desain**: Dokumen konkrit yang berisi rancangan aplikasi yang akan kita buat, contohnya `CDM`, `PDM`, dan `UI/UX`

## **No. 2**

### **Tahap**

**1. Requirement Analysis and Specification**

Tahap ini berfokus pada pengumpulan dan analisis kebutuhan perangkat lunak. Tim proyek bekerja sama dengan pengguna atau klien untuk memahami apa yang diharapkan dari sistem yang akan dikembangkan. Hasil dari tahap ini adalah dokumen Software Requirements Specification (SRS) yang berisi kebutuhan fungsional (seperti fitur spesifik) dan non-fungsional (seperti performa atau keamanan). Dokumen ini menjadi dasar untuk semua tahap selanjutnya, sehingga harus dibuat lengkap dan bebas dari ambiguitas.

**2. System Design**

Setelah kebutuhan dirumuskan, tahap ini bertujuan untuk membuat desain sistem yang memenuhi kebutuhan tersebut. Desain ini melibatkan pemilihan teknologi, struktur data, dan arsitektur perangkat lunak. Diagram seperti data flow diagram (DFD), diagram kelas, atau diagram entity-relationship digunakan untuk memvisualisasikan sistem. Pada tahap ini, antarmuka pengguna dan desain database juga dirancang untuk memastikan efisiensi dan integrasi sistem.

**3. Implementation (Coding)**

Tahap implementasi melibatkan penerjemahan desain sistem ke dalam kode program. Pengembang mulai menulis kode untuk setiap modul berdasarkan desain yang telah dibuat. Modul-modul ini biasanya dikembangkan secara terpisah, diuji secara independen menggunakan unit testing, dan disiapkan untuk integrasi dengan modul lain. Hasil akhir dari tahap ini adalah perangkat lunak yang berfungsi sesuai desain awal.

**4. Integration and Testing**

Setelah modul-modul selesai dikembangkan, tahap ini bertujuan untuk mengintegrasikan semua modul ke dalam sistem penuh dan melakukan pengujian. Pengujian dilakukan untuk memastikan bahwa perangkat lunak memenuhi kebutuhan yang telah didefinisikan. Jenis pengujian yang dilakukan mencakup pengujian fungsional (menguji apakah fitur berjalan dengan baik), pengujian kinerja (mengukur efisiensi sistem), dan pengujian pengguna (menguji apakah perangkat lunak sesuai dengan harapan pengguna).

**5. Deployment and Maintenance**

Pada tahap akhir ini, perangkat lunak dirilis ke lingkungan produksi sehingga dapat digunakan oleh pengguna akhir. Setelah perangkat lunak diluncurkan, tim pengembang memberikan dukungan berupa pemeliharaan. Pemeliharaan ini meliputi perbaikan bug yang ditemukan setelah rilis (corrective maintenance), penyesuaian perangkat lunak terhadap perubahan lingkungan (adaptive maintenance), dan peningkatan sistem untuk memenuhi kebutuhan baru atau meningkatkan performa (perfective maintenance). Tahap ini bersifat berkelanjutan selama perangkat lunak masih digunakan.

### **Kelebihan**

- Struktur yang Terorganisasi.
- Dokumentasi Lengkap.
- Cocok untuk Proyek dengan Kebutuhan Tetap.
- Hasil yang Mudah Diprediksi.

### **Kekurangan**

- Kurang Fleksibel
- Resiko Keterlambatan Identifikasi Masalah
- Tidak Cocok untuk Proyek Kompleks atau Dinamis:
- Keterlibatan Pengguna Terbatas

### **Kesimpulan**

Seperti yang dijelaskan pada soal, disini konteksnya adalah proyek yang besar dan persyaratan yang tetap. Dalam konteks ini, metode `Waterfall` memiliki keunggulan yang cukup tinggi, yang dimana salah satu kelebihan dalam menggunakan metode ini adalah unggul dalam proyek dengan persyaratan tetap (karena memang waterfall tinggal menjalankan semuanya sesuai rencana awal tanpa adanya rencara tambahan). Lalu karena proyeknya besar, `Waterfall` juga unggul di bagian struktur yang terorganisir dengan baik.

## **No. 3**

### **Perbedaan**

- **Architectural Design**
  
  Merupakan desain tingkat tinggi yang menentukan struktur sistem secara keseluruhan, termasuk komponen utama, hubungan antar komponen, dan teknologi yang digunakan. Fokusnya adalah pada kerangka kerja besar dan bagaimana komponen berinteraksi.

- **Detailed Design**

  Merupakan desain rinci dari setiap komponen sistem. Fokusnya adalah pada algoritma, logika, dan implementasi teknis dalam setiap modul.

### **Alasan Mengapa Membutuhkan Keduannya**

- **Architectural Design**

  Membantu memastikan bahwa sistem dapat memenuhi kebutuhan bisnis dan bersifat skalabel.

- **Detailed Design**

  Memberikan panduan rinci kepada pengembang dalam implementasi teknis, memastikan efisiensi dan keandalan modul.

## **No. 4**

Pada studi kasus ini, saya memilih metode pendekatan `Waterfall`. Hal ini dikarenakan dari awal tujuan aplikasi sudah jelas (untuk menghandle transaksi) dan tidak begitu kompleks. Berikut tahapan dari pendekatan yang saya pilih:

**1. Requirement Analysis and Specification**

Pada tahap pertama, kita akan mengumpulkan ide-ide serta kebutuhan aplikasi melalui wawancara dan analisis bisnis. Sistem harus mendukung penjualan produk digital, menangani lonjakan transaksi, dan memiliki fitur keamanan serta efisiensi. Semua kebutuhan didokumentasikan dalam Software Requirements Specification (SRS) sebagai panduan untuk tahap selanjutnya.

**2. System Design**

Disini kita akan menentukan bagaimana bentuk dari sistem yang akan kita buat. Pertama dari arsitektur kita bisa memilih antara `Microservice` yang memiliki skalabilitas tinggi, namun dengan cost yang tinggi dan sistem yang lebih kompleks. Atau kita juga dapat memilih `Monolith` yang memiliki sistem yang lebih sederhana dan mudah untuk di kembangkan, namun dengan kurangnya skalabilitas. Lalu disini juga kita akan mendesain bagaimana bentuk dari database, serta kita juga akan mendesain alur kerja aplikasi dalam bentuk `Use Case Diagram` atuu bisa dengan diagram-diagram lainnya.

**3. Implementation (Coding)**

Pada tahap ini, kita akan mulai mengimplementasikan fitur-fitur seperti manajemen pengguna, transaksi, katalog, dll kedalam kode program. Disini untuk `Backend` dapat menggunakan bahasa seperti `Typescript` dengan `ExpressJs` atau `Golang` dengan banyak pilihan framework, dan `Frontend` bisa menggunakan framework moderen seperti `NextJs`. Kita mungkin juga bisa menggunakan `Laravel` jika ingin pengembangan lebih mudah dan cepat, namun kekurangannya adalah kecepatan pemrosesan yang tidak secepat bahasa lain yang saya sebutkan sebelumnya.

**4. Integration and Testing**

Untuk masa pengembangang, kita dapat melakukan `Unit Testing` untuk melakukan tes pada komponen-komponen yang cakupannya kecil. Lalu pada saat aplikasi sudah jadi, sebelum di deploy kita dapat melakukan `Integration Test` untuk mengetes fitur-fitur aplikasi secara keseluruhan agar memastikan aplikasi memiliki `bug` yang minim.

**5. Deployment and Maintenance**

Terakhir, kita akan meluncurkan sistem ke production dan disertai pelatihan untuk pengguna internal seperti `admin` dan lainnya. Pemeliharaan dilakukan secara berkelanjutan untuk memperbaiki bug, menyesuaikan kebutuhan baru, dan meningkatkan performa sistem agar tetap optimal.




