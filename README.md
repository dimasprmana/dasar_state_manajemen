**NAMA: DIMAS PERMANA**
-
**NIM: 362358302004**
-
**KELAS: 2A TRPL**
-
**Tugas Praktikum 1: Dasar State dengan Model-View**
-
1.Selesaikan langkah-langkah praktikum tersebut, lalu dokumentasikan berupa GIF hasil akhir praktikum beserta penjelasannya di file README.md! Jika Anda menemukan ada yang error atau tidak berjalan dengan baik, silakan diperbaiki.
-
2.Jelaskan maksud dari langkah 4 pada praktikum tersebut! Mengapa dilakukan demikian?
-
.Penyederhanaan Impor: Ketika aplikasi semakin besar, mengimpor setiap file model satu per satu dapat menjadi rumit dan memperbanyak kode di setiap bagian yang membutuhkan model tersebut. Dengan menggunakan data_layer.dart, Anda hanya perlu satu baris impor di setiap tempat yang membutuhkan plan dan task, yakni import 'data_layer.dart';.
-
.Pemeliharaan Kode yang Lebih Mudah: Jika di masa depan Anda menambah atau menghapus model, Anda hanya perlu menyesuaikan di data_layer.dart tanpa harus mengubah setiap file yang mengimpor model-model ini.
-
