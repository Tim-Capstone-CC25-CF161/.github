# Safana (System Analytics Fauna Nusantara)

Proyek ini mengembangkan sebuah platform web yang memungkinkan pengguna mengunggah gambar dan secara otomatis mendeteksi apakah gambar tersebut mengandung hewan langka atau dilindungi menggunakan model **RetinaNet dengan backbone ResNetFPN**. Model dilatih menggunakan dataset khusus berisi spesies terancam punah di Indonesia yang telah dianotasi dengan Roboflow. Setelah proses deteksi, sistem memberikan informasi lengkap mencakup nama spesies (lokal & ilmiah), status konservasi, sebaran, ancaman utama, hingga tindakan dukungan yang dapat dilakukan.

Lebih lanjut, sistem menampilkan **peta interaktif** yang menunjukkan lokasi hasil deteksi dan merekomendasikan **BKSDA terdekat** berdasarkan data lokasi pengguna secara real-time. Hal ini mendukung potensi kolaborasi publik untuk pelaporan kejadian dan perlindungan langsung di lapangan.

Berikut adalah Halaman Utama Website Safana:
![image](https://github.com/user-attachments/assets/998f74e9-fc6e-4dc9-9334-a4f7b51c437f)

## Cara menggunakan fitur deteksi di Website Safana
1. Pada halaman utama anda bisa menekan tombol "Unggah & Cari Tahu!" yang akan membuka sebuah modal yang menunjukkan pilihan sumber foto yang akan di deteksi
![image](https://github.com/user-attachments/assets/6828191a-7fe1-4e72-b66b-408b71fc540f)
(Pada saat menekan tombol "Unggah & Cari Tahu!" akan muncul terlebih dahulu permintaan untuk izin akses lokasi, izinkan untuk bisa menggunakan fitur ini lebih lanjut)

2. Apabila memilih sumber foto dari galeri maka akan membuka file explorer dan anda diharuskan untuk memilih foto yang akan diprediksi
![image](https://github.com/user-attachments/assets/9fe43c4a-8f85-4b16-ad7e-15dfb259ca85)
Tampilan setelah memilih foto:
![image](https://github.com/user-attachments/assets/e9497cfd-3828-4f12-8698-d939022867eb)

4. Apabila memilih gunakan kamera maka akan terbuka halaman yang mengakses kamera dan anda bisa langsung menangkap foto dihalaman tersebut
![image](https://github.com/user-attachments/assets/4aa4aceb-6f27-4597-9e7b-e017a33a128b)
Tampilan setelah mengambil foto:
![image](https://github.com/user-attachments/assets/d090fb76-17cc-445e-822d-cec125063ed6)

6. Setelah dikirim proses deteksi akan berlangsung
![image](https://github.com/user-attachments/assets/7485e347-4beb-4dcf-9cfb-5d2924320045)

7. Setelah selesai maka akan muncul popup selesai dan anda bisa menekan tombol "Lihat Hasil" untuk melihat hasil lebih lanjut
![image](https://github.com/user-attachments/assets/91542ed1-7226-476d-9c1d-79b8cd57267f)
![image](https://github.com/user-attachments/assets/20e68883-8e16-4393-8018-978350dce259)

8. Dalam halaman Hasil Deteksi anda bisa menekan tombol "Lihat BKSDA Terdekat" untuk melihat BKSDA didekat anda dan anda bisa klik nomornya untuk bisa langsung menelepon BKSDA tersebut untuk pelaporan
![image](https://github.com/user-attachments/assets/38901df4-028a-40b3-ba54-fe3bbbc3a269)

9. Anda juga dapat menekan tombol "Lihat Detail Informasi Hewan" untuk mengetahui lebih lanjut mengenai hewan tersebut
![image](https://github.com/user-attachments/assets/b7529bba-9923-4114-a9d8-1df2a02674b8)

10. Berikut adalah tampilan bila dalam foto yang diberikan tidak ditemukan adanya hewan langka
![image](https://github.com/user-attachments/assets/990732e8-3df1-4f41-98ea-b791b013e125)
