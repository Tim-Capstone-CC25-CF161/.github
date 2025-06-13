# Safana (System Analytics Fauna Nusantara)

Proyek ini mengembangkan sebuah platform web yang memungkinkan pengguna mengunggah gambar dan secara otomatis mendeteksi apakah gambar tersebut mengandung hewan langka atau dilindungi menggunakan model **RetinaNet dengan backbone ResNetFPN**. Model dilatih menggunakan dataset khusus berisi spesies terancam punah di Indonesia yang telah dianotasi dengan Roboflow. Setelah proses deteksi, sistem memberikan informasi lengkap mencakup nama spesies (lokal & ilmiah), status konservasi, sebaran, ancaman utama, hingga tindakan dukungan yang dapat dilakukan.

Lebih lanjut, sistem menampilkan **peta interaktif** yang menunjukkan lokasi hasil deteksi dan merekomendasikan **BKSDA terdekat** berdasarkan data lokasi pengguna secara real-time. Hal ini mendukung potensi kolaborasi publik untuk pelaporan kejadian dan perlindungan langsung di lapangan.

Berikut adalah Halaman Utama Website Safana:
![image](https://github.com/user-attachments/assets/998f74e9-fc6e-4dc9-9334-a4f7b51c437f)

Apabila anda baru mengunjungi website maka akan ditampilkan sebuah modal funfact seperti berikut:
![image](https://github.com/user-attachments/assets/1749784b-fef6-46a9-bf6b-08d6b9dd0058)

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

## Halaman lain yang tersedia
1. Peta Sebaran
![image](https://github.com/user-attachments/assets/5b86cb3d-6050-4321-87bd-ca75a5e7e0e6)
![image](https://github.com/user-attachments/assets/e2347c02-14e9-4dbf-8cc7-700bb1f13526)

3. Galeri
![image](https://github.com/user-attachments/assets/b82ba52b-07ca-4216-9664-a877d93d8d19)

5. List BKSDA
![image](https://github.com/user-attachments/assets/cca86c8d-6801-4a23-9677-5cfa1852789a)

6. Daftar
![image](https://github.com/user-attachments/assets/2e955d36-c29f-44be-ac7b-07531a980731)

7. Masuk
![image](https://github.com/user-attachments/assets/4d49aa34-c7f6-430e-b3aa-a54b3a4871db)

Berikut adalah tampilan dan halaman tambahan apabila pengguna telah daftar dan login pada website:
1. Perubahan pada navigasi
![image](https://github.com/user-attachments/assets/0b779f72-4063-4548-8109-b7687726effc)

2. Halaman Profil
![image](https://github.com/user-attachments/assets/d639bab6-27eb-4b76-9e0b-83e56e215892)

3. Halaman Riwayat Deteksi
![image](https://github.com/user-attachments/assets/83401fc7-6292-47a3-8e07-beb110150877)

## Fitur tambahan
Anda dapat memasang website ini selayaknya aplikasi biasa
![image_2025-06-11_16-14-31](https://github.com/user-attachments/assets/60d88d32-8ec4-4e12-9bc2-04b97a50fa3f)
![Screenshot_20250611-161557](https://github.com/user-attachments/assets/30888ec6-299b-4510-9aa1-adead6dd05ac)

Setelah diinstall tersedia juga beberapa shortcut untuk menuju langsung ke halaman tertentu yang bisa anda manfaatkan
![image](https://github.com/user-attachments/assets/8a7b8027-4cc5-4663-aa5f-2f8a0058977a)

## Repositori yang tersedia
1. [Frontend](https://github.com/Tim-Capstone-CC25-CF161/frontend-safana-deteksi-hewan-langka)
2. [Backend](https://github.com/Tim-Capstone-CC25-CF161/backend-safana-deteksi-hewan-langka)
3. [Machine Learning](https://github.com/Tim-Capstone-CC25-CF161/object-detection-model-dev)

## Credits
Website ini dibuat oleh: Tim CC25-CF161

Yang terdiri dari:
- (ML) MC208D5Y1488 - Mario Valerian Rante Ta'dung - Universitas Hasanuddin
- (ML) MC610D5X1898 - Rika Rostika Afipah - Universitas Logistik dan Bisnis Internasional
- (ML) MC189D5X0806 - Attiya Dianti Fadli - Universitas Bengkulu
- (FEBE) FC012D5X1290 - Ghefira Putri Athaya Fairuz - Telkom University
- (FEBE) FC189D5Y0434 - Muhammad Fachrurrozi - Universitas Bengkulu
- (FEBE) FC369D5Y2212 - Ramdan Rohendi - STMIK AMIKBANDUNG

