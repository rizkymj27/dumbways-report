# **Dokumentasi Proses Setiap Perintah yang Dipelajari di Materi Manage Server With Terminal**

## **Text Editor with Nano**

1. Buat directori dan file untuk diedit dengan perintah nano

![image](https://user-images.githubusercontent.com/95203293/147381987-0a5fb680-944c-4440-ba7d-8d0c99614cf7.png)

2. Edit teks di dalam nano menggunakan berbagai perintah

![image](https://user-images.githubusercontent.com/95203293/147382008-8983d93a-e03f-4206-994c-f493b9abb43b.png)

![image](https://user-images.githubusercontent.com/95203293/147382010-c642ab77-6cd6-4225-b5e0-67e7632bcf9a.png)

## **Text Manipulation**

- Gunakan perintah cat untuk melihat isi file

![image](https://user-images.githubusercontent.com/95203293/147382027-f3cc10dd-aeb1-4f8a-8ee1-4bec33afac4b.png)

- Gunakan perintah cat untuk menambahkan/mengoverwrite teks pada file

![image](https://user-images.githubusercontent.com/95203293/147382056-30514e1a-c2be-4c9f-9c63-979377eb11ec.png)

- Copy file teks lalu gabungkan dengan perintah cat berdasarkan urutan yang diinginkan

![image](https://user-images.githubusercontent.com/95203293/147382070-b18d6e7a-3d75-4d22-97a4-8a802891297c.png)

- Edit file dengan perintah nano lalu urutkan dengan perintah cat berdasarkan urutan yang diinginkan

![image](https://user-images.githubusercontent.com/95203293/147382090-b14bd175-b2ab-45ef-8d3e-1c74429666b2.png)

- Gunakan perintah sed untuk mengganti suatu kata pada file, serta gunakan perintah grep untuk melakukan pencarian teks dalam file

![image](https://user-images.githubusercontent.com/95203293/147382102-eeac99af-7e15-40a3-87b4-f6ff0a1662df.png)

- Buat teks untuk diurutkan dengan perintah sort

![image](https://user-images.githubusercontent.com/95203293/147382392-569a927e-08a3-40ea-9fb0-d03a6bf7c054.png)

- Sort untuk mengurutkan teks

![image](https://user-images.githubusercontent.com/95203293/147382400-2d9d0724-410c-4e05-a47c-b97cbd90124c.png)

- Sort descending

![image](https://user-images.githubusercontent.com/95203293/147382421-bec099e3-a198-47b9-9a34-f98bcf8774cc.png)

- Echo untuk mencetak string/pesan

![image](https://user-images.githubusercontent.com/95203293/147382430-5dafb58c-0eea-4c58-9bab-28ff228a818a.png)

- Cat untuk menambahkan teks pada file

![image](https://user-images.githubusercontent.com/95203293/147382456-14c3b811-b226-4527-a942-416ea2ff42da.png)

# **Dokumentasi Proses Setiap Perintah yang Dipelajari di Materi Manage Monitoring Server With Terminal**

## **htop**

![image](https://user-images.githubusercontent.com/95203293/147382480-8a3a5767-bbb2-4e05-ba0f-a4a064df86d6.png)

![image](https://user-images.githubusercontent.com/95203293/147382484-9f26b1c6-3ed1-4d2d-9dcd-45703cc84ced.png)

## **Nmon**

![image](https://user-images.githubusercontent.com/95203293/147382494-2839f0b0-1ecc-491b-b489-05f87489926f.png)

![image](https://user-images.githubusercontent.com/95203293/147382497-ec180b49-bc98-46f0-8324-edf5cf05206a.png)

## **lsof**

![image](https://user-images.githubusercontent.com/95203293/147382510-8b0c2de6-72d2-4f7d-bcdd-27700f7e4fdc.png)

## **ps**

![image](https://user-images.githubusercontent.com/95203293/147382514-1cef54c2-19db-4c52-9080-2bb73bc8116b.png)

![image](https://user-images.githubusercontent.com/95203293/147382519-ba5324c2-38ae-4da4-b324-c3bd63938f5b.png)

## **ufw**

<img width="585" alt="image" src="https://user-images.githubusercontent.com/95203293/147382534-6782d1bf-24d3-41eb-841c-08b98047a6f0.png">

![image](https://user-images.githubusercontent.com/95203293/147382555-f6687eb4-5fc9-4980-853f-d7a3a29c1002.png)

![image](https://user-images.githubusercontent.com/95203293/147382562-967d677e-9dfe-4f99-92f2-e649529c58ba.png)

<img width="585" alt="image" src="https://user-images.githubusercontent.com/95203293/147382564-f4afb7d7-c256-4993-aec9-c137e7831d83.png">

# **Another Command for Monitoring With Terminal**

## **top**

Perintah top digunakan untuk menampilkan semua proses real-time yang berjalan dan aktif dalam daftar yang diurutkan dan diperbarui/diupdate secara teratur. 

Ini menampilkan penggunaan CPU, penggunaan Memori, Memori Swap, Ukuran Cache, Ukuran Buffer, PID Proses, Pengguna, Perintah, dan banyak lagi.

![image](https://user-images.githubusercontent.com/95203293/147382639-7873e37f-8274-442a-a7b9-77c75f5e395e.png)


## **vmstat**

Perintah Linux VmStat digunakan untuk menampilkan statistik memori virtual, utas kernel, disk, proses sistem, blok I/O, interupsi, aktivitas CPU, dan banyak lagi.

![image](https://user-images.githubusercontent.com/95203293/147382658-2aaf2871-c446-4e28-aaad-2383e2ebcc0d.png)

## **iostat**

iostat adalah alat sederhana yang akan mengumpulkan dan menampilkan statistik perangkat penyimpanan input dan output sistem.
 
Alat ini sering digunakan untuk melacak masalah kinerja perangkat penyimpanan termasuk perangkat, disk lokal, disk jarak jauh seperti NFS.

![image](https://user-images.githubusercontent.com/95203293/147382682-2142ab9b-ffb4-41eb-a792-366a66376c5c.png)

## **collectl**

Collectl adalah utilitas berbasis baris perintah dan kaya fitur lainnya, yang dapat digunakan untuk mengumpulkan informasi tentang sumber daya sistem Linux seperti penggunaan CPU, memori, jaringan, inode, proses, nfs, TCP, soket, dan banyak lagi.

![image](https://user-images.githubusercontent.com/95203293/147382688-a0264f48-9f71-4bed-9c1b-b32fa3071a71.png)

# **CMS Manajer**

## **Content Management System**

Content Management System adalah suatu software yang bertugas dalam mengubah, mengelola, serta mempublikasikan suatu konten website. Content Management System juga akan membantu setiap penggunanya dalam berkolaborasi mengelola konten website.

Sederhananya, Content Management System adalah suatu program yang berguna untuk memudahkan berbagai pekerjaan yang berkaitan dengan website. Kehadiran CMS juga akan membantu para pengguna dalam membuat website tanpa harus mengetahui kemampuan coding ataupun programming yang memusingkan.

## **Contoh Content Management System**

**WordPress**
WordPress adalah salah satu aplikasi Content Management System yang sifatnya lebih open source. Itu artinya, setiap orang bisa mengakses kode asalnya dan mengembangkan software buatan mereka sendiri dengan berdasarkan kode itu sendiri.

Untuk saat ini, WordPress adalah CMS yang paling banyak digunakan oleh para pengguna di seluruh negara.

## **CMS Manajer**

**CMS Manajer (Cadabra Multiple Server Manajer)**

Merupakan platform yang dibuat untuk memudahkan pengguna yang tidak memiliki pengetahuan server agar dapat memanajemen server-server tersebut dalam satu dashboard dan memudahkan kita untuk menginstal aplikasi yang dibutuhkan dengan sekali klik serta dapat menginstal CMS (Content Management System) seperti WordPress. Selain itu CMS Manajer juga mengoptimalkan konfigurasi kernel, security dan performance pada server.

![image](https://user-images.githubusercontent.com/95203293/147382765-baa1d183-c8a3-400b-9691-f7167a6697bd.png)

CMS Manajer menyediakan fitur marketplace dan app management, yang dapat dimanfaatkan untuk install aplikasi yang kita perlukan.

![image](https://user-images.githubusercontent.com/95203293/147382770-fb43369c-6a06-4e4a-bfb0-34c2d4cf91b3.png)

Terdapat beberapa pilihan aplikasi yang dapat di install, kedepannya akan terus di update jumlah aplikasi yang akan di support pada CMS Manajer. Selanjutnya klik aplikasi yang akan kita install pada server kita, misalkan kita pilih LEMP. Dimana server kita akan otomatis diinstallkan aplikasi Nginx, PHP, MySQL.


