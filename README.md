# Praktikum 1: Membangun Layout di Flutter
![Tangkapan Layar Aplikasi](assets/image/1.1.png)



# Praktikum 2: Implementasi button row
![Tangkapan Layar Aplikasi](assets/image/2.1.png)



# Praktikum 3: Implementasi text section
![Tangkapan Layar Aplikasi](assets/image/3.1.png)



# Praktikum 4: Implementasi image section
![Tangkapan Layar Aplikasi](assets/image/4.1.png)




# Tugas Praktikum 1

1. Selesaikan Praktikum 1 sampai 4, lalu dokumentasikan dan push ke repository Anda berupa screenshot setiap hasil pekerjaan beserta penjelasannya di file README.md!

**Jawab:** link source code praktikum 1-4: https://github.com/doggest25/layout_flutter

2. Silakan implementasikan di project baru "basic_layout_flutter" dengan mengakses sumber ini: https://docs.flutter.dev/codelabs/layout-basics

**Jawab:**

![Tangkapan Layar Aplikasi](assets/image/tugas1.1.png)

![Tangkapan Layar Aplikasi](assets/image/tugas1.2.png)

![Tangkapan Layar Aplikasi](assets/image/tugas1.3.png)

![Tangkapan Layar Aplikasi](assets/image/tugas1.4.png)

![Tangkapan Layar Aplikasi](assets/image/tugas1.5.png)

link implementasi: https://github.com/doggest25/basic_layout_flutter

3. Kumpulkan link commit repository GitHub Anda kepada dosen yang telah disepakati!

**Jawab:** done


# Praktikum 5: Membangun Navigasi di Flutter

Langkah 1: 

Siapkan project baru
Sebelum melanjutkan praktikum, buatlah sebuah project baru Flutter dengan nama belanja dan susunan folder seperti pada gambar berikut. Penyusunan ini dimaksudkan untuk mengorganisasi kode dan widget yang lebih mudah.

Langkah 2: 

Mendefinisikan Route
Buatlah dua buah file dart dengan nama home_page.dart dan item_page.dart pada folder pages. Untuk masing-masing file, deklarasikan class HomePage pada file home_page.dart dan ItemPage pada item_page.dart. Turunkan class dari StatelessWidget. Gambaran potongan kode dapat anda lihat sebagai berikut.

Langkah 3: 

Lengkapi Kode di main.dart
Setelah kedua halaman telah dibuat dan didefinisikan, bukalah file main.dart. Pada langkah ini anda akan mendefinisikan Route untuk kedua halaman tersebut. Definisi penamaan route harus bersifat unique. Halaman HomePage didefinisikan sebagai /. Dan halaman ItemPage didefinisikan sebagai /item. Untuk mendefinisikan halaman awal, anda dapat menggunakan named argument initialRoute. Gambaran tahapan ini, dapat anda lihat pada potongan kode berikut.

Langkah 4: 

Membuat data model
Sebelum melakukan perpindahan halaman dari HomePage ke ItemPage, dibutuhkan proses pemodelan data. Pada desain mockup, dibutuhkan dua informasi yaitu nama dan harga. Untuk menangani hal ini, buatlah sebuah file dengan nama item.dart dan letakkan pada folder models. Pada file ini didefinisikan pemodelan data yang dibutuhkan. Ilustrasi kode yang dibutuhkan, dapat anda lihat pada potongan kode berikut.

Langkah 5: 

Lengkapi kode di class HomePage
Pada halaman HomePage terdapat ListView widget. Sumber data ListView diambil dari model List dari object Item. Gambaran kode yang dibutuhkan untuk melakukan definisi model dapat anda lihat sebagai berikut.

Langkah 6: 

Membuat ListView dan itemBuilder
Untuk menampilkan ListView pada praktikum ini digunakan itemBuilder. Data diambil dari definisi model yang telah dibuat sebelumnya. Untuk menunjukkan batas data satu dan berikutnya digunakan widget Card. Kode yang telah umum pada bagian ini tidak ditampilkan. Gambaran kode yang dibutuhkan dapat anda lihat sebagai berikut.

