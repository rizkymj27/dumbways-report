# **Rangkuman Materi Minggu ke-1**

## **DevOps**

DevOps adalah kombinasi dari development dan operations yang bertugas sebagai penghubung antara divisi development & operations untuk mempercepat proses development hingga rilis produk ke publik. DevOps diharapkan agar melancarkan pekerjaan development dan operation teams dengan cara mengkomunikasikan hal terkait.

Pekerjaan DevOps dapat digambarkan sebagai pengulangan tak terbatas yang meliputi:
Plan, Code, Build, Test, Release, Deploy, Operate, Monitor.

**DevOps Process**

<img src=https://user-images.githubusercontent.com/95203293/145389940-2d540a0f-8227-461e-afcc-1f952bb54619.png width="500" height="250">

## **CI/CD Concept**

CI/CD adalah kepanjangan dari Continuous Integration dan Continuous Deployment, yang berarti metode untuk mengirimkan perubahan code secara terus menerus hingga aplikasi dapat rilis ke publik dengan otomatis.

**Continuous Integration** merupakan proses otomatisasi untuk developer ketika melakukan perubahan code agar dapat diperiksa terlebih dahulu sebelum masuk ke tahap contiuous deployment.

**Continuous Deployment** merupakan proses otomatisasi agar aplikasi yang telah siap di deploy ke server dapat diteruskan hingga aplikasi dapat diakses secara publik.

**Kelebihan CI/CD** antara lain: dapat menyebarkan aplikasi sesuai dengan permintaan, dapat mengurangi resiko aplikasi tidak berfungsi ketika produksi, dapat dengan mudah di rollback ke versi sebelumnya jika terjadi error.

Beberapa daftar tools yang dapat digunakan untuk CI/CD antara lain: Jenkins, GitLab CI, Bitbucket Pipeline, GitHub Actions, dan Circle CI.

## **Operating Systems Concept**

**Sistem Operasi** adalah penghubung antara software dan hardware agar dapat digunakan oleh pengguna.

Contoh OS untuk komputer desktop: Windows, Linux, MacOS

Contoh OS untuk server: Linux, WIndows Server

**Functions of Operating System** merupakan list fungsi yang harus dimiliki sebuah sistem operasi. 

Berikut di antaranya: 
1. Memory Management 
2. Processor Management 
3. File Management 
4. Device Management 
5. I/O Management
6. Command Interpretation
7. Networking 
8. Security
9. Storage Management
10. Secondary Storage Management

**Distribusi Linux** adalah sistem operasi yang dibangun dari kernel linux dengan penambahan komponen lain berupa module, aplikasi, service, ataupun package lain agar tercipta sistem operasi dengan tujuan yang spesifik yang telah ditentukan oleh developer.

Distribusi Linux yang cocok untuk server antara lain: Ubuntu, CentOS, Debian, OpenBSD, FreeBSD, Fedora.

64-bit processors lebih direkomendasikan untuk multi-tasking.

## **Virtualization Concept**

**Virtualization** adalah teknologi yang memungkinkan kita untuk membagi sebuah resource menjadi lebih kecil dari perangkat yang memiliki resource besar. Atau dapat menjalankan beberapa sistem operasi secara bersamaan.

**Hypervisor** adalah program untuk membuat dan menjalankan virtual machine.

**Virtual Machine** adalah sistem komputer yang berjalan di atas sistem lain, memiliki akses ke beberapa sumber daya yang ada di bawahnya. Seperti CPU, Memory, dan Storage. Serta dapat mengakses USB, Network Card, dan sebagainya.

**Kelebihan menggunakan virtualization** antara lain:

1. Kemudahan backup dan recovery server-server yang dijalankan di dalam sebuah virtual machine, karena akan melakukan backup secara keseluruhan termasuk konfigurasi sistem.
2. Kemudahan deployment karena dapat di clone sebanyak mungkin dengan konfigurasi sistem yang sama.
3. Dapat memindahkan virtual machine ke server lain jika terjadi kerusakan hardware.

