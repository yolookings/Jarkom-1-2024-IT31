# Jarkom-1-2024-IT31

## Anggota Kelompok IT31 :

| Nama Lengkap         | NRP        |
| -------------------- | ---------- |
| Maulana Ahmad Zahiri | 5027231010 |
| Dzaky Faiq Fayyadhi  | 5027231047 |

## Write Up

# Advance Sanity Check

- tcp contains "username"

- http.request.method == "POST"

- http contains ".php"

- http contains "Clue3.txt"

![alt text](<POST upload.php HTTP1.1.png>)

￼`cGVud29yZA==` Kemudian lanjut decode kata tersebut pada platform decode sehingga menghasilkan string = penword

lalu terdapat flag berupa :
`flag-mu: JarkomIT{8uK4n_S4n1ty_b1a5A_nNg9t4F2b5hhjWnYXz3rtRo57Su5g7MTESM91HNORWKx7soLpZ3CRIKK}`

## EZ

- tcp > follow > tcp stream,
- lalu terdapat “jawabannya jawaban”
- kemudian untuk port 1234 dari bilah kiri bawah

`Benar! Ini flag-mu: JarkomIT{BiAr_aman_Pake_sSh_XkqtsFzqvkQN7WGDVpVdCwQwp3zfWapqYj6r4REavoAUP7YwIAcDEZ}
`

## FTP login:

Mencari login successful

Lalu terdapat username dan passwordnya

￼![alt text](<Apa username yang berhasil digunakan untuk FTP login.png>)

## Pegawai Negeri Sebelah

tcp contain “nNnM%coQuF”terus find nNnM%coQuF, lalu input Vero Tampubolon

Lalu search taufan, dan mendapatkan jabatab berupa Analis Kebijakan

Lalu menampilkan yang paling awal dan paling akhir

`Benar! Ini flag-mu: JarkomIT{Tum8eN_p45SnYa_Ku4t_B1aS4Nya_y4TlFN0REl3joQLdlDkYMLBLKL3GcDd6mGXEFwzbcWqTeBfCO9ppM4h}`

￼
![alt text](<nc 10.15.42.60 53000.png>)


# Illegal Breakthrough

1.	Tcp contains”.php”
   
2.	 ![image](https://github.com/user-attachments/assets/eff0b7fd-f6e1-49f1-94f7-334266f78538)

3.	Ip address korban ada di Host : 172.21.88.207

4.	Port yang digunakan sebagai webserver ada di Host : 1917

5.	Dimana endpoint ada di paling atas /ww1.php

6.	Tools apa yang digunakan oleh attacker?
   ![image](https://github.com/user-attachments/assets/a97f974a-da82-452f-a68d-1c265d3ce091)

Fuzz Faster U Fool v2.1.0-dev disingkat ffuf-v2.1.0-dev

7.	Apa kredesial yang berhasil digunakan oleh hacker
Redbaron:fly1ng4c3


## Packets Barrage

1. IP Address Attacker ada di Source ketika membuka file

![image](https://github.com/user-attachments/assets/63989d0b-0046-4f92-8359-fffc1bdb47c1)

2. Berapa total attempt?
   
   cari menggunakan http.response.code == 200

   ![image](https://github.com/user-attachments/assets/686099ce-747c-489c-a582-244315f0b15e)

3. Apa nama file yang didownload oleh hacker?

   File > Export Object > http > Filter R > Save > Extract

4. Apa isi dari file ?

  tinggal buka


## InneRCE

1. frame contains "POST"

   ![image](https://github.com/user-attachments/assets/f6ff2516-f325-4eb9-9c61-569c805f270e)

   UTC beda 7 jam jadi

2. Nyari 1 1 sampe ke stream  55 ada server-app

3. idzoyyshell.php

4. ![image](https://github.com/user-attachments/assets/0572b4e5-ac06-4936-9d08-08ecce894edf)
   di stream 49 ada bakuls dia menggunakan whoami

5. ![image](https://github.com/user-attachments/assets/4f0c7b7a-c117-4e23-9aa6-212a3f562fe0)

   di stream 52 copas yang di antara %20()%20 trus decrypt menggunakan base 64 = pls rate soal ini



   


