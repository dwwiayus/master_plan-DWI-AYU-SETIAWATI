NAMA : DWI AYU SETIAWATI
NIM : 362358302073
KELAS : 2A TRPL

Praktikum 1
![Screenshot (1)](https://github.com/user-attachments/assets/c3681d49-df36-4074-b522-4fd6450185cb)

Tugas
2. pada pratikum step 4 file data_layer hanya berisi expor dari file plan dan task, itu karena agar perulangan pemanggilan class pada coding tidak terlalu banyak, dalam satu file sudah menyagkut 2 class didalamnya jadi saat import di file lain hanya menggunakan "import:data_layer.dart" saja.
3. Variabel plan digunakan untuk mengelola data state yang terkait dengan rencana di dalam widget.
4.
5. initState() berguna untuk menginisialisasi ScrollController dan menambahkan listener untuk menangani aksi saat scroll.
dispose() digunakan untuk membersihkan ScrollController setelah State dihapus agar aplikasi berjalan lebih efisien dan bebas dari kebocoran memori.

Praktikum 2
![Screenshot (3)](https://github.com/user-attachments/assets/a87ab33a-566c-4608-a191-320fbdd10fd2)

Tugas
2. yang dimaksud dengan InheritedWidget adalah PlanProvider, yang diturunkan dari kelas InheritedNotifier. InheritedWidget merupakan widget yang memungkinkan data atau state diakses oleh semua widget yang berada di dalam subtree-nya. Dengan menggunakan InheritedWidget, data dapat diteruskan ke bawah tanpa harus melewati setiap widget secara eksplisit.
3. completedCount dan completenessMessage memberikan cara yang efisien untuk menghitung jumlah tugas yang selesai dan menyusun pesan status penyelesaian dengan baik. Ini membantu menjaga kode mudah dipahami.