**Tools** yang dapat digunakan untuk teknologi **virtualisasi** antara lain:

1. VMWare
2. VirtualBox
3. Microsoft Hyper-V
4. QEMU
5. Proxmox

## **Container Concept**

**Container** adalah sebuah paket aplikasi yang dikemas dengan dependensinya sehingga aplikasi dapat berjalan dengan cepat tanpa perlu mengkonfigurasi sebuah environment tertentu pada sistem operasi.

Dengan teknologi container kita dapat menjalankan aplikasi yang sudah berbentuk container tersebut di sistem operasi Windows ataupun Linux.

<img src=https://user-images.githubusercontent.com/95203293/145400054-9cfc1c4d-f26a-4ad1-b8e1-969d76a77a4a.png width="500" height="400">

**Tools** yang dapat digunakan untuk teknologi **container** antara lain:

1. Docker
2. Podman
3. Containerd
4. LXC atau LXD

**Kelebihan menggunakan teknologi container** antara lain:

1. Isolasi lingkungan terdapat pada tingkat aplikasi/service, sehingga deployment akan lebih fleksibel per-service.
2. Maintenance sistem dapat lebih fokus per service, sehingga ketika ada update pada salah satu service dengan versi yang lebih baru tidak akan mempengaruhi service yang lain.
3. Dapat dengan mudah di scale aplikasi sehingga lebih stabil ketika ada salah satu aplikasi yang mati.

## **Cloud Computing Concept**

**Cloud Computing** adalah pengiriman berbagai layanan melalui internet, seperti data storage, servers, databases, networking, dan software.

**Kelebihan Cloud Computing** antara lain:
1. Menghemat biaya
2. Meningkatkan produktivitas
3. Kecepatan dan efisiensi
4. Keamanan data

<img src=https://user-images.githubusercontent.com/95203293/145402049-d96dd209-b181-4fdf-9c68-52584a64368e.png width="500" height="600">

Cloud computing terdiri dari dua jenis, yaitu:

1. **Private Cloud** : merupakan layanan yang disediakan kepada sejumlah orang tertentu. Biasanya hanya diterapkan dalam suatu perusahaan, yang memiliki data dalam jumlah besar tetapi bersifat rahasia.
2. **Public Cloud** : merupakan layanan yang disediakan kepada publik. Biasanya digunakan untuk mempublikasikan data mereka secara publik, baik itu dalam bentuk object seperti foto, video, dokumen, dan sebagainya.

<img src=https://user-images.githubusercontent.com/95203293/145403343-bdd51b42-9d47-4378-ad0c-eb830c89b434.png width="700" height="300">

Karakteristik dari private cloud antara lain:
1. Dapat di scale secara mandiri, dengan pengetahuan teknis
2. Management data hanya dapat diakses oleh staf IT tertentu
3. Tidak perlu membayar biaya layanan jika orang menggunakannya

Contoh dari private cloud:
1. Server yang dapat diakses melalui VPN
2. Aplikasi yang hanya dapat diakses melalui jaringan internet lokal

Karakteristik dari public cloud antara lain:
1. Dapat di scale dengan mudah
2. Ada biaya layanan yang harus dibayar
3. Sangat fleksibel, dapat dihapus jika tidak digunakan, dapat di create ulang jika ingin digunakan.

Contoh dari public cloud:
1. Amazon Web Service
2. Google Cloud Platform
3. Microsoft Azure

## **Basic Network**

**Jaringan komputer** adalah interkoneksi antara 2 komputer atau lebih, yang saling terhubung dengan media transmisi kabel atau tanpa kabel (wireless). Komputer saling terkoneksi apabila komputer tersebut bisa saling bertukar data/informasi, berbagai resource yang dimiliki seperti file, printer, hard disk, dll.

