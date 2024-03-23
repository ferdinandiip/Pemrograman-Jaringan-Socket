# Laporan-Praktikum-Pemrograman-Jaringan-Socket

Nama   : Ferdinand Dwi

NIM    : 1203220138

# Soal Nomor 1
1. Membuat sebuah program server yang dapat menerima koneksi dari klien menggunakan protokol TCP. Server ini akan menerima pesan dari klien dan mengirimkan pesan balasan berisi jumlah karakter pada pesan tersebut. Gunakan port 12345 untuk server. Membuat analisa dari hasil program tersebut

Screenshoot :

![image](https://github.com/ferdinandiip/Pemrograman-Jaringan-Socket/assets/162901297/59fec10f-6768-4cff-976c-56aeb737ff89)
![image](https://github.com/ferdinandiip/Pemrograman-Jaringan-Socket/assets/162901297/4f94062a-8a8f-4bdd-87f7-76d3fe6f1e9e)


**Analisa Program**

• Server dibuat menggunakan modul Socket Python. Server ini dikonfigurasi untuk mendengarkan koneksi masuk dari klien pada alamat IP "localhost" dan port 12345.Ketika server menerima koneksi dari klien, server membaca data yang dikirim oleh klien. Data ini diasumsikan berupa angka yang dikirim dalam format string, yang kemudian didekodekan dan diubah menjadi integer. Server kemudian memeriksa apakah angkanya genap atau ganjil dan meresponsnya. Respons ini dikodekan menjadi string dan dikirim kembali ke klien. Soket klien dan server kemudian ditutup. Server berhasil menerima pesan "perdi tampan" dari klien dan mengirimkan balasan yang berisi pesan tersebut dan jumlah karakternya. Ini menunjukkan bahwa komunikasi antara klien dan server berjalan dengan baik.

# Soal Nomor 2
2.	Membuat sebuah program klien yang dapat terhubung ke server yang telah dibuat pada soal nomor 2. Klien ini akan mengirimkan pesan ke server berupa inputan dari pengguna dan menampilkan pesan balasan jumlah karakter yang diterima dari server. Membuat analisa dari hasil program tersebut

Screenshot:

![image](https://github.com/ferdinandiip/Pemrograman-Jaringan-Socket/assets/162901297/23191289-3bce-448e-8899-13b3be03489a)
![image](https://github.com/ferdinandiip/Pemrograman-Jaringan-Socket/assets/162901297/95e94d37-aa09-4124-a16b-37fe87c35d67)

**Analisa Program**

•	Ketika klien terhubung ke server, ia akan mengirimkan pesan ke server. Pesan ini dimasukkan oleh pengguna dalam format string. Klien kemudian menunggu dan menerima respon dari server. Respons ini menunjukkan jumlah karakter dalam pesan. Ketika klien menerima respon dari server, ia akan menampilkan respon tersebut dan menutup koneksi. Klien berhasil mengirimkan pesan "perdi tampan" ke server dan menerima balasan bahwa pesan tersebut memiliki 12 karakter. Ini menunjukkan bahwa komunikasi antara client dan server berjalan dengan baik.



