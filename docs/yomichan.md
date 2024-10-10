# Tutorial Pengaturan Yomitan

**Baru: Yomichan tidak lagi dalam pengembangan. Penggantinya adalah Yomitan.**

## Apa itu Yomitan?
Yomitan adalah ekstensi browser yang memungkinkan Anda mencari kata-kata bahasa Jepang dengan mudah, menampilkan baik arti maupun cara bacanya di halaman web.

## Memulai
Yomitan tersedia untuk browser berbasis Chromium dan Firefox. Anda dapat menemukan versi masing-masing di bawah ini.
[Chrome Web Store](https://chromewebstore.google.com/detail/yomitan/likgccmbimhjbgkjambclfkhldnlhbnn)
[Firefox](https://addons.mozilla.org/en-GB/firefox/addon/yomitan/)
Setelah diinstal, akan terbuka halaman tab baru, tutup saja untuk saat ini agar kita tidak saling membingungkan.

## Mendapatkan Kamus
Ketika Anda pertama kali menginstal Yomitan, Anda perlu memuat kamus ke dalamnya agar dapat menggunakannya.
File-file ini menggunakan ekstensi `.zip` dan **tidak boleh diekstrak oleh pengguna.**

Anda dapat menemukan koleksi kamus Yomitan saya di bawah ini. Ini akan memiliki semua yang Anda butuhkan dan (mungkin) tidak butuhkan. :slight_smile:
→→→→[Koleksi Kamus Yomitan Shoui](https://learnjapanese.link/dictionaries)←←←←　　

Kamus dapat ditemukan di folder masing-masing.
Saya merekomendasikan Anda menginstal kamus-kamus berikut:
	- `Bilingual/[Bilingual] Jitendex (Recommended).zip`
	- `Bilingual/[Bilingual] 新和英.zip`
	- `Kanji/[Kanji] KANJIDIC (English).zip`
	- `Grammar/Dictionary of Japanese Grammar.zip`
	- `Pitch Accent/アクセント辞典v2 (Recommended).zip`

## Menginstal kamus dan penggunaan dasar

1. Klik ikon ![yomitan-icon](img/yomitan-icon.png) di toolbar browser.
2. Klik ikon ![cog](img/yomitan-cog.png) untuk mengakses halaman pengaturan.
3. Di sidebar kiri, klik "Dictionaries" dan kemudian klik "Configure installed and enabled dictionaries…"
4. Klik tombol "Import" di bagian bawah.
5. Di sini Anda memilih kamus yang akan diimpor. Harap impor hanya yang berikut:
	- `Bilingual/[Bilingual] Jitendex (Recommended).zip`
	- `Bilingual/[Bilingual] 新和英.zip`
	- `Kanji/[Kanji] KANJIDIC (English).zip`
	- `Grammar/Dictionary of Japanese Grammar.zip`
	- `Pitch Accent/アクセント辞典v2 (Recommended).zip`

6. Harap tunggu sampai kamus selesai diimpor. Ini mungkin memakan waktu.
7. Setelah selesai, Anda dapat menguji Yomitan dengan menahan tombol ++shift++ dan mengarahkan kursor ke teks bahasa Jepang. Berikut contohnya: 日本語. Ini akan menampilkan kotak pop-up yang menampilkan definisi yang dipisahkan berdasarkan kamus.

![Demo Yomichan](img/yomidemo1.png)

Klik di mana saja di luar kotak atau tekan tombol ++esc++ untuk menutup.
Klik pada kanji individual di kata utama untuk melihat informasi kanji (hanya berfungsi dengan KANJIDIC terinstal).

Anda dapat mengklik tombol ![audio](img/yomichan-audio.png) untuk mendengar kata tersebut diucapkan oleh penutur asli.

Di toolbar ekstensi browser Anda, jika Anda mengklik logo Yomitan, kemudian pada ikon ![search icon](img/yomitan-search.png) atau dengan menggunakan pintasan keyboard ++alt+insert++, Anda dapat mengakses Pencarian Yomitan, di mana Anda dapat menggunakan Yomitan sebagai kamus mandiri Jepang ke Inggris.

Ukuran kotak pop-up dapat diedit dengan pengaturan lanjutan yang diaktifkan.
Mode gelap penuh juga dapat diaktifkan di pengaturan.

**Jitendex** adalah kamus Jepang-Inggris gratis dan berlisensi terbuka. Jitendex dibangun berdasarkan data yang disediakan oleh beberapa proyek gratis dan terbuka. Yang paling menonjol adalah proyek JMdict, yang digunakan pada banyak proyek kamus Jepang seperti Jisho.org, Akebi, Shirabe Jisho, Takoboto, dll.

**新和英** (Shinwaei) adalah kamus Jepang-Inggris yang ditujukan untuk orang Jepang. Ini memiliki banyak contoh kalimat yang dapat sangat berguna bagi pelajar bahasa Jepang. Variasi dari ini dengan lebih banyak contoh kalimat disebut `[Bilingual] 研究社　新和英大辞典　第５版.zip` juga dapat ditemukan dalam koleksi kamus saya.

**KANJIDIC** adalah kamus kanji, yang memungkinkan Anda melihat informasi kanji individual.

**Dictionary of Japanese Grammar**, atau 日本語文法辞典(全集), adalah kamus yang membantu Anda mencari tata bahasa (tentu saja!).

**アクセント辞典v2** memungkinkan Anda melihat informasi aksen nada kata-kata.

## Kamus frekuensi yang direkomendasikan

Yomitan mendukung penggunaan kamus frekuensi yang memberi tahu Anda seberapa umum sebuah kata.

**JPDB** - Daftar frekuensi yang dibuat dari jpdb.io, yang merupakan situs yang telah menganalisis banyak light novel, visual novel, anime, dan drama Jepang. Dengan demikian, ini adalah daftar frekuensi dari media fiksi Jepang.

**CC100** - Daftar frekuensi data korpus dari internet Jepang. Kata-kata formal akan muncul lebih umum dalam daftar frekuensi ini. Contoh: 審議会 (dewan) memiliki frekuensi 9733 di CC100 dan 58730 di JPDB.

**Apa itu kata yang umum?**

Sangat umum: 1-10.000
Umum: 10.001-20.000
Cukup umum: 20.001-30.000
Agak tidak umum: 30.001-40.000
Tidak umum: 40.001-50.000
Jarang: 50.001-80.000
Tingkat-penutur-asli-mungkin-tidak-tahu: 80.000+

## Mengizinkan akses ke URL file

Mengaktifkan ini memungkinkan Anda menggunakan Yomitan pada file lokal seperti file .HTML.

!!! failure "File PDF"
    Pada Chrome, Anda perlu menggunakan [PDF.js](https://mozilla.github.io/pdf.js/web/viewer.html). Klik pada tanda panah diagonal ke atas untuk memuat pdf.

Chromium:
	- Klik kanan pada ikon ![yomi icon](img/yomichan-icon.png)
	- Klik "Kelola Ekstensi"
	- Aktifkan "Izinkan akses ke URL file"

Firefox:
	- Diaktifkan secara default.

## Bonus: Menambahkan sumber audio tambahan Forvo

Anda mungkin menemui audio yang hilang dengan sumber audio Yomitan default, menambahkan [Forvo](https://ja.forvo.com/) akan membantu mengisi celah tersebut.

Terima kasih kepada [jamesnicholas](https://github.com/jamesnicolas/yomichan-forvo-server) untuk add-on yang luar biasa ini!

Ini memerlukan Anda memiliki Anki (2.1 dan lebih baru) terinstal dan terbuka di komputer Anda agar berfungsi.

1. Salin kode ini `580654285`
2. Di Anki, di menu bagian atas, klik **Tools**, lalu **Add-ons**.
3. Di jendela baru, klik **Get Add-ons...** dan tempel kode `580654285` ke dalam kotak teks dan klik **OK**
4. Restart Anki dengan menutupnya dan membukanya kembali.
5. Di halaman pengaturan Yomitan ![cog](img/yomitan-cog.png), klik **Audio** di sebelah kiri, dan kemudian klik **Configure audio playback sources...**
6. Klik **Add** dan kemudian pilih **Custom** dari menu drop-down.
7. Sekarang di mana tertulis **Custom audio source (?)**, pilih tipe **JSON** dari menu drop-down.
8. Di kotak teks URL, masukkan ini `http://localhost:8770/?expression={expression}&reading={reading}`

## Bonus: Penggunaan Android dengan Kiwi Browser

Kiwi Browser adalah browser Chromium yang mendukung ekstensi, termasuk Yomichan. Anda dapat mengunduhnya di bawah ini.
[Google Play](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser)

Anda dapat mengakses halaman pengaturan Yomichan dengan pergi ke :material-dots-vertical: > Yomichan	![yomi icon](img/yomichan-icon.png) > Settings.

Silakan lihat di atas untuk tautan untuk mengunduh ekstensi, tautan ke koleksi kamus, dan kamus awal yang direkomendasikan.
Mengimpor kamus adalah proses yang sangat intensif prosesor dan akan memakan waktu lama tergantung pada ponsel Anda. Harap bersabar.

Ketuk pada kata untuk mencarinya. Jika tidak berfungsi, Anda mungkin perlu mematikan tombol modifier.

![Yomichan Android](img/yomichan_android_alt.png)

## Pengaturan Anki

Lihat [situs web kuri](https://donkuri.github.io/learn-japanese/setup/#anki-setup).

## Server audio offline (+ Lebih banyak audio daripada default)

[Ikuti panduan ini untuk mendapatkan audio lokal.](https://github.com/themoeway/local-audio-yomichan)

<h3>Merasa ini bermanfaat? Pertimbangkan untuk mendukung saya di Patreon!</h3>

[:fontawesome-brands-patreon: Dukung saya di Patreon](https://www.patreon.com/shoui){: .md-button }
