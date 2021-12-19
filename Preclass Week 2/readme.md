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

# **BASH Linux Command Lists**

1. **find**

Menggunakan find juga mencari file dan direktori. Perbedaannya adalah, Anda menggunakan perintah find untuk mencari file dalam direktori tertentu. Sebagai contoh, perintah find /home/ -name notes.txt akan mencari file bernama notes.txt di dalam direktori home dan subdirektorinya. Variasi lain saat menggunakan find adalah:


Untuk menemukan file dalam penggunaan direktori saat ini, find . -name notes.txt


Untuk mencari direktori gunakan, / -type d -name notes.txt


2. **sudo**

Singkatan dari "SuperUser Do", perintah ini memungkinkan Anda untuk melakukan tugas-tugas yang memerlukan izin administratif atau root. Namun, tidak disarankan untuk menggunakan perintah ini untuk penggunaan sehari-hari karena mungkin mudah terjadi kesalahan jika Anda melakukan kesalahan.

3. **ping**

Gunakan perintah ping untuk memeriksa status konektivitas Anda ke server. Misalnya, hanya dengan memasukkan ping google.com, perintah akan memeriksa apakah Anda dapat terhubung ke Google dan juga mengukur waktu respons.

4. **wget**

Baris perintah Linux sangat berguna — Anda bahkan dapat mengunduh file dari internet dengan bantuan perintah wget. Untuk melakukannya, cukup ketik wget diikuti dengan tautan unduhan.

5. **history**

Ketika Anda telah menggunakan Linux untuk jangka waktu tertentu, Anda akan segera menyadari bahwa Anda dapat menjalankan ratusan perintah setiap hari. Dengan demikian, menjalankan perintah history sangat berguna jika Anda ingin meninjau kembali perintah yang telah Anda masukkan sebelumnya.

6. **man**

Bingung tentang fungsi perintah Linux tertentu? Jangan khawatir, Anda dapat dengan mudah mempelajari cara menggunakannya langsung dari shell Linux dengan menggunakan perintah man. Misalnya, memasukkan man tail akan menampilkan instruksi manual dari perintah tail.

7. **echo**

Perintah ini digunakan untuk memindahkan beberapa data ke dalam sebuah file. Misalnya, jika Anda ingin menambahkan teks, "Halo, nama saya John" ke dalam file bernama name.txt, ketikkan echo Halo, nama saya John >> name.txt

# **Study Case Proses Update dari Branch Development > Staging > Production**

Disini saya menggambarkan fitur update di website Dumbways.

**Langkah-Langkah**

1. Buat folder untuk init git
2. Tambahkan file yang akan diupdate
3. Add lalu commit
4. Remote dan push
5. Buat branch
6. Checkout ke staging
7. Push dan pull
8. Merge

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
