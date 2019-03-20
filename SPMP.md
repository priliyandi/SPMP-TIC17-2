<p align="center"><font size="5"><b>Software Project Management Plan</b></font><br>
"Sistem Informasi Absensi dan Penggajian Kafka Konveksi"</p>

<p align="center"><img src="Gambar/POLINDRA.png" width="250" height="250"></p>

<br>

<p align="center">
    <b><font size="4">Kelompok 2:</font></b><br>
    1. Priliyandi (1703073) <br>
    2. Riyanwar Setiadi (1703087)<br>
    3. Setyo Abiansyah (1703071)<br>
    4. Uum Khumaeroh (1703084)
</p>
<center><font size="3"><p align="center">Kelas D3TI2C</p></font></center>

<br>

<br>

<p align="center"><b><font size="5">D3 TEKNIK INFORMATIKA</font></b><br>
<b><font size="3">POLITEKNIK NEGERI INDRAMAYU</font></b><br>
<b><font size="3">2019</font></b></p>










**1.** **Pendahuluan**<br><br>
    **1.1** **Gambaran Proyek** <br>
        <ol>Proyek yang sedang kami buat adalah Sistem Informasi Absensi dan Penggajian di Perusahaan Konveksi "Kafka". Kafka merupakan sebuah perusahaan konvenksi dengan karyawan yang cukup banyak. Oleh karena itu Sistem absen dan penggajian merupakan hal yang sangat pokok pada kegiatan financial sebuah perusahaan karena hal tersebut sangat berpengaruh kepada kinerja para pegawai yang setiap hari melakukan aktifitas. Sistem penggajian menyajikan cara-cara penggajian pegawai secara akurat, menghasilkan laporan-laporan yang diperlukan dan menyajikan kebutuhan informasi kepada manajemen. </ol><br>
        <ol>Adapun kendala yang dihadapi di Kafka konveksi yaitu absensi dan penggajian yang masih dilakukan secara manual masih berbentuk arsip sehingga memperlambat dalam proses pencarian, penghitungan dan proses pembuatan laporan penggajian. oleh karena itu akan dirancang sebuah sistem informasi absensi dan  penggajian, antara lain meliputi sistem absensi karyawan, sistem penghitungan gaji dan berbagai attributnya seperti lembur, cuti, potongan dan sebagainya secara terotomatisasi. Selain itu sistem juga mampu membuat berbagai laporan baik yang ditujukan untuk karyawan seperti slip gaji dan laporan yang ditujukan untuk direktur seperti laporan data karyawan, laporan absensi karyawan, dan laporan gaji karyawan secara terotomatisasi dimana system informasi tersebut dibuat dengan Framework Laravel dan Android.</ol><br>
        <ol>Tentunya dalam pembuatan Sistem Informasi Absensi dan Penggajian di Perusahaan Konveksi "Kafka" yang akan Kami buat butuh sebuah tim yang solid, tim yang terdiri dari Project Manager, Programmer, Data Analisis,Database Administrator. kami bermaksud membagi beberapa tugas sesuai kriteria kemampuan masing-masing, yang nantinya satu sama lain diharapkan dapat bekerja sama dan melengkapi satu sama lain, sehingga dapat membangun sistem yang baik sesuai yang produsen butuhkan. </ol>
​    **1.2** **Dokumen-dokumen dalam Proyek** <br>
        <ol>Saat mengerjakan projek ini, pencatatan kegiatan yang telah dilakukan ditulis didalam log book kelompok, anggota yang telah mengerjakan tugas sesuai projek kegiatannya dicatat dalam log book, selain log book dokumen yang berkaitan dengan projek ini meliputi requirtments, penjadwalan, pembagian tugas, dan referensi-referensi yang berkaitan dengan pembuatan projek kami. Selain Log book ada juga Proposal serta laporan, Proposal mengenai daftar yang di butuhkan dalam penggarapan project serta laporan hasil project yang telah dibuat </ol><br>
