# SI-Penjualan-Kopken

Anggota Kelompok 6
<br>
Yahya Jailani – 2509116085
<br>
Muhammad Dzikri Andhika – 2509116103
<br>
Diara Gladys Ignacia F. S. – 2509116093
<br>
<br>
<h2> Flowchart Menu Utama </h2>
<img width="694" height="556" alt="image" src="https://github.com/user-attachments/assets/52400b33-c0e9-49f8-849f-c272aef4cba4" />

<h2> Flowchart Menu Admin </h2>
<img width="599" height="677" alt="image" src="https://github.com/user-attachments/assets/23b03baa-3b0d-4fc7-92f2-e385dfa83e4d" />

<h2> Flowchart Menu Kasir </h2>
<img width="736" height="373" alt="image" src="https://github.com/user-attachments/assets/bf05a17f-2787-437d-af35-c15a0b8e95f1" />

<h2> Flowchart Menu Pelanggan </h2>
<img width="744" height="547" alt="image" src="https://github.com/user-attachments/assets/3fdfde24-d524-4125-b271-2f0117e332e9" />

<h2> Menu Utama </h2>
- Source Code Menu Utama
<br>
<br>
<img width="476" height="261" alt="image" src="https://github.com/user-attachments/assets/f1733e79-8a93-4799-8ba1-a01534b7fa97" />
<br>
<br>
- Output Menu Utama
<br>
<br>
<img width="564" height="190" alt="image" src="https://github.com/user-attachments/assets/e2743ff7-784d-4d93-ae03-4366264b0b3b" />
<br>
<br>
Menu utama merupakan titik awal interaksi pengguna. Terdapat tiga pilihan, yaitu Login, Registrasi, dan Keluar.

<h2> Registrasi </h2>
- Source Code Registrasi
<br>
<br> 
<img width="664" height="684" alt="image" src="https://github.com/user-attachments/assets/21b06e6b-68c1-43f2-bbdd-6cf1e3517286" />
<br>
<br>
- Output Registrasi
<br>
<br>
<img width="655" height="308" alt="image" src="https://github.com/user-attachments/assets/4869afdd-eadd-4558-98ba-8fd6ca637add" />
<br>
<br>
Jika pengguna memilih opsi 2. Registrasi, maka sistem akan meminta data baru:
<br>
1.	Username
<br>
2.	Password (4 digit)
<br>
3.	Saldo awal (maksimal Rp200.000)
<br>
Data pengguna yang berhasil diregistrasi otomatis disimpan dalam file user.csv dengan role default sebagai pelanggan.

<h2> Login </h2>
- Source Code Login
<br>
<br> 
<img width="632" height="379" alt="image" src="https://github.com/user-attachments/assets/cb4b95d5-292f-4bc4-b58d-10a6398c58a9" />
<br>
<br>
- Output Login
<br>
<br>
<img width="632" height="547" alt="image" src="https://github.com/user-attachments/assets/5e559155-d4e0-405d-abab-33311272197c" />
<br>
<br>
Menu login memungkinkan pengguna masuk berdasarkan perannya masing-masing. Sistem akan mencocokkan username dan password dengan data di file user.csv.
<br>
Jika data valid, sistem akan menampilkan pesan sukses dan membuka menu sesuai peran (admin, kasir, atau pelanggan).

<h2> Menu Admin </h2>
- Source Code Menu Admin
<br>
<br>
<img width="412" height="415" alt="image" src="https://github.com/user-attachments/assets/522b5aad-76f1-4ec6-a487-8d41b38c8b35" />
<br>
<br>
- Output Menu Admin
<br>
<br>
<img width="419" height="356" alt="image" src="https://github.com/user-attachments/assets/06bc150c-e28a-401a-a539-f91463c3a86b" />
<br>
<br>
Setelah login sebagai admin, pengguna dapat mengakses menu pengelolaan sistem. Admin memiliki kontrol penuh terhadap data produk, pengguna, dan laporan penjualan.

<h2> Lihat Produk </h2>
- Source Code Lihat Produk
<br>
<br>
<img width="644" height="291" alt="image" src="https://github.com/user-attachments/assets/45120942-5649-4de5-a6f9-5fd1c7f9bb80" />
<br>
<br>
- Output Lihat Produk
<br>
<br>
<img width="631" height="313" alt="image" src="https://github.com/user-attachments/assets/f94c273b-70cc-4cff-9f87-811e68330d8d" />
<br>
<br>
Admin dapat menampilkan daftar seluruh produk kopi yang tersimpan di produk.csv. Program menggunakan library PrettyTable untuk menampilkan data dalam format tabel.

<h2> Tambah Produk </h2>
- Source Code Tambah Produk
<br>
<br>
<img width="647" height="395" alt="image" src="https://github.com/user-attachments/assets/8e4e6021-11da-4e49-b1a3-48bf233ab7d2" />
<br>
<br>
- Output Tambah Produk
<br>
<br>
<img width="458" height="156" alt="image" src="https://github.com/user-attachments/assets/a25db08d-1035-48b5-87e4-14407fa71295" />
<br>
<br>
Admin dapat menambah produk baru dengan mengisi kode, nama kopi, dan harga. Data produk baru langsung disimpan ke produk.csv.

<h2> Ubah Produk </h2>
- Source Code Ubah Produk
<br>
<br>
<img width="636" height="397" alt="image" src="https://github.com/user-attachments/assets/11ff33a5-72e4-47d8-8c95-c7f1022a0a7b" />
<br>
<br>
- Output Ubah Produk
<br>
<br>
<img width="633" height="424" alt="image" src="https://github.com/user-attachments/assets/4cb98385-87f7-4e47-8b84-368e0c084d55" />
<br>
<br>
Admin juga dapat memperbarui data produk dengan memasukkan kode produk lama, lalu mengganti nama atau harga sesuai keinginan.

