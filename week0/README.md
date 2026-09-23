Nama: Aura Yoshua Eka Putra Sarwanta  
NIM: 260530911132  

Penggunaan Tools yang digunakan **UBUNTU**  
**KATEGORI CTF PILIHAN - FORENSICS**  
# PENGUJIAN WSL  

<img width="1011" height="542" alt="pengujian wsl" src="https://github.com/user-attachments/assets/57c45a02-537f-4690-b468-64de85d15d34" />  
Pengujian diatas menggunakan command line dari linux serta pengujian terhadap python.  
  
# PROSES PENYELESAIAN CHALLENGE  
Tahap awal terdapat foto cat.jpg pada CTF Challenge "Information" dan tugas kita memecahkan flag yang ada file tersebut.  
Cara pemecahan flag tersebut kita memerlukan yang namanya **ExifTool** didalam WSL.  

Setelah kalian mempunyai/mengistall ExifTool kalian dapat mengakses Cat.JPG tersebut pada Exiftool  
contoh : ```bash exiftool cat.jpg```  

jika sudah maka sehabis itu akan ada data menampilkan hasil dari isi file jpg tersebut lalu kita bisa menganalisisnya

<img width="1346" height="758" alt="kode cat jpg" src="https://github.com/user-attachments/assets/e4a05574-20c2-429e-8826-ec8d0c77117c" />  

Diatas adalah kode yang ditampilkan biasanya flag akan muncul dalam barisan komentar tetapi study case diatas tidak menunjukan flag terlihat secara langsung yang berarti ada satu kode yang terenkripsi sehingga secara bahasa gampangnya kita harus mengekstrak kode tersebut agar mendapat flagnya  

Dalam contoh diatas mari kita ambil bagian dari license yang terlihat mempunyai numerik unik  
berikut cara penyelesaiannya :  

<img width="1008" height="597" alt="penyelesaian kode cat jpg" src="https://github.com/user-attachments/assets/1afee596-2c4c-430c-a058-48057d20a9f1" />

Lalu diakhir kita akan mendapatkan flag yang kita cari sehingga dapat menyelesaikan tugas tersebut.  

Selama Pengujian dan penugasan untuk saya masih mencari saran dan refrensi dari berbagai sumber seperti google dan juga ai untuk bantuan selama pengerjaan.