​    **1.3** **Evolusi SPMP**<br>
        <ol>Dokumen ini bersifat freeware, jadi siapa saja boleh untuk memanfaatkan dokumen ini untuk hal yang positif. Tentu ada hal-hal yang tidak boleh dilakukan dalam pemanfaatan dokumen ini, seperti menjualbelikan dokumen ini secara ilegal, ataupun mengubah dokumen tanpa dasar yang jelas.</ol><br>
​    **1.4** **Material Acuan** <br>
        <ol>Materi yang menjadi acuan dalam pembuatan projek ini menggunakan standar IEEE, karena menyediakan kerangka kerja yang menggabungkan seluruh spektrum proses siklus hidup perangkat lunak. Dan juga standar IEEE untuk membentukmodel yang diakui secara internasional dari kehidupan perangkat lunak umum, siklus proses yang dapat direferensikan oleh industri perangkat lunak diseluruh dunia, untuk mempromosikan pemahaman diantara pihak bisnis dengan aplikasi umum serta mengakui proses, kegiatan dan tugas.</ol><br>
        <ol>IEEE adalah sebuah organisasi profesi nirlaba yang terdiri dari banyak ahli dibidang teknik yang mempromosikan pengembangan standar-standar dan bertindak sebagai pihak yang mempercepat teknologi- teknologi baru dalam semua aspek dalam industry dan rekayasa (engineering), yang mencakup telekomunikasi, jaringan komputer, kelistrikan, antariksa, dan elektronika. Tujuan inti IEEE adalah mendorong inovasi teknologi dan kesempurnaan untuk kepentingan kemanusiaan.Visi IEEE adalah akan menjadi penting untuk masyarakat teknis global dan professional teknis dimana-mana dan dikenal secara universal untuk kontribusi teknologi dan teknis yang professional dalam meningkatkan kondisi perkembangan global. Standar dalam IEEE adalah mengatur fungsi, kemampuan dan interoperabilitas dari berbagai macam produk dan layanan yang mengubah cara orang hidup, bekerja dan berkomunikasi.</ol><br>
​    **1.5** **Definisi Akronim (Singkatan)** <br>
        <ol>Dalam penulisan dokumen pembuatan projek ini, ada beberapa kata yang mungkin akan sulit dipahami oleh orang awam berikut ini : <br>
        IEEE = The International Institute of Electronic and Electrical Engineers<br><br>
**2.** **Organisasi Proyek**<br><br>
   **2.1** **Model proses**<br>
        Kami menggunakan model sashimi, Proses perangkat lunak sashimi (Takeuchi + Nonaka1986-nnpd) sangat mirip dengan model waterfall, kecuali bahwa fase tumpang tindih untuk menunjukkan bahwa persyaratan tidak dapat diselesaikan sampai arsitektur setidaknya sebagian dieksplorasi, dan arsitektur tidak dapat diselesaikan sampai desain modul setidaknya sebagian dieksplorasi, dan sebagainya.<br>
        Proses sashimi paling tepat untuk proyek-proyek berukuran sedang di mana komunikasi antar fase dapat ditangani secara improvisasi. Untuk proyek yang lebih besar, proyek berisiko tinggi, atau proyek di mana beberapa pengembang berpengalaman, pendekatan spiral mungkin lebih baik.<br>
​    **2.2** **Struktur Organisasi**<br>
        <ol>Project Manager         : Priliyandi<br>
        Programmer              : Riyanwar Setiadi<br>
        Database Administrator  : Setyo Sbiansah<br>
        Analisys Desain         : Uum Khumaeroh</ol><br>
​    **2.3** **Batasan dan antarmuka organisasi**<br>
        <ol><li>Project manager dimana harus mejadi pengawas dari anggota – anggotanya bilamana saat anggota lalai dengan tugas – tugasnya, Ketua berhak menegur dan bagi anggota tidak berhak melawan jika ditegur, dan untuk Ketua sendiri tidak berhak semena-mena \dengan jabatanya.<br>
        <li>Programmer dimana dia bertanggung jawab untuk membuat dan menyempurnakan suatu program.<br>
        <li>Database administrator dimana dia bertanggung jawab merancang dan mengelola database<br>
        <li>Analis dimana dia bertugas memberikan gambaran project dan alur pengkoding pada programmer.</ol><br> 
