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
