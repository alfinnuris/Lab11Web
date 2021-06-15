# Lab11Web
Praktikum 11: PHP Framework (Codeigniter)

Nama : Alfin Nuris Setiadi

NIM : 311910738

Kelas : TI.19.B1

Prodi : Teknik Informatika

Mata Kuliah : Pemrograman Web

Dosen Pengajar : Agung Nugroho, S. Kom., M. Kom

Sebelum memulai menggunakan Framework Codeigniter, perlu dilakukan konfigurasi pada webserver. Beberapa ekstensi PHP perlu diaktifkan untuk kebutuhan pengembangan Codeigniter :

![Screenshot (89)](https://user-images.githubusercontent.com/81596397/121980894-f601ff00-cdb6-11eb-9cb4-58434efbcbb4.png)

![Screenshot (85)](https://user-images.githubusercontent.com/81596397/121980922-01552a80-cdb7-11eb-9d5d-c171fec0b994.png)

Maka akan menjadi seperti

![Screenshot (86)](https://user-images.githubusercontent.com/81596397/121981010-26499d80-cdb7-11eb-9cf1-d75af84e7eb7.png)

Codeigniter menyediakan CLI, untuk mengaksesnya buka terminal lalu arahkan ke direktori project yang akan dibuat. Kemudian jalankan perintah php spark untuk memanggil CLI codeigniter.

![Screenshot (87)](https://user-images.githubusercontent.com/81596397/121981033-32355f80-cdb7-11eb-97e9-d8542d64bd31.png)

Codeigniter juga menyediakan mode debugging/development yang dapat menampilkan error/kesalahan dalam kode program.

![Screenshot (90)](https://user-images.githubusercontent.com/81596397/121981197-6dd02980-cdb7-11eb-8b13-55e233f55135.png)

contoh mengubah file home.php dengan mengahapus tanda ; (titik coma) maka akan terjadi muncul pesan Whoops! :

![Screenshot (93)](https://user-images.githubusercontent.com/81596397/121981832-9d336600-cdb8-11eb-9ab9-80c2bc6c9e6c.png)

konfigurasi Routing dan Controller yg terletak di app/config/Routes.php :

![Screenshot (94)](https://user-images.githubusercontent.com/81596397/121982160-35314f80-cdb9-11eb-99d2-2c4d9ba6eae4.png)

hasil output di web server maka terjadi error 404 file not found karena file/page tsb tidak ada.

![Screenshot (95)](https://user-images.githubusercontent.com/81596397/121982512-d28c8380-cdb9-11eb-9f2d-d61c0ad86427.png)

membuat Controller page.php pada direktori Controller :

![image](https://user-images.githubusercontent.com/81596397/121985159-6d875c80-cdbe-11eb-8035-a8914342fe6f.png)

![Screenshot (97)](https://user-images.githubusercontent.com/81596397/121983141-0916ce00-cdbb-11eb-8bff-935f994faa00.png)

![image](https://user-images.githubusercontent.com/81596397/121985398-e090d300-cdbe-11eb-9280-2e4da98871cd.png)

![Screenshot (98)](https://user-images.githubusercontent.com/81596397/121983147-0ae09180-cdbb-11eb-8f94-5c14bf7a10b7.png)

![Screenshot (99)](https://user-images.githubusercontent.com/81596397/121983794-18e2e200-cdbc-11eb-91a5-b9c6da1614ac.png)

![image](https://user-images.githubusercontent.com/81596397/121983864-37e17400-cdbc-11eb-8adc-b70f087ca237.png)

![image](https://user-images.githubusercontent.com/81596397/121984617-7d527100-cdbd-11eb-9391-1b92779e1bbc.png)

![image](https://user-images.githubusercontent.com/81596397/121984678-96f3b880-cdbd-11eb-8e09-7a041608ccb8.png)

![image](https://user-images.githubusercontent.com/81596397/121984701-a3781100-cdbd-11eb-9493-3def2026ef4f.png)

![image](https://user-images.githubusercontent.com/81596397/121984741-b854a480-cdbd-11eb-9e41-57f5570f2c94.png)

![image](https://user-images.githubusercontent.com/81596397/121984750-c1457600-cdbd-11eb-8b68-31f1354d4fc8.png)