​    **2.4** **Lingkup tanggung jawab**<br>
        <ol><li>Manager adalah seseorang mempunyai tanggung jawab dan tugas yang besar dalam sebuah tim, tidak hanya terfokus pada hal-hal yang teknis sifatnya. Manager juga harus mampu memajemen tim dengan baik, agar target projek dapat tercapai. Selain itu memberi pengarahan, memonitoring kinerja tim, serta serta membagi tugas juga bagian tanggung jawab dari seorang manager.<br>
        <li>Programmer Dalam hal ini, seorang programer bertugas untuk mengimplementasikan dari sistem yang sudah dirancang didesain. Programmer dituntut dapat menuliskan code program dengan baik, dan efesien. Hal ini dimaksudakan untuk menghindari terjadinya banyak error dalam proses implementasinya.<br>
        <li>Database Administrator adalah seseorang yang bertanggung jawab terhadap pengaturan, pembuatan, dan rekam jejak segala jenis dokumen yang terlibat dalam proyek. Mulai dari proposal dan kontrak proyek, sampai dengan hasil sampling atau percobaan dalam proses pembangunan proyek. Disamping dokumen, hal-hal yang berkaitan dengan komunikasi antara anggota proyek dengan perusahaan dan vendors juga harus dikelola oleh Administrator. Agar segalanya berjalan dengan lancar, biasanya Administrator sudah memiliki standar dokumen dan prosedur yang harus diikuti oleh seluruh tim proyek, agar proses administrasi berjalan dengan efektif dan secara efisien. <br>
        <li>Analisys sistem, Banyak hal yang harus dilakukan oleh seorang sistem analis, terutama yang berkaitan dengan pemecahan masalah. Seorang sistem analis harus mampu menganalisa segala kemungkinan dari pemasalahan yang ada, dan dapat mengasilkan solusi yang tepat dari permasalahan tersebut. Menentukan sistem yang tepat merupakan bagian dari tugas seorang sistem analis, sehingga kinerja tim dapat berjalasan secara efesien.</ol> <br>


**3.** **Proses Manajerial**<br>
    **3.1** **Tujuan dan prioritas manajemen**<br>
        <ol><li>Prioritas Jadwal <br>
            Prioritas jadwal yang dilakukan pada saat ini adalah membuat sistem yang akan dibuat, dokumen  projek, jadwal  kegiatan, struktur pembuatan projek dan organisasi<br>
        <li>Budget <br>
            Prioritas budget untuk project ini lebih ditekankan pada kualitas hardware dan requirtment proyek.  <br>
        <li>Kemampuan (Kualitas dan reusability)  <br>
            Projek yang kami buat saat ini mempunyai kelebihan dalam memanajemen pembuatan proyek, juga berbasis desktop yang membuat konsumen merasa lebih budah dalam interaksinya.<br></ol>
    **3.2** **Asumsi-asumsi, ketergantungan/keterkaitan, dan batasan-batasan**<br>
<ol>a. Asumsi <br>
Adapun aplikasi yang sejenis sistem informasi absensi dan penggajian berbasis web dan mobile. <br>
b. Keterkaitan dan Batasan  <br>
Dalam projek yang kami buat adapun beberapa software desktop yang mendukungnya, seperti xampp sebagai perantara mysql database. Namun ada batasannya, yaitu tidak bisa digunakan secara online. <br></ol>

 **3.3** **Manajemen resiko**<br>
<table border="1">
    <tr>
        <td>Resiko</td>
        <td>Solusi</td>
    </tr>
    <tr>
        <td>Kerusakan Teknologi dan bahan produk</td>
        <td>Mengganti dengan teknologi yang baru dengan sistem yang sama</td>
    </tr>
    <tr>
        <td>Estimasi biaya dan waktu yang tidak realistis</td>
        <td>Membuat berapa biaya estimasi, desain untuk kerja, merekam dan menganalisa project yang akan dibuat</td>
    </tr>
    <tr>
        <td>Pengembangannya terlalu sulit secara teknis</td>
        <td>Analisis teknis, analisa biaya manfaat, analisa software, simulasi software</td>
    </tr>
</table>

