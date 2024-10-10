# Panduan Visual Novel

### Apa itu Visual Novel?

Visual Novel (sering disingkat sebagai **VN**) dapat digambarkan sebagai semacam perpaduan antara novel dan permainan, yang menampilkan cerita berbasis teks dengan sedikit interaksi dari pemain. Kebanyakan VN memiliki visual bergaya anime, dan biasanya disertai dengan pengisi suara, musik latar, dan efek suara. Sepanjang permainan, pemain mungkin diberi pilihan yang akan mempengaruhi bagaimana cerita akan berkembang, jadi jika Anda memainkannya untuk kedua kalinya dengan pilihan yang berbeda, Anda mungkin akan mendapatkan alur cerita yang sama sekali berbeda.

![Gambar](img/vn1.jpg)

### Mengapa Visual Novel?
Membaca bahasa Jepang sangat penting, tetapi tidak semua orang suka membaca buku. Anda mungkin merasa lelah setelah beberapa saat membaca novel standar yang hanya berisi teks, tetapi anehnya Anda mungkin bisa membaca VN selama berjam-jam tanpa merasa lelah. VN memiliki campuran prosa sastra dan bahasa Jepang percakapan, sehingga sangat cocok untuk latihan membaca yang mendalam.
Bagi orang-orang yang mungkin tidak suka membaca, dan bahkan merasa manga membosankan, VN mungkin cocok untuk Anda.
![Gambar](img/vn2.jpg)

### Bermain visual novel untuk belajar bahasa Jepang

Panduan ini akan membahas cara bermain visual novel dalam bahasa Jepang dan belajar bahasa Jepang darinya. Panduan ini mengasumsikan Anda sudah memiliki visual novel Jepang yang terpasang dan berfungsi. Jika belum, lihat [Pengaturan VN Lintas Platform](/vn-setup).

Persyaratan:

