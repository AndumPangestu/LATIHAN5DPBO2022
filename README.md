# LATIHAN5DPBO2022


SS : https://github.com/AndumPangestu/LATIHAN5DPBO2022/issues/1#issue-1174890965


## Penjelasan

a. pada program ini, semua font dari teks diubah menjadi calibri dan beberapa element, seperti nama kolom form diubah ukurannya menjadi 16. kedua pengubahan tersebut dilakukan melalui menu properties.

b. semua variabel input diubah menjadi txt kemudain diikuti dengan nama inputannya dengan diawali huruf kapital di awal katanya. contoh txtNim.

c. untuk validas inputan, digunakan pengecekan melalui panjang dari string masukan. jika panjang setiap string masukan lebih besar dari 0 (terdapat inputan atau tidak kosong) maka dilakukan penambahan atau pengubahan data.

![image](https://user-images.githubusercontent.com/91056905/159208302-e521975c-79fa-4767-87f1-fa4fc87a769e.png)

jika inputan tidak lengkap maka tidak akan dilakukan penambhan atau pengubahan data serta akan ditampilkan pesan kegagalan tersebut

![image](https://user-images.githubusercontent.com/91056905/159208385-b789fc09-83de-4cc5-a005-b5432fffb8f2.png)

d. untuk menghapus data pada label inputan, ditambahkan satu method emptyTextFields() yang berfungsi untuk mengosongkan label inputan setiap kali operasi berhasil dilakukan. method tersebut akan dipanggil di setiap akhir operasi seperti operasi add, cancel, update dan delete.

![image](https://user-images.githubusercontent.com/91056905/159208643-cbedd55d-3e8a-4456-b55c-91dbcf961099.png)

e. update tabel pada setiap ada perubahan dilakukan dengan pemanggilan jTable1.setModel(setTable()) pada setiap akhir operasi.

* bonus : dilakukan penambhan atribut inputan baru, yaitu inputan kelas.
