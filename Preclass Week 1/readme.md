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