**3.4** **Mekanisme monitoring dan kontroling**<br>
        <ol>a. Pertemuan proyek II seminggu 3 kali<br>
        b. Repository bersama di Github</ol><br>
   
**3.5** **Perencanaan staf**
        <ol>1.  Priliyandi (Project Manager)<br>
        2.  Riyanwar Setiadi (Programmer)<br>
        3. Setyo Abiansah (Database Administrator)<br>
        4.  Uum Khumaeroh (Analisis Sistem)<br></ol>
        
 **4.**  **Proses teknis**<br>
**4.1** **Metoda, tool, dan teknik**<br>
        <ol>Proyek II ini akan menggunakan tools, metoda, dan teknologi yaitu :<br>
            1. Android Studio<br>
            2. Laravel<br>
            3. laragon<br>
            4. SubimeText3<br>
            5. Bootstrap<br></ol>
            
**4.2** **Dokumentasi perangkat lunak**<br>
<ol> Dokumentasi perangkat lunak yang digunakan berdasarkan standar internasional IEEE, karena telah menyediakan kerangka kerja yang menghubungkan seluruh spektrum siklus hidup perangkat lunak</ol>
   
**4.3** **Fungsi-fungsi pendukung proyek**
        <ol>Semua pendukung proyek akan selesai secara bertahap</ol>

**5.** **Paket pekerjaan, jadwal, dan budget**<br>
**5.1** **Paket pekerjaan**<br>
    <center>Paket Pekerjaan</center>
    <table border="1">
        <tr>
            <th>Bulan</th>
            <th>Februari</th>
            <th>Maret</th>
            <th>April</th>
            <th>Mei</th>
        </tr>
        <tr>
            <th>Minggu</th>
            <th>1 2 3 4</th>
            <th>1 2 3 4</th>
            <th>1 2 3 4</th>
            <th>1 2 3 4</th>
        </tr>   
        <tr>
            <td>Nama</td>
        </tr>
        <tr>
            <td>1. Priliyandi</td>
            <td>W W W V</td>
            <td>V V V V</td>
            <td>V V X X</td>
            <td>X X Y Y</td>
        </tr>
        <tr>
            <td>2. Riyanwar Setiadi</td>
            <td>W W V V</td>
            <td>V V V V</td>
            <td>V V V V</td>
            <td>V X Y Y</td>
        </tr>
        <tr>
            <td>3. Setyo Abiansah</td>
            <td>W W W V</td>
            <td>V V V V</td>
            <td>V V X X</td>
            <td>X X Y Y</td>
        </tr>
        <tr>
            <td>4. Uum Khumaeroh</td>
            <td>W W W V</td>
            <td>V V X X</td>
            <td>V V X X</td>
            <td>X Y Y Y</td>
        </tr>
    </table>
    <ol>
        Kategori Kegiatan : <br>
(V) :Pengerjaan projek dari koding dan pencarian referensi hingga
dilakukan pengecekan. <br>
(W) :Persiapan projek dan pengumpulan sumber daya yg di perlukan. <br>
(X) :Pengecekan hasil projek, berupa pengecekan terhadap error code pada
program. <br>
(Y) :Melakukan perbaikan projek yang sudah dicek. <br>
    </ol>

**5.2** **Ketergantungan/keterkaitan**<br>
        <center>Tabel Ketergantungan dan Keterkaitan</center>
        <table border="1">
            <tr>
                <th>Dari</th>
                <th>Tugas Untuk</th>
                <th>Keterkaitan</th>
            </tr>
            <tr>
                <td>Manager</td>
                <td>Anggota</td>
                <td>Tugas manager adalah untuk mengawasi anggota-anggotanya jika saat mengerjakan projek anggotanya lalai dengan tugasnya ketua tersebut berhak untuk menegur anggotanya dan yang Menjadi anggota tidak berhak untuk melawan</td>
            </tr>
            <tr>
                <td>Programmer</td>
                <td>Tester</td>
                <td>Salah satu tugas Tester yaitu untuk mengecek jika saat programmer salah dalam melakukan pengkodingan tersebut agar bisa langsung di perbaiki.</td>
            </tr>
            <tr>
                <td>Administrator</td>
                <td>Manager</td>
                <td>Tugas Administrator bertanggung jawab untuk menyiapkan dokumen-dokumen yang akan di gunakan untuk penggarapan dan saat selesai hasil akhir projek.</td>
            </tr>
            <tr>
                <td>Analis</td>
                <td>Programmer</td>
                <td>Yang bertugas sebagai analisis yaitu memberi suatu gambaran projek dan pengkodian pada programer. </td>
            </tr>
            <tr>
                <td>Tester</td>
                <td>Programmer</td>
                <td>Bertugas sebagai memberi masukanmasukan kepada Programer untuk membuat program yang sedang di buat.</td>
            </tr>
        </table>

