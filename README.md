**NAMA: DIMAS PERMANA**
-
**NIM: 362358302004**
-
**KELAS: 2A TRPL**
-
**Tugas Praktikum 1: Dasar State dengan Model-View**

1.Selesaikan langkah-langkah praktikum tersebut, lalu dokumentasikan berupa GIF hasil akhir praktikum beserta penjelasannya di file README.md! Jika Anda menemukan ada yang error atau tidak berjalan dengan baik, silakan diperbaiki.

2.Jelaskan maksud dari langkah 4 pada praktikum tersebut! Mengapa dilakukan demikian?

.Penyederhanaan Impor: Ketika aplikasi semakin besar, mengimpor setiap file model satu per satu dapat menjadi rumit dan memperbanyak kode di setiap bagian yang membutuhkan model tersebut. Dengan menggunakan data_layer.dart, Anda hanya perlu satu baris impor di setiap tempat yang membutuhkan plan dan task, yakni import 'data_layer.dart';.

.Pemeliharaan Kode yang Lebih Mudah: Jika di masa depan Anda menambah atau menghapus model, Anda hanya perlu menyesuaikan di data_layer.dart tanpa harus mengubah setiap file yang mengimpor model-model ini.

3.Mengapa perlu variabel plan di langkah 6 pada praktikum tersebut? Mengapa dibuat konstanta ?
. Plan digunakan sebagai objek untuk menyimpan data atau daftar tugas yang ingin Anda tampilkan di layar ini. Karena layar ini merupakan master plan atau rencana utama, variabel plan diperlukan untuk menyimpan informasi terkait rencana yang akan ditampilkan atau diakses di layar tersebut

4.Lakukan capture hasil dari Langkah 9 berupa GIF, kemudian jelaskan apa yang telah Anda buat!
![WhatsApp Image 2024-11-11 at 12 05 57_9d72782c](https://github.com/user-attachments/assets/0ab6a2bd-ea59-43c5-b9d3-cb4908aded16)

5.Apa kegunaan method pada Langkah 11 dan 13 dalam lifecyle state ?

answer :
initState(): Method ini digunakan untuk menginisialisasi state. Pada Langkah 11, initState() digunakan untuk menginisialisasi ScrollController yang akan mengatur perilaku scroll dan keyboard pada aplikasi.
dispose(): Method ini digunakan untuk membersihkan resource ketika widget tidak lagi digunakan1. Pada Langkah 13, dispose() digunakan untuk membersihkan ScrollController agar tidak terjadi kebocoran memori.


