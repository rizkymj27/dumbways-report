# **Instalasi Linux Ubuntu**

## **Langkah-Langkah**

1. Perangkat yang dibutuhkan: Flashdisk 8GB+, Hardisk/SSD minimal 30GB, Windows 10 (*untuk dual boot*)
2. Identifikasi BIOS Mode
3. Download File ISO Ubuntu
4. Download Rufus
5. Burn File ISO ke Flashdisk Menggunakan Rufus
6. Restart Laptop dan Masuk ke BIOS Mode Untuk Menginstall Ubuntu via Flashdisk
7. Pilih Bahasa
8. Pilih Bahasa pada Keyboard
9. Pilih Jenis Instalasi
10. Pilih Tipe Instalasi (Dual Boot atau Single Boot)
11. Alokasi Partisi pada Hardisk/SSD
12. Pilih Zona Waktu
13. Registrasi User
14. Tunggu Hingga Proses Instalasi Selesai
15. Instalasi Selesai, Restart Laptop
16. Masuk ke Boot Menu lalu Pilih Ubuntu
17. Selesai

# **Instalasi Ubuntu Server**

## **Langkah-Langkah**

1. Persiapkan VMWare dan File ISO Ubuntu Server
2. Install VMWare
3. Create a new virtual machine
4. Install OS later
5. Pilih guest OS dan versinya
6. Cari direktori file ISO Ubuntu Servernya
7. Ubah pengaturan hardware sesuai dengan kebutuhan
8. Power on pada Ubuntu server
9. Install Ubuntu Server

# **BASH Linux Command Lists**

1. **find**

Menggunakan find juga mencari file dan direktori. Perbedaannya adalah, Anda menggunakan perintah find untuk mencari file dalam direktori tertentu. Sebagai contoh, perintah find /home/ -name notes.txt akan mencari file bernama notes.txt di dalam direktori home dan subdirektorinya. Variasi lain saat menggunakan find adalah:


Untuk menemukan file dalam penggunaan direktori saat ini, find . -name notes.txt


Untuk mencari direktori gunakan, / -type d -name notes.txt