**5.3** **Kebutuhan Sumber Daya**<br>
    Untuk pembuatan aplikasi ini akan dikerjakan oleh 4 (empat) orang, dapat
dilihat pada tabel berikut ini :<br>
<center>Tabel Kebutuhan Sumber Daya Manusia</center>
<table border="1">
    <tr>
        <th>No</th>
        <th>Nama Personal</th>
        <th>Job</th>
    </tr>
    <tr>
        <td>1.</td>
        <td>Priliyandi</td>
        <td>Project Manager</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>Riyanwar Setiadi</td>
        <td>Programmer</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>Setyo Abiansah</td>
        <td>Administrator</td>
    </tr>
    <tr>
        <td>4.</td>
        <td>Uum Khumaeroh</td>
        <td>Analis</td>
    </tr> 
</table>

<center>Tabel Kebutuhan Sumber Daya Hardware</center>
<table border="1">
    <tr>
        <th>No</th>
        <th>Jenis Hardware</th>
        <th>Kebutuhan Hardware</th>
    </tr>
    <tr>
        <td>1.</td>
        <td>Processor</td>
        <td>Minimal Core i3 atau diatasnya</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>Memory(RAM)</td>
        <td>Minimal 4GB atau diatasnya</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>Penyimpanan(Harddisk)</td>
        <td>Minimal Free Space 2GB atau lebih</td>
    </tr>
</table>

**5.4** Alokasi budget dan sumber daya<br>
    Berikut adalah rincian biaya yang diperlukan untuk pengerjaan proyek kami,
dapat dilihat pada tabel dibawah ini.<br>
         <center>Tabel Estimasi Biaya Software</center>
<table>
    <tr>
        <th>No</th>
        <th>Kebutuhan Software</th>
        <th>Biaya</th>
    </tr>
    <tr>
        <td>1.</td>
        <td>Windows 7,10 dan Linux</td>
        <td>Rp 2.500.000,-</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>SublimeText3</td>
        <td>Rp 1.350.000,-</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>Xampp</td>
        <td>Rp 99.000,-</td>
    </tr>
    <tr>
        <td>4.</td>
        <td>Android Studio</td>
        <td>Rp 50.000,-</td>
    </tr>
    <tr>
        <td>5.</td>
        <td>Laragon</td>
        <td>Rp 0,-</td>
    </tr>
    <tr>
        <td>6.</td>
        <td>Laravel</td>
        <td>Rp 0,-</td>
    </tr>
</table>

<center>Tabel Estimasi Biaya Hardware</center>
<table border="1">
    <tr>
        <th>No</th>
        <th>Jenis Hardware</th>
        <th>Kebutuhan Hardware</th>
        <th>Biaya</th>
    </tr>
    <tr>
        <td>1.</td>
        <td>Laptop</td>
        <td>Minimal Core i3 atau lebih, Minimal RAM 4GB atau lebih,
        Kapasitas memori minimal 4GB atau lebih</td>
        <td>Rp 7.000.000,-</td>
    </tr>
</table>

**5.5** **Jadwal**<br>
    <ol>Untuk menyelesaikan Aplikasi Simulasi Manajemen Proyek Perangkat Lunak
ini diperlukan waktu kurang lebih 5 bulan. Dimana rincian jadwal kerja
pembuatan aplikasi ini dapat dilihat pada tabel estimasi kerja berikut :<br></ol>
<html>
<head>
</head>
<body>
    <img src="Gambar/Jadwal.png" height="300px" width="500px;"/>
</body>
</html>