Jalankan aplikasi pada emulator atau pada device anda.

![Tangkapan Layar Aplikasi](assets/image/5.1.png)

Langkah 7: 

Menambahkan aksi pada ListView
Item pada ListView saat ini ketika ditekan masih belum memberikan aksi tertentu. Untuk menambahkan aksi pada ListView dapat digunakan widget InkWell atau GestureDetector. Perbedaan utamanya InkWell merupakan material widget yang memberikan efek ketika ditekan. Sedangkan GestureDetector bersifat umum dan bisa juga digunakan untuk gesture lain selain sentuhan. Pada praktikum ini akan digunakan widget InkWell.

Untuk menambahkan sentuhan, letakkan cursor pada widget pembuka Card. Kemudian gunakan shortcut quick fix dari VSCode (Ctrl + . pada Windows atau Cmd + . pada MacOS). Sorot menu wrap with widget... Ubah nilai widget menjadi InkWell serta tambahkan named argument onTap yang berisi fungsi untuk berpindah ke halaman ItemPage. Ilustrasi potongan kode dapat anda lihat pada potongan berikut.

![Tangkapan Layar Aplikasi](assets/image/5.2.png)

![Tangkapan Layar Aplikasi](assets/image/5.3.png)


# Tugas Praktikum 2
1. Untuk melakukan pengiriman data ke halaman berikutnya, 
cukup menambahkan informasi arguments pada penggunaan Navigator. 
Perbarui kode pada bagian Navigator menjadi seperti berikut.

**Jawab:**

![Tangkapan Layar Aplikasi](assets/image/tugas2.1.png)

2. Pembacaan nilai yang dikirimkan pada halaman sebelumnya dapat dilakukan menggunakan ModalRoute. 
Tambahkan kode berikut pada blok fungsi build dalam halaman ItemPage. 
Setelah nilai didapatkan, anda dapat menggunakannya seperti penggunaan variabel pada umumnya. 
(https://docs.flutter.dev/cookbook/navigation/navigate-with-arguments)

**Jawab:**

![Tangkapan Layar Aplikasi](assets/image/tugas2.2.png)

3. Pada hasil akhir dari aplikasi belanja yang telah anda selesaikan, tambahkan atribut foto produk, stok, dan rating. 
Ubahlah tampilan menjadi GridView seperti di aplikasi marketplace pada umumnya

**Jawab:**

![Tangkapan Layar Aplikasi](assets/image/tugas2.3.1.png)

![Tangkapan Layar Aplikasi](assets/image/tugas2.3.2.png)



4. Silakan implementasikan Hero widget pada aplikasi belanja Anda dengan mempelajari dari 
sumber ini: https://docs.flutter.dev/cookbook/navigation/hero-animations

**Jawab:**

![Tangkapan Layar Aplikasi](assets/image/tugas2.4.1.gif)

5. Sesuaikan dan modifikasi tampilan sehingga menjadi aplikasi yang menarik. Selain itu, pecah widget menjadi kode yang lebih kecil. Tambahkan Nama dan NIM di footer aplikasi belanja Anda.

**Jawab:**

![Tangkapan Layar Aplikasi](assets/image/tugas2.5.1.gif)


6. Selesaikan Praktikum 5: Navigasi dan Rute tersebut. Cobalah modifikasi menggunakan plugin go_router, lalu dokumentasikan dan push ke repository Anda berupa screenshot setiap hasil pekerjaan beserta penjelasannya di file README.md. Kumpulkan link commit repository GitHub Anda kepada dosen yang telah disepakati!

**Jawab:** 

![Tangkapan Layar Aplikasi](assets/image/tugas2.6.1.png)


Link github belanja: https://github.com/doggest25/belanja