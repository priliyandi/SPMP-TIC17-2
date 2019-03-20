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










1.** **Pendahuluan**<br><br>
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

        <ol>Kami menggunakan model sashimi, Proses perangkat lunak sashimi (Takeuchi + Nonaka1986-nnpd) sangat mirip dengan model waterfall, kecuali bahwa fase tumpang tindih untuk menunjukkan bahwa persyaratan tidak dapat diselesaikan sampai arsitektur setidaknya sebagian dieksplorasi, dan arsitektur tidak dapat diselesaikan sampai desain modul setidaknya sebagian dieksplorasi, dan sebagainya.</ol><br>
        <ol>Proses sashimi paling tepat untuk proyek-proyek berukuran sedang di mana komunikasi antar fase dapat ditangani secara improvisasi. Untuk proyek yang lebih besar, proyek berisiko tinggi, atau proyek di mana beberapa pengembang berpengalaman, pendekatan spiral mungkin lebih baik.</ol><br>
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

