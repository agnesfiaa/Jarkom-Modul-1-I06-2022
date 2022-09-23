# Jarkom-Modul-1-I06-2022
Nama Anggota :
1. Rycahaya Sri Hutomo   5025201046
2. Agnesfia Anggraeni    5025201059
3. Rahel Cecilia Purba   5025201155

<strong> No 1. Sebutkan web server yang digunakan pada "monta.if.its.ac.id"!</strong>

Ketikkan ```http``` pada Capture Filter, kemudian double klik pada data yang kolomnya berisi tulisan ```200 OK```
![soal 1](https://user-images.githubusercontent.com/94664966/191895635-fe9562cf-6283-4772-adb9-ec762673feaf.PNG)

Web server yang digunakan pada "monta.if.its.ac.id" adalah server : ```nginx/1.10.3\r\n```
![Soal 1 1](https://user-images.githubusercontent.com/94664966/191895789-905977cc-95df-4f50-b0af-8564c65fe2c3.PNG)

<strong> No 2. Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq ? </strong>

Ketik `http contains "monta.if.its.ac.id"` pada Capture Filter.Kemudian klik data yang bertuliskan ``detailTopik``. Perlu diingat bahwa nama akhirnya bukan `detailTopik` melainkan `194`
![Soal 2](https://user-images.githubusercontent.com/94664966/191898141-32eb3e5e-d073-46e9-a4d7-f74fa2708470.PNG)

Klik Tab File, kemudian Klik Export Object lalu pilih http 
![Soal 2 1](https://user-images.githubusercontent.com/94664966/191898299-77701d98-6807-4a27-9273-93cf0c1cef2e.png)

Kemudian save file  dengan nama file `194`
![Soal 2 2](https://user-images.githubusercontent.com/94664966/191899077-8d9ff3bf-6220-440b-b586-b9acd31997fa.png)

Kemudian buka file `194` pada PC anda, dan terlihat Judul TA yang dibuka oleh Ishaq adalah <strong>Evaluasi Unjuk Kerja User Space Filesystem (FUSE)</strong>
![Soal 2 3](https://user-images.githubusercontent.com/94664966/191899153-89bfd74f-e62e-4a49-a91c-6dbf820e9d25.png)


<strong> No 3. Filter sehingga wireshark hanya menampilkan paket yang menuju port 80!</strong>

Cara menampilkan paket yang hanya menuju port 80 adalah dengan menggunakan ```tcp.dstport == 80.``` di display filter. 
![no 3](https://user-images.githubusercontent.com/112471006/191893444-9af2d7d3-e47a-4ef3-8fba-0a9c537804f2.png)

