# Jarkom-Modul-1-I06-2022
<strong>Nama Anggota :
1. Rycahaya Sri Hutomo    (5025201046)
2. Agnesfia Anggraeni     (5025201059)
3. Rahel Cecilia Purba    (5025201155) </strong>

## 1. Sebutkan web server yang digunakan pada "monta.if.its.ac.id"!

Ketikkan ```http``` pada Capture Filter, kemudian double klik pada data yang kolomnya berisi tulisan ```200 OK```
![soal 1](https://user-images.githubusercontent.com/94664966/191895635-fe9562cf-6283-4772-adb9-ec762673feaf.PNG)
<br><br>
Web server yang digunakan pada "monta.if.its.ac.id" adalah server : ```nginx/1.10.3\r\n```
![Soal 1 1](https://user-images.githubusercontent.com/94664966/191895789-905977cc-95df-4f50-b0af-8564c65fe2c3.PNG)

## 2. Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq ?

Ketik `http contains "monta.if.its.ac.id"` pada Capture Filter.Kemudian klik data yang bertuliskan ``detailTopik``. Perlu diingat bahwa nama akhirnya bukan `detailTopik` melainkan `194`
![Soal 2](https://user-images.githubusercontent.com/94664966/191898141-32eb3e5e-d073-46e9-a4d7-f74fa2708470.PNG)
<br><br>
Klik Tab ``File``, kemudian Klik ``Export Object`` lalu pilih ``HTTP`` 
![Soal 2 1](https://user-images.githubusercontent.com/94664966/191898299-77701d98-6807-4a27-9273-93cf0c1cef2e.png)

Kemudian save file  dengan nama file `194`
![Soal 2 2](https://user-images.githubusercontent.com/94664966/191899077-8d9ff3bf-6220-440b-b586-b9acd31997fa.png)

Kemudian buka file `194` pada PC anda, dan terlihat Judul TA yang dibuka oleh Ishaq adalah <strong>Evaluasi Unjuk Kerja User Space Filesystem (FUSE)</strong>
![Soal 2 3](https://user-images.githubusercontent.com/94664966/191899153-89bfd74f-e62e-4a49-a91c-6dbf820e9d25.png)


## 3. Filter sehingga wireshark hanya menampilkan paket yang menuju port 80!

Cara menampilkan paket yang hanya menuju port 80 adalah dengan menggunakan ```tcp.dstport == 80.``` di display filter. 
![no 3](https://user-images.githubusercontent.com/112471006/191893444-9af2d7d3-e47a-4ef3-8fba-0a9c537804f2.png)

## 4. Filter sehingga wireshark hanya mengambil paket yang berasal dari port 21!
Cara menampilkan paket yang hanya berasal dari port 21 dengan menggunakan `tcp.srcport == 21` pada capture filter.
![Soal 4](https://user-images.githubusercontent.com/94664966/192077262-8ea83012-5a98-4192-9411-a9f851283b63.PNG)
![Soal 4 1](https://user-images.githubusercontent.com/94664966/192077263-cb25d97c-f57b-4ad0-9cfc-3a4ecee431c5.PNG)
![Soal 4 2](https://user-images.githubusercontent.com/94664966/192077265-93e6c9f8-4bb3-4b14-bfb0-6e76dc2cdbf9.PNG)


## 5. Filter sehingga wireshark hanya mengambil paket yang berasal dari port 443!

Cara menampilkan paket yang hanya berasal port 443 adalah dengan menggunakan ```tcp.srcport == 443``` di display filter.
![no 5 (1)](https://user-images.githubusercontent.com/112471006/191997656-720d0d96-255b-4ddf-8f72-b5209559d605.png)
![no 5 (2)](https://user-images.githubusercontent.com/112471006/191997660-73d3a65d-f7a8-4aad-b800-86aa7b5ff386.png)
![no 5 (3)](https://user-images.githubusercontent.com/112471006/191997627-6ec99d01-1058-4999-99bc-a85421db322c.png)
![no 5 (4)](https://user-images.githubusercontent.com/112471006/191997637-a73c23d2-527a-49e9-8be8-b70a9cbdbf4a.png)
![no 5 (5)](https://user-images.githubusercontent.com/112471006/191997643-7afc1175-fee2-45f2-b3b6-e3bf7cd23a9f.png)
![no 5 (6)](https://user-images.githubusercontent.com/112471006/191997645-48c547cd-2227-4e2e-90d1-a0e5aa0a05c7.png)
![no 5 (7)](https://user-images.githubusercontent.com/112471006/191997649-22de2332-288e-4928-8e6e-3140c2e44a14.png)
![no 5 (8)](https://user-images.githubusercontent.com/112471006/191997651-8872d3c2-1e9a-45a9-8717-7fda8d8ebec1.png)
![no 5 (9)](https://user-images.githubusercontent.com/112471006/191997655-2be9b7c0-62d4-4e42-ba43-b7cc76b27cb7.png)

## 6. Filter sehingga wireshark hanya menampilkan paket yang menuju ke lipi.go.id!

Pertama-tama kita mencari tahu ip address dari lipi.go.id dari cmd menggunakan ```ping```
![no 6 (ip)](https://user-images.githubusercontent.com/112471006/191999678-a3c2d8e8-6394-4e11-831b-27c8b728b07c.png)
kemudian kita diminta untuk mencari tahu paket yang menuju ip address tersebut dengan menggunakan
```ip.dst == 203.160.128.158``` di display filter.
![No 6](https://user-images.githubusercontent.com/112471006/191998778-ece8561a-f1ef-4600-8cf8-9078d5d213cd.png)

## 7. Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!

Pertama-tama kita mencari tahu ip address kita dari dari cmd menggunakan ```ipconfig```
![no 7 (ip)](https://user-images.githubusercontent.com/112471006/191999958-8ff99f75-c1bc-46fe-8eec-3e914583e64d.png)<br>
kemudian kita diminta untuk mencari tahu paket yang berasal dari ip addres kita dengan menggunakan ```ip.src == 192.168.1.10``` di display filter.
![no 7](https://user-images.githubusercontent.com/112471006/192001108-23dcc036-0707-4ca2-8304-33409a34b475.png)

## Studi Kasus untuk No. 8 - 10
Di sebuah planet bernama Viltrumite, terdapat Kementerian Komunikasi dan Informatika yang baru saja menetapkan kebijakan baru. Dalam kebijakan baru tersebut, pemerintah dapat mengakses data pribadi masyarakat secara bebas jika memang dibutuhkan, baik dengan maupun tanpa persetujuan pihak yang bersangkutan. Sebagai mahasiswa yang sedang melaksanakan program magang di kementerian tersebut, kalian mendapat tugas berupa penyadapan percakapan mahasiswa yang diduga melakukan tindak kecurangan dalam kegiatan Praktikum Komunikasi Data dan Jaringan Komputer 2022. Selain itu, terdapat sebuah password rahasia (flag) yang diduga merupakan milik sebuah organisasi bawah tanah yang selama ini tidak sejalan dengan pemerintahan Planet Viltrumite. Tunggu apa lagi, segera kerjakan tugas magang tersebut agar kalian bisa mendapatkan pujian serta kenaikan jabatan di kementerian tersebut!

## 8. Telusuri aliran paket dalam file .pcap yang diberikan, cari informasi berguna berupa percakapan antara dua mahasiswa terkait tindakan kecurangan pada kegiatan praktikum. Percakapan tersebut dilaporkan menggunakan protokol jaringan dengan tingkat keandalan yang tinggi dalam pertukaran datanya sehingga kalian perlu menerapkan filter dengan protokol yang tersebut.

Ketik <code>tcp.stream eq 12</code>. Kemudian, klik kanan baris data pertama. Lalu, pilih <code>Follow</code> dan klik <code>TCP Stream</code>.
![8_tcp stream eq 12](https://user-images.githubusercontent.com/94436711/192070630-744f6df5-851b-4d59-aea0-c8e617fd7dad.png)<br>

Maka, percakapan antara dua mahasiswa terkait tindakan kecurangan pada kegiatan praktikum dapat ditampilkan seperti gambar di bawah.<br>
![8_percakapan](https://user-images.githubusercontent.com/94436711/192070812-d4c0eeb8-27a7-48a9-ac2a-de394480ed82.png)

## 9. Terdapat laporan adanya pertukaran file yang dilakukan oleh kedua mahasiswa dalam percakapan yang diperoleh, carilah file yang dimaksud! Untuk memudahkan laporan kepada atasan, beri nama file yang ditemukan dengan format ``[nama_kelompok].des3`` dan simpan output file dengan nama ``flag.txt``!

1. Ketik <code>tcp.dstport == 9002</code> (melalui percakapan antara kedua mahasiswa, dapat diketahui bahwa file dikirim melalui port 9002).</li>
2. Kemudian, klik kanan baris pertama.
3. Pilih <code>Follow</code>
4. Klik <code>TCP Stream</code>!
![9_tcp dstport == 9002](https://user-images.githubusercontent.com/94436711/192071013-3f341e07-069f-4c34-967f-86a47abdd152.png)
5. Muncul tulisan kode. Kemudian, ganti <code>show data as</code> yang semula <code>ASCII</code> menjadi <code>raw</code><br>
![9_sallted](https://user-images.githubusercontent.com/94436711/192071615-5ee947db-7eee-4356-b51d-6e7920724bc2.png)
6. Simpan dan rename file menjadi <code>I06.des3</code><br>
![9_renameI06 des3](https://user-images.githubusercontent.com/94436711/192071317-ea2c1ba8-a78c-45cc-9417-77ddd0c6c705.png)
7. Decrypt file tersebut, lalu rename menjadi <code>flag.txt</code><br>
![9_flag txt](https://user-images.githubusercontent.com/94436711/192071797-9174c1e3-a753-40b7-bf5a-b5c4f866dea6.png)

Namun kami mengalami kesulitan saat mengerjakan nomor 9, yaitu kami tidak dapat men-decrypt file tersebut.

## 10. Temukan password rahasia (flag) dari organisasi bawah tanah yang disebutkan di atas!
Setelah di-decrypt, dalam file ``flag.txt`` tertulis password rahasianya.

Namun disini kami mengalami kesulitan dalam mengerjakan no 10, dikarenakan no 9 tidak dapat kami selesaikan.