**Jenis-jenis jaringan**:
1. **PAN (Personal Area Network)** merupakan jaringan komunikasi satu perangkat dengan perangkat lainnya dalam jarak yang sangat dekat. Contohnya komputer yang dihubungkan ke internet.
2. **LAN (Local Area Network)** merupakan jaringan komputer yang jaringannya hanya mencakup wilayah kecil. Contohnya jaringan komputer kampus, gedung, dan kantor.
3. **MAN (Metropolitan Area Network)** merupakan jaringan yang mencakup wilayah seperti provinsi atau negara bagian. Dalam hal ini jaringan menghubungkan beberapa buah jaringan kecil ke dalam lingkungan area yang lebih besar. Contohnya jaringan beberapa kantor cabang sebuah bank.
4. **WAN (Wide Area Network)** merupakan jaringan yang biasanya sudah menggunakan media wireless, sarana satelit ataupun kabel serat optik. Contohnya jaringan ATM internasional yang tersebar di seluruh negara.

## **Network Types**

Jaringan komputer memiliki tipe-tipe sebagai berikut:
1. **Jaringan client-server**, server adalah komputer yang menyediakan fasilitas bagi komputer-komputer lain di dalam suatu jaringan. Client adalah komputer-komputer yang menerima atau menggunakan fasilitas yang disediakan oleh server. 

Keunggulannya antara lain: kecepatan akses tinggi serta keamanan dan backup data lebih baik.

Kelemahannya antara lain: biaya operasional lebih mahal, diperlukan adanya satu komputer khusus untuk server, dan kelangsungan jaringan sangat bergantung pada server.

<img src=https://user-images.githubusercontent.com/95203293/145517764-6e95d36b-49ab-4730-891d-c340eeac6b3a.png width="500" height="300">

2. **Jaringan peer to peer** merupakan jaringan non-dedicated server, karena server tidak berperan sebagai server murni, melainkan sekaligus dapat berperan sebagai workstation. Jadi, setiap workstation dapat bertindak sebagai server atau client.

Keunggulannya antara lain: antar komputer dalam jaringan ini dapat berbagi fasilitas yang dimiliki, dan kelangsungan kerja jaringan tidak bergantung pada satu server.

<img src=https://user-images.githubusercontent.com/95203293/145518398-1a5d1f65-db18-4841-878f-8a523ce0909b.png width="400" height="300">

## **Network Topology**

**Topology** adalah metode atau cara yang digunakan agar bisa menghubungkan satu komputer dengan komputer lainnya. Struktur atau jaringan yang digunakan yaitu dengan menggunakan kabel atau nirkabel.

**Jenis-jenis topologi**:
1. **Mesh**, topologi ini menerapkan hubungan antar sentral secara penuh. Jumlah saluran harus disediakan untuk membentuk jaringan mesh. Merupakan jaringan peer to peer.

<img src=https://user-images.githubusercontent.com/95203293/145521826-dec1e855-1143-4fd4-91e3-241d4b052a5e.png width="400" height="300">

**Karakter Mesh** antara lain: tidak ada client server semuanya dapat bertidak sebagai client dan server, peer to peer, serta bentuk mesh yang sangat sederhana ialah array dua dimensi tempat masing-masing simpul juga saling terhubung dengan keempat tetangganya.

2. **Bus**, topologi ini dibangun dengan kabel coaxial yang dibentang kemudian beberapa komputer dihubungkan pada kabel tersebut. Kedua ujung jaringan harus diakhiri dengan sebuah terminator.

<img src=https://user-images.githubusercontent.com/95203293/145522280-82d6a6db-aff3-4c88-8e7c-d12594a12074.png width="600" height="250">

**Karakteristik Bus** antara lain: setiap komputer dalam suatu jaringan terhubung melalui kabel tunggal sebagai media transmisi, kabel tunggal tersebut dapat berfungsi sebagai backbone yang menjadi jalur data, serta setiap ujung kabel utama terpasang terminator untuk bisa menghentikan sinyal dan mencegah terjadinya tabrakan sinyal.

