# Jarkom_Modul1_2025_k41


|nama kelompok                | nrp         |
|-----------------------------|-------------|
| Balqis Sani Sabillah        |  5027241002 |   
| Alnico Virendra Kitaro Diaz |  5027241081 |

## Soal no 14 ##
Setelah gagal mengakses FTP, Melkor melancarkan serangan brute force terhadap  Manwe. Analisis file capture yang disediakan dan identifikasi upaya brute force Melkor. 
[link file](https://drive.google.com/drive/folders/13rf0AlzUrkNhUWbBNt9tIVSimw3njKqd) nc 10.15.43.32 3401

### Jawaban ###
![14](images/14.png) 

A. Terdapat 50038 packet  

![14A](images/14A.png) 

B. Pilih Packet HTTP karena biasanya memuat username, namun tdk selalu maka lakukan pengecekan dengan klik kanan -> Follow -> HTTP Stream    
![14B](images/14B.png) 

c. Dipacket yg sama terdapat kolom Stream di bagian kanan bawah  
![14C](images/14C.png)   

d. Di dalam Packet yang sama terdapat user-agent yang memuat tools apa yang digunakan   
![14D](images/14D.png)  

## Soal no 15 ##
Melkor menyusup ke ruang server dan memasang keyboard USB berbahaya pada node Manwe. Buka file capture dan identifikasi pesan atau ketikan (keystrokes) yang berhasil dicuri oleh Melkor untuk menemukan password rahasia.
[link file](https://drive.google.com/drive/folders/1aHSRMoEgQBsA-4I2wWatFxAy3laumcgb) nc 10.15.43.32 3402

## Soal no 16 ##
Melkor semakin murka ia meletakkan file berbahaya di server milik Manwe. Dari file capture yang ada, identifikasi file apa yang diletakkan oleh Melkor.
[link file](https://drive.google.com/drive/folders/1aJf_PQGXwr4fxd79df8nd7NzL7SsN6U9) nc 10.15.43.32 3403

### Jawaban ###
<img width="790" height="523" alt="Image" src="https://github.com/user-attachments/assets/aa675771-9432-4e0f-a337-ea5ef5957812" />        

A. Cari Packet FTP karena biasanya sebagai tempat login, sehingga bisa memuat username dan password client  
<img width="397" height="150" alt="Image" src="https://github.com/user-attachments/assets/71b092c5-9c3d-4760-8d1c-d595820e667d" />   

B. Salah satu ciri - ciri file malware adalah .exe dan terdapat 5 file dengan akhiran .exe ( q.exe, w.exe, e.exe, r.exe, t.exe )  
<img width="89" height="135" alt="Image" src="https://github.com/user-attachments/assets/4da7f5c0-e1ee-4f41-9f7b-4706216a8ff2" />    

C. Untuk mengintegritaskan file FTP-DATA ( q.exe, w.exe, e.exe, r.exe, t.exe) dengan **sha256sum** maka kita harus mengsave file packet dengan row agar dapat menyimpan payload benar - benar apa adanya (bit by bit)  
bash : sha256sum <namafile>

<img width="634" height="30" alt="Image" src="https://github.com/user-attachments/assets/5bcda994-4f82-4a12-a877-02e5aa12d0ba" />   

D. <img width="609" height="35" alt="Image" src="https://github.com/user-attachments/assets/917457dd-0e7b-445e-97d1-d458a4e6be86" />  

E. <img width="561" height="30" alt="Image" src="https://github.com/user-attachments/assets/7b1b1cad-3543-4138-8d49-e2102c534991" /> 

F. <img width="559" height="34" alt="Image" src="https://github.com/user-attachments/assets/d2d3cdc3-a999-4753-a10b-576452fab9b8" /> 

G. <img width="564" height="32" alt="Image" src="https://github.com/user-attachments/assets/6307d2df-b5f8-4a4c-9459-391d5b13229a" />

## Soal no 17 ##
Manwe membuat halaman web di node-nya yang menampilkan gambar cincin agung. Melkor yang melihat web tersebut merasa iri sehingga ia meletakkan file berbahaya agar web tersebut dapat dianggap menyebarkan malware oleh Eru. Analisis file capture untuk menggagalkan rencana Melkor dan menyelamatkan web Manwe.
[link file](https://drive.google.com/drive/folders/10UNx8BhvbyCDhHGHS7D7zmyvFbCf41ze) nc 10.15.43.32 3404

### Jawaban ###
<img width="703" height="345" alt="Image" src="https://github.com/user-attachments/assets/92fb208e-0fef-4853-9be2-b6b9488484dd" />

A. Untuk menemukan suspicius file yaitu pergi ke file -> Export Object -> HTTP
   <img width="741" height="113" alt="Image" src="https://github.com/user-attachments/assets/9641d4e5-0701-4934-869d-425dfc179f62" />  
B.
<img width="738" height="117" alt="Image" src="https://github.com/user-attachments/assets/b53287c5-0d81-4d50-99a4-96e8e9e49d07" />   

C. Sama seperti diatas, kita harus mensave file knr.exe dulu

<img width="648" height="38" alt="Image" src="https://github.com/user-attachments/assets/814f8bee-4f0e-440f-8460-723860c914b3" /> 

## Soal no 18 ##   
Karena rencana Melkor yang terus gagal, ia akhirnya berhenti sejenak untuk berpikir. Pada saat berpikir ia akhirnya memutuskan untuk membuat rencana jahat lainnya dengan meletakkan file berbahaya lagi tetapi dengan metode yang berbeda. Gagalkan lagi rencana Melkor dengan mengidentifikasi file capture yang disediakan agar dunia tetap aman.
[link file](https://drive.google.com/drive/folders/1R4-D1WnsDVrT73UlkacjY0Ntag42AFUy) nc 10.15.43.32 3405

### Jawaban ### 
<img width="710" height="394" alt="Image" src="https://github.com/user-attachments/assets/36b4889f-5dcb-4674-960f-0c1b5f983377" />    

A. Untuk melihat file berisi malware yaitu pergi ke file -> Export Object -> SMB, nahh ciri - ciri file malware biasanya ada .exe nahh disini ada 2 file     
<img width="740" height="225" alt="Image" src="https://github.com/user-attachments/assets/56c9a0aa-e8fd-4a0f-a5fd-f3bda5ac9508" />    

B. File ke 2 

<img width="748" height="221" alt="Image" src="https://github.com/user-attachments/assets/ac7e469f-eb40-44d5-8563-f7d01535d93b" />  

C.   
<img width="603" height="38" alt="Image" src="https://github.com/user-attachments/assets/1cbf4ed9-fc56-4bcd-90b9-26cdef79d8b0" />   

D. 

<img width="599" height="44" alt="Image" src="https://github.com/user-attachments/assets/f14e7f3a-2b96-4678-ad0f-03376cb36a9c" />


## Soal no 19 ##
Manwe mengirimkan email berisi surat cinta kepada Varda melalui koneksi yang tidak terenkripsi. Melihat hal itu Melkor sipaling jahat langsung melancarkan aksinya yaitu meneror Varda dengan email yang disamarkan. Analisis file capture jaringan dan gagalkan lagi rencana busuk Melkor.
[link file](https://drive.google.com/drive/folders/1D6d8EYdIvE8UF_i4Ms0C7Yakd9j0GYBN) nc 10.15.43.32 3406

### Jawaban ###
<img width="643" height="432" alt="Image" src="https://github.com/user-attachments/assets/2c976256-637c-4e54-8cb2-74df706bdf57" />  

A. Disini saya pilih packet yg bawah bawah karena biasanya informasinya itu lebih lengkap  
<img width="243" height="24" alt="Image" src="https://github.com/user-attachments/assets/efb6f7a3-7060-4e0f-b7f3-59d2ce95194d" />

B. Di packet yang sama sudah terdapat informasi yang tertulis  
<img width="350" height="33" alt="Image" src="https://github.com/user-attachments/assets/2ad9cabc-ab92-4ca2-8656-4cef971ca2a3" />a

C. Di packet yang sama sudah terdapat informasi yang tertulis   
<img width="432" height="45" alt="Image" src="https://github.com/user-attachments/assets/9a512e33-ecdf-4f82-981b-a09036890f01" />

## Soal no 20 ##
Untuk yang terakhir kalinya, rencana besar Melkor yaitu menanamkan sebuah file berbahaya kemudian menyembunyikannya agar tidak terlihat oleh Eru. Tetapi Manwe yang sudah merasakan adanya niat jahat dari Melkor, ia menyisipkan bantuan untuk mengungkapkan rencana Melkor. Analisis file capture dan identifikasi kegunaan bantuan yang diberikan oleh Manwe untuk menggagalkan rencana jahat Melkor selamanya.
[link file](https://drive.google.com/drive/folders/1wOe76_DgH087tAaHH_jxsHCinwFv9pmT) nc 10.15.43.32 3407

### Jawaban ###
<img width="1365" height="465" alt="Image" src="https://github.com/user-attachments/assets/7d99bf2e-1806-4fd2-837a-14f129157c5d" />
A. Jawabannya TLS karena di Wireshark terlihat protokol yang digunakan adalah TLSv1.2. TLS sendiri berfungsi mengenkripsi komunikasi (misalnya HTTP → HTTPS), sehingga data tidak terkirim dalam bentuk plain text. Jadi, encryption method yang dipakai dalam capture ini adalah TLS.
<img width="1365" height="190" alt="Image" src="https://github.com/user-attachments/assets/72c671f7-cc33-40d1-9fc0-d2adf2cf0b63" />

B. Nahh disini kita memerlukan file [keyslogfile.txt](https://drive.google.com/drive/folders/1wOe76_DgH087tAaHH_jxsHCinwFv9pmT), untuk membuka file tersembunyi yaitu dengan cara : 
- Edit -> Preferences -> Protocol -> TLS -> Masukkan *keyslogfile.txt* -> Apply
nahh baru disini keluar semua isi file tersembunyi di
- File ->  Export Objects -> HTTP
<img width="1364" height="305" alt="Image" src="https://github.com/user-attachments/assets/c2c5a537-192a-4ef5-87a0-4f417276c915" />

C. 
<img width="659" height="35" alt="Image" src="https://github.com/user-attachments/assets/790b12e0-ef59-4c96-96cb-f9ce49ec5de4" />