<h2> Hapus User </h2>
- Source Code Hapus User
<br>
<br>
<img width="676" height="368" alt="image" src="https://github.com/user-attachments/assets/5ce53e5c-aa10-4461-a454-cc4b9e2beb07" />
<br>
<br>
- Output Hapus User 
<br>
<br>
<img width="625" height="356" alt="image" src="https://github.com/user-attachments/assets/78b67a85-5f47-40c3-9078-a2a0ab7d5c74" />
<br>
<br>
Admin dapat menghapus akun pengguna kecuali admin utama (id = 1). Sebelum penghapusan, sistem menampilkan seluruh daftar user.

<h2> Lihar Laporan Penjualan </h2>
- Source Code Laporan Penjualan
<br>
<br>
<img width="712" height="268" alt="image" src="https://github.com/user-attachments/assets/025f8311-5d6b-45b9-864e-d868bf274f84" />
<br>
<br>
- Output Laporan Penjualan 
<br>
<br>
<img width="702" height="164" alt="image" src="https://github.com/user-attachments/assets/2b2c1c2e-beb0-49a7-b785-7e0c48541205" />
<br>
<br>
Admin dapat melihat seluruh transaksi penjualan yang dilakukan oleh pelanggan atau kasir. Sistem menampilkan tanggal transaksi, kode produk, jumlah pembelian, dan total harga.

<h2> Menu Kasir </h2>
- Source Code Menu Kasir
<br>
<br>
<img width="402" height="395" alt="image" src="https://github.com/user-attachments/assets/1e8713f7-354c-4509-ab44-7081c05e1821" />
<br>
<br>
- Output Menu Kasir
<br>
<br>
<img width="381" height="254" alt="image" src="https://github.com/user-attachments/assets/2a38502a-f0a9-473f-a033-d0f80551d45d" />
<br>
<br>
Kasir memiliki akses untuk melihat menu kopi, melakukan transaksi, dan menampilkan laporan penjualan.

<h2> Lihat Menu Kopi </h2>
- Menampilkan daftar produk dari produk.csv (sama seperti admin).

<h2> Beli Kopi </h2>
- Souce Code Beli Kopi Bagian 1
<br>
<br> 
<img width="584" height="578" alt="image" src="https://github.com/user-attachments/assets/4232bfb5-257f-4e99-84f6-1478e67df1ff" />
<br>
<br>
- Source Code Beli Kopi Bagian 2
<br>
<br>
<img width="466" height="622" alt="image" src="https://github.com/user-attachments/assets/f88004ff-c552-4f71-96bf-9ececd46759e" />
<br>
<br>
- Output Beli Kopi
<br>
<br>
<img width="450" height="649" alt="image" src="https://github.com/user-attachments/assets/46c2528f-ebc6-4512-8eeb-c41bb50ef023" />
<br>
<br>
Kasir dapat melakukan transaksi atas nama pelanggan. Sistem menghitung total harga otomatis.

<h2> Laporan Penjualan </h2>
- Kasir juga dapat melihat seluruh transaksi penjualan yang dilakukan oleh pelanggan atau kasir. Sistem menampilkan tanggal transaksi, kode produk, jumlah pembelian, dan total harga (sama seperti admin).

<h2> Menu Pelanggan </h2>
- Source Code Menu Pelanggan 
<br>
<br>
<img width="549" height="344" alt="image" src="https://github.com/user-attachments/assets/1da14ab6-015d-44fd-a34a-f43760b01b23" />
<br>
<br>
- Output Menu Pelanggan 
<br>
<br>
<img width="374" height="261" alt="image" src="https://github.com/user-attachments/assets/be8a553a-6e9d-4c46-88ac-8787c35832fb" />
<br>
<br>
- Pelanggan memiliki dua fungsi utama: melihat daftar kopi dan melakukan pembelian.

<h2> Lihat Menu Kopi </h2>
- Sistem menampilkan seluruh produk seperti berikut (sama seperti admin dan kasir).

<h2> Beli Kopi </h2>
- Ketika pelanggan membeli kopi, sistem otomatis menghitung total biaya dan mengurangi saldo pelanggan (sama dengan user).

<h2> Lihat Bukti Transaksi </h2>
- Source Code Lihat Bukti Transaksi
<br>
<br>
<img width="714" height="222" alt="image" src="https://github.com/user-attachments/assets/a1263308-8e88-4c95-9e39-be7add2cb206" />
<br>
<br>
- Output Lihat Bukti Transaksi 
<br>
<br>
<img width="706" height="133" alt="image" src="https://github.com/user-attachments/assets/1106dc11-317b-4375-a18d-3d39b1522b04" />
<br>
<br>
Ketika pelanggan membeli kopi, sistem otomatis mencatat transaksi tersebut dan akan ditampilkan di menu ini.

<h2> Proses Keluar Sistem </h2>
- Output Keluar dari Sistem
<br>
<br>
<img width="618" height="286" alt="image" src="https://github.com/user-attachments/assets/6b53bb3b-e0b7-4d33-b08f-1e07813dcdeb" />
<br>
<br>
Jika pengguna memilih opsi “Keluar” dari menu utama atau submenu, sistem akan menampilkan pesan perpisahan dan menghentikan program.

<h2> TERIMAKASIH </h2>
