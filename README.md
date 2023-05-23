# Smtr2-Praktikum-3
# Latihan1 
````
1.	Lakukan penambahan data pada table mahasiswa dengan mengisi kd_ds yang belum ada pada data dosen.
````
![image](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum-3/assets/115562487/ede0ac37-40eb-4aa8-81b4-942476e9fe31)
````
2.	Hapus satu record data pada table dosen yang telah dirujuk pada table mahasiswa.
````
![image](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum-3/assets/115562487/aa1c54aa-9ba0-4475-98c0-aaae7e8b0efc)
````
3.	Ubah mode menjadi ON UPDATE CASCADE ON DELETE RESTRICT
````
![image](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum-3/assets/115562487/43e63126-06b2-41f5-bcb6-7e00ad1e0d5c)
````
4.	Lakukan perubahan data pada table dosen (kd_ds)
````
![image](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum-3/assets/115562487/5f2d3f68-7d41-4c8e-ae73-ae9d7f711574)
````
5.	Lakukan penghapusan data pada table dosen
````
![image](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum-3/assets/115562487/963f3499-2222-4751-80c8-687d44892359)
````
6.	Ubah mode menjadi ON UPDATE CASCADE ON DELETE SET NULL
````
![image](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum-3/assets/115562487/60b95e4f-870f-40a1-a55f-21f51356cf8a)
````
7.	Lakukan penghapusan data pada table dosen
````
![image](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum-3/assets/115562487/64398113-7274-4913-8bcc-7bf04c1edc16)
````
EVALUASI DAN PERTANYAAN
````
Apa bedanya penggunaan RESTRICT dan penggunaan CASCADE
RESTRICT dan CASCADE adalah dua jenis aturan referensial (referential integrity rules) yang digunakan dalam basis data relasional untuk mengatur tindakan yang terjadi ketika data pada suatu tabel dihapus atau diubah.
RESTRICT: Jika aturan RESTRICT diterapkan pada kunci referensial, maka data tidak dapat dihapus atau diubah pada tabel utama (parent table) jika ada data yang masih terkait pada tabel anak (child table). Dalam hal ini, akan muncul pesan kesalahan dan operasi akan dibatalkan.
CASCADE: Jika aturan CASCADE diterapkan pada kunci referensial, ketika data pada tabel utama dihapus atau diubah, aksi tersebut akan diikuti dengan menghapus atau mengubah data yang terkait pada tabel anak. Dalam hal ini, operasi akan dilanjutkan tanpa pesan kesalahan dan data pada tabel anak akan dihapus atau diubah sesuai dengan aturan CASCADE.
````
Kesimpulan
````
RESTRICT dan CASCADE digunakan untuk memastikan konsistensi data pada tabel relasional. Aturan RESTRICT menghindari penghapusan atau perubahan data yang akan mengganggu konsistensi data, sedangkan aturan CASCADE menghapus atau mengubah data terkait pada tabel anak ketika data pada tabel utama dihapus atau diubah. Pilihan antara RESTRICT atau CASCADE tergantung pada kebutuhan bisnis dan hubungan antara tabel pada basis data.
````