![image](https://user-images.githubusercontent.com/95203293/147377664-dd18deab-0c73-48d4-bea0-22809355410a.png)


2. **sudo**

Singkatan dari "SuperUser Do", perintah ini memungkinkan Anda untuk melakukan tugas-tugas yang memerlukan izin administratif atau root. Namun, tidak disarankan untuk menggunakan perintah ini untuk penggunaan sehari-hari karena mungkin mudah terjadi kesalahan jika Anda melakukan kesalahan.

3. **ping**

Gunakan perintah ping untuk memeriksa status konektivitas Anda ke server. Misalnya, hanya dengan memasukkan ping google.com, perintah akan memeriksa apakah Anda dapat terhubung ke Google dan juga mengukur waktu respons.

![image](https://user-images.githubusercontent.com/95203293/147377689-181ef21e-a06b-4baf-adf4-3f92386a50a3.png)


4. **wget**

Baris perintah Linux sangat berguna — Anda bahkan dapat mengunduh file dari internet dengan bantuan perintah wget. Untuk melakukannya, cukup ketik wget diikuti dengan tautan unduhan.

![image](https://user-images.githubusercontent.com/95203293/147377702-ac9b9e85-01aa-469b-a041-61882732c221.png)


5. **history**

Ketika Anda telah menggunakan Linux untuk jangka waktu tertentu, Anda akan segera menyadari bahwa Anda dapat menjalankan ratusan perintah setiap hari. Dengan demikian, menjalankan perintah history sangat berguna jika Anda ingin meninjau kembali perintah yang telah Anda masukkan sebelumnya.

![image](https://user-images.githubusercontent.com/95203293/147377712-8c5a96b7-d8da-4f7c-a783-23f49857ba1a.png)


6. **man**

Bingung tentang fungsi perintah Linux tertentu? Jangan khawatir, Anda dapat dengan mudah mempelajari cara menggunakannya langsung dari shell Linux dengan menggunakan perintah man. Misalnya, memasukkan man tail akan menampilkan instruksi manual dari perintah tail.

![image](https://user-images.githubusercontent.com/95203293/147377718-f5fea68f-1eda-45d0-bbd2-8ba83a37f3de.png)


7. **echo**

Perintah ini digunakan untuk memindahkan beberapa data ke dalam sebuah file. Misalnya, jika Anda ingin menambahkan teks, "Halo, nama saya John" ke dalam file bernama name.txt, ketikkan echo Halo, nama saya John >> name.txt

![image](https://user-images.githubusercontent.com/95203293/147377724-3e895824-7b6e-451e-8161-ab3323536dc5.png)


# **Study Case Proses Update dari Branch Development > Staging > Production**

Disini saya menggambarkan fitur update di website Dumbways.

**Langkah-Langkah**

1. Buat folder untuk init git

![image](https://user-images.githubusercontent.com/95203293/147377738-dbd3f328-e97e-46aa-85d1-3f7f059b6517.png)


2. Tambahkan file yang akan diupdate

![image](https://user-images.githubusercontent.com/95203293/147377750-b3ef56b0-cea5-4f9f-bcba-b85ab272e75f.png)


3. Add lalu commit

![image](https://user-images.githubusercontent.com/95203293/147377757-4ec0d38e-3931-493e-9cc8-39b616348370.png)


4. Remote dan push

![image](https://user-images.githubusercontent.com/95203293/147377764-c3cf0f1e-761d-47da-a309-94c4693b5d58.png)


5. Buat branch

![image](https://user-images.githubusercontent.com/95203293/147377766-a8d30c39-f20f-4e6c-92f2-b5f0601e2824.png)

6. Checkout ke staging

![image](https://user-images.githubusercontent.com/95203293/147377770-0f0694e8-89e7-4d26-9f0a-e1ea4e4891e0.png)


7. Push dan pull

![image](https://user-images.githubusercontent.com/95203293/147377773-aba6c7c2-725f-4f63-a226-18f46420d79d.png)


8. Merge

![image](https://user-images.githubusercontent.com/95203293/147377776-ec046922-cc16-41e3-ad41-20bfa041d420.png)



# **Proses pembuatan CI/CD menggunakan Github Actions**

**Github Actions** adalah alat otomasi yang hadir di Github, Alat ini sangat membantu kita untuk membuat berbagai keperluan otomasi seperti unit test, auto deploy.
Dengan Github Actions kita juga bisa menentukan saat-saat apa saja otomasi akan terpanggil.

## **Langkah-Langkah**

1. Mempersiapkan Github

Persiapkan repository pada github, Selanjutnya, init projek dengan github lalu tambahkan remote repository yang sudah buat di github.

2. Unit Test

Unit Test adalah pengujian atau testing dengan otomasi. Dengan Unit Test kita dengan mudah melakukan pengujian terhadap aplikasi dengan mudah.
Contohnya di Continuous Integration ini, sebagai contoh saat kita melakukan pull request ke suatu branch, maka dengan CI kita bisa menjalankan testing di github actions secara otomatis.

3. Membuat Workflows Untuk Continuous Integration

Dengan CI, integrasi antar fitur satu dengan lainnya dapat mudah dan cepat dilakukan secara otomatis.


Workflows:
- Membuat nama untuk action
- Definisikan kapan action kita akan di trigger atau dijalankan
- Membuat job, artinya action apa aja yang akan dikerjakan nantinya

4. Continuous Deployment

Ini adalah kelanjutan dari CI, setelah semua teringrasi dengan baik, tentunya tujuan akhir adalah melakukan deploy. dengan metode ini kita bisa membuat otomasi. 


Sebagai contoh ketika kode teman kerja sudah aman dan melakukan merge ke branch utama, maka kita bisa mentrigger otomasi CD untuk melakukan deploy otomatis ke server. Dengan begitu kita tidak perlu repot-repot manual mengupdate kode kita di server, kita cukup melakukan push ke branch misalnya, lalu CD akan mendeploy seacara otomatis.

5. Uji Coba

Untuk melakukan uji coba, commit semua yang sudah dibuat sebelumnya.
Lihat workflow CI dan CD apakah sudah berjalan secara benar tanpa error.