3. **Ring**, topologi ini merupakan semua workstation dan server dihubungkan sehingga terbentuk sebuah pola lingkaran. Tiap workstation atau server akan menerima dan melewatkan informasi dari satu komputer ke komputer lain.

<img src=https://user-images.githubusercontent.com/95203293/145522815-cdef0a56-6605-4247-8c21-081b1086ca8b.png width="400" height="280">

**Karakteristik Ring** antara lain: Setiap komputer atau perangkat yang terhubung secara langsung satu dengan lainnya dalam satu jaringan, Dalam proses pengiriman data pada suatu waktu hanya bisa dilakukan oleh satu titik dengan proses pengiriman satu jalur, Setiap paket data atau informasi bisa mengalir melalui kanan atau kiri titik sehingga hal ini dapat menghindari collision, dan Kerusakan pada satu titik bisa mengakibatkan kerusakan pada titik-titik lainnya yang saling terhubung dalam satu jaringan.

4. **Star**, topologi ini masing-masing workstation dihubungkan secara langsung ke server. Sehingga jalur bandwith akan semakin lebar dan meningkatkan kinerja jaringan secara keseluruhan.

<img src=https://user-images.githubusercontent.com/95203293/145523841-dc7d244e-25dd-41bc-89cc-fb8e17ea6aba.png width="400" height="280">

**Karakteristik Star** antara lain: Dari berbagai node dapat berkomunikasi secara langsung pada central node dengan trafik yang mengalir dari node central, Dapat dengan mudah dikembangkan karena dari masing-masing node mempunyai kabel yang saling terhubung, dan Jaringan tidak mudah terganggu yang dapat disebabkan mengalami suatu kerusakan.

5. **Tree**, merupakan gabungan dari beberapa topologi yang ada (star dan bus), yang bisa memadukan kinerja dari beberapa topologi.

<img src=https://user-images.githubusercontent.com/95203293/145524427-7d52ad8e-273d-4d5f-80d6-7be5bfd60386.png width="500" height="280">

**Karakteristik Tree** antara lain: Proses pengiriman data dari klien pengirim ke klien penerima harus melalui hub (pusat kendali), Pusat data dan kendali jaringan dipegang oleh sebuah hub sebagai kabel utama yang menghubungkan beberapa hub, Terdapat kabel utama (backbone) yang berfungsi sebagai penghubung antar jaringan, dan Mempunyai tingkatan dalam jaringan.

## **IP Address**

**IP Address** adalah Internet Protocol Address, yaitu serangkaian angka unik milik perangkat yang terhubung ke jaringan yang lebih luas. IP Address diperlukan agar perangkat dan server dapat bertukar informasi satu sama lain.

**Jenis IP Address**:
1. **IP Address Publik** adalah alamat IP yang digunakan router untuk berkomunikasi dengan jaringan yang lebih luas. Diberikan oleh penyedia layanan internet (ISP), dimana terdapat informasi sehingga dapat dilacak.
2. **IP Address Private** adalah alamat IP pribadi yang dimiliki oleh setiap perangkat, entah itu laptop, smart TV atau smartphone yang terhubung ke jaringan lokal.

<img src=https://user-images.githubusercontent.com/95203293/145525679-889f7dec-8c26-4562-bf98-eacb3c248efc.png width="700" height="400">

**IP Address Dinamis** merupakan pemberian IP secara otomatis dalam sebuah jaringan baik itu bersifat IP publik atau IP private. IP ini akan berubah-ubah setiap waktu.

**IP Address Statis** merupakan pemberian IP yang tidak akan berubah, harus dikonfigurasi manual jika ingin menggunakan IP statis.

![Screenshot from 2021-12-08 14-41-30](https://user-images.githubusercontent.com/95203293/145526295-acbf837b-2901-4a18-9748-b5fe3917b93c.png)

## **OSI Concept**

**OSI** adalah 
