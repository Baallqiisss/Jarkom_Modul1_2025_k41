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
![16](images/16.png)      

A. Cari Packet FTP karena biasanya sebagai tempat login, sehingga bisa memuat username dan password client  
![16A](images/16A.png)    

B. Salah satu ciri - ciri file malware adalah .exe dan terdapat 5 file dengan akhiran .exe ( q.exe, w.exe, e.exe, r.exe, t.exe )  
![16B](images/16B.png)     

C. Untuk mengintegritaskan file FTP-DATA ( q.exe, w.exe, e.exe, r.exe, t.exe) dengan **sha256sum** maka kita harus mengsave file packet dengan row agar dapat menyimpan payload benar - benar apa adanya (bit by bit)  
bash : sha256sum <namafile>

![16C](images/16C.png)    

D. ![16D](images/16D.png)    

E. ![16E](images/16E.png)  

F.![16F](images/16F.png)   

G. ![16G](images/16G.png)  

## Soal no 17 ##
Manwe membuat halaman web di node-nya yang menampilkan gambar cincin agung. Melkor yang melihat web tersebut merasa iri sehingga ia meletakkan file berbahaya agar web tersebut dapat dianggap menyebarkan malware oleh Eru. Analisis file capture untuk menggagalkan rencana Melkor dan menyelamatkan web Manwe.
[link file](https://drive.google.com/drive/folders/10UNx8BhvbyCDhHGHS7D7zmyvFbCf41ze) nc 10.15.43.32 3404

### Jawaban ###
![17](images/17.png)  

A. Untuk menemukan suspicius file yaitu pergi ke file -> Export Object -> HTTP
   ![17A](images/17A.png)    
B.
![17B](images/17B.png)    

C. Sama seperti diatas, kita harus mensave file knr.exe dulu
![17C](images/17C.png)  

## Soal no 18 ##   
Karena rencana Melkor yang terus gagal, ia akhirnya berhenti sejenak untuk berpikir. Pada saat berpikir ia akhirnya memutuskan untuk membuat rencana jahat lainnya dengan meletakkan file berbahaya lagi tetapi dengan metode yang berbeda. Gagalkan lagi rencana Melkor dengan mengidentifikasi file capture yang disediakan agar dunia tetap aman.
[link file](https://drive.google.com/drive/folders/1R4-D1WnsDVrT73UlkacjY0Ntag42AFUy) nc 10.15.43.32 3405

### Jawaban ### 
![18](images/18.png)     

A. Untuk melihat file berisi malware yaitu pergi ke file -> Export Object -> SMB, nahh ciri - ciri file malware biasanya ada .exe nahh disini ada 2 file     
![18A](images/18A.png)    

B. File ke 2 

![18B](images/18B.png)  

C.   
![18C](images/18C.png)   

D. 
![18D](images/18D.png)   


## Soal no 19 ##
Manwe mengirimkan email berisi surat cinta kepada Varda melalui koneksi yang tidak terenkripsi. Melihat hal itu Melkor sipaling jahat langsung melancarkan aksinya yaitu meneror Varda dengan email yang disamarkan. Analisis file capture jaringan dan gagalkan lagi rencana busuk Melkor.
[link file](https://drive.google.com/drive/folders/1D6d8EYdIvE8UF_i4Ms0C7Yakd9j0GYBN) nc 10.15.43.32 3406

### Jawaban ###
![19](images/19.png)    

A. Disini saya pilih packet yg bawah bawah karena biasanya informasinya itu lebih lengkap  
![19A](images/19A.png)  

B. Di packet yang sama sudah terdapat informasi yang tertulis  
![19B](images/19B.png)  

C. Di packet yang sama sudah terdapat informasi yang tertulis   
![19C](images/19C.png)  

## Soal no 20 ##
Untuk yang terakhir kalinya, rencana besar Melkor yaitu menanamkan sebuah file berbahaya kemudian menyembunyikannya agar tidak terlihat oleh Eru. Tetapi Manwe yang sudah merasakan adanya niat jahat dari Melkor, ia menyisipkan bantuan untuk mengungkapkan rencana Melkor. Analisis file capture dan identifikasi kegunaan bantuan yang diberikan oleh Manwe untuk menggagalkan rencana jahat Melkor selamanya.
[link file](https://drive.google.com/drive/folders/1wOe76_DgH087tAaHH_jxsHCinwFv9pmT) nc 10.15.43.32 3407

### Jawaban ###
![20](images/20.png)  

A. Jawabannya TLS karena di Wireshark terlihat protokol yang digunakan adalah TLSv1.2. TLS sendiri berfungsi mengenkripsi komunikasi (misalnya HTTP → HTTPS), sehingga data tidak terkirim dalam bentuk plain text. Jadi, encryption method yang dipakai dalam capture ini adalah TLS.
![20A](images/20A.png)  

B. Nahh disini kita memerlukan file [keyslogfile.txt](https://drive.google.com/drive/folders/1wOe76_DgH087tAaHH_jxsHCinwFv9pmT), untuk membuka file tersembunyi yaitu dengan cara : 
- Edit -> Preferences -> Protocol -> TLS -> Masukkan *keyslogfile.txt* -> Apply
nahh baru disini keluar semua isi file tersembunyi di
- File ->  Export Objects -> HTTP  
![20B](images/20B.png)  

C. 
![20C](images/20C.png)  