[Textractor](https://github.com/Artikash/Textractor/releases)  
[Yomichan](https://foosoft.net/projects/yomichan/)  
[Clipboard Inserter](https://github.com/kmltml/clipboard-inserter) ([Versi Firefox di Sini](https://addons.mozilla.org/en-US/firefox/addon/lap-clipboard-inserter/))  
[Halaman Texthooking](https://learnjapanese.moe/texthooker.html)  

Tutorial pengaturan Yomichan yang detail dapat ditemukan [di sini](/yomichan)

Untuk sebagian besar aplikasi, gunakan executable x86 dari Textractor.

!!! info "Steins;Gate"
	Jika Anda ingin menghook Steins;Gate dan Steins;Gate 0, silakan lihat [Steins;Gate Textractor](https://github.com/shiiion/steinsgate_textractor)  

Jalankan VN Anda dan Textractor, lalu pertama-tama hapus semua ekstensi yang tidak diperlukan dengan menekan tombol ++delete++. 

Hapus yang berikut:

- Bing Translate
- Terjemahan lainnya
- Extra Window
- Extra Newlines
- Styler 

![Gambar](img/textractor1.png)  

!!! warning "Urutan ekstensi" 
	Urutan ekstensi Anda penting. Berikut adalah yang biasanya saya rekomendasikan:  
	- Remove Repeated Characters  
	- Remove Repeated Phrases  
	- Regex Filter (opsional, tapi harus di atas clipboard)  
	- Copy to Clipboard  

Sekarang kita perlu *menghubungkan* Textractor ke VN Anda. 

![Gambar](img/textractor2.png)  

Ketika terhubung, majukan teks di VN kemudian beralih melalui hook untuk menemukan hook yang cocok dengan teks yang ditampilkan di VN.  

![Gambar](img/textractor3.png)  

Sekarang buka browser Anda, buka [halaman texthooking](https://learnjapanese.moe/texthooker.html) saya, pastikan **Clipboard Inserter** terpasang dan diaktifkan, lalu majukan teks di VN lagi.  

![Gambar](img/textractor4.png)  

Anda kemudian bisa menekan ++shift++ untuk menggunakan Yomichan.  

![Gambar](img/textractor5.png)  

Selesai! Nikmati membacanya!! :smirk_cat:

Anda dapat melacak berapa banyak karakter yang telah Anda baca menggunakan indikator di pojok kanan atas halaman texthooking.
Anda dapat memilih untuk menyimpan teks ketika Anda merefresh halaman, atau hanya jumlah karakter, atau tidak sama sekali.  
Halaman texthooking memiliki "penghitungan karakter yang akurat", artinya tidak menghitung karakter khusus dan tanda baca seperti 。「」 dalam hitungan.   

!!! info "Tidak bisa hook?"
	Coba lihat [Daftar H-Code @ Visual Novel Texthooking Wiki](https://vn-hooking.fandom.com/wiki/H-Code)  
	Pemain Little Busters!, gunakan versi Ecstasy dan lihat [ini](https://cdn.discordapp.com/attachments/813105334763126814/1047252417735036988/little_busters.png)  

### Butuh panduan?
Jika Anda tidak terbiasa dengan visual novel, atau permainan yang membuat Anda membuat pilihan yang menentukan nasib cerita, Anda mungkin ingin menggunakan panduan. Bagaimanapun, Anda tidak ingin mendapatkan ending yang buruk.  
Anda dapat menemukan panduan dengan mencari "[nama vn] 攻略" misalnya "Angel Beats! -1st Beat- 攻略".  

Jika Anda bersikeras untuk tidak menggunakan panduan, adalah keputusan yang bijak untuk membuat file simpanan setiap kali Anda dihadapkan pada pilihan. VN sering memiliki 99+ slot data simpanan, karena mereka mengasumsikan Anda akan mengisinya dengan setiap titik keputusan dalam permainan.  

### Tidak yakin apa yang harus dimainkan?

Lihat daftar visual novel di bawah ini

[Daftar jamal](https://anacreondjt.gitlab.io/vn-chart/)  
[Daftar terkenal ini](https://docs.google.com/document/u/1/d/1KnyyDt7jimEz-dgeMSKymRaT2r3QKBPm9AzqZ6oUWAs/pub)  
[Daftar Dinuz](/dinuzlist)  
[Daftar Chronopolize](https://docs.google.com/spreadsheets/d/18vCgQHhBNBeRJdcTcyUi2Atq-nAapQW--33qrwl5Yfw)  
[Visual novel terbaik yang pernah dibuat (menurut peringkat VNDB)](https://vndb.org/v?f=022gja3gja&s=34w)  

Selamat membaca!

Pertimbangkan untuk bergabung dengan **VN Club** kami di [Discord](https://discord.gg/nhqjydaR8j)!

### Bonus: Menggunakan Textractor untuk Visual Novel PPSSPP
Menghook Visual Novel PPSSPP mengharuskan Anda menggunakan versi x86 (32-bit) dari PPSSPP bersama dengan versi x86 dari Textractor.  
 
1. Jalankan PPSSPP (32-bit)  
2. Jalankan Visual Novel.  
3. Hubungkan Textractor (x86) ke PPSSPP (32-bit)  
4. Majukan teks di VN (tombol O)  
5. Menggunakan fitur "Search for hooks", pilih "search for specific text"  
6. Cari teks spesifik yang ada di VN PPSSPP. Harus **persis sama.**  
7. Akan memakan waktu untuk mencari hook, emulator Anda mungkin mulai lag untuk sementara.  
8. Jika Textractor bertanya, (perhatikan Console) dengan cepat majukan teks (tombol O) pada VN PPSSPP.  
9. Sekarang hook akan ditemukan.  
10. Majukan teks sekali lagi (tombol O)  
11. Beralih melalui hook untuk melihat hook mana yang memiliki teks yang baru dimajukan.   
12. Itu saja! :tada: Anda bisa menyimpan hook untuk membuat proses lebih mudah nanti.  

Bukti texthooking bekerja dengan PPSSPP:  
  
![Gambar](img/vnpsp2.jpg)  
