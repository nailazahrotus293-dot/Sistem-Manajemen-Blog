Sistem Manajemen Blog (Content Management System/CMS) merupakan aplikasi berbasis web yang dirancang untuk memudahkan pengguna dalam mengelola konten blog secara terstruktur dan efisien. Sistem ini dibangun menggunakan bahasa pemrograman PHP, database MySQL, serta JavaScript dengan pendekatan asynchronous menggunakan Fetch API sehingga proses pengolahan data dapat dilakukan tanpa perlu memuat ulang halaman.

Aplikasi ini memiliki tiga fitur utama, yaitu pengelolaan data penulis, artikel, dan kategori artikel. Pada bagian penulis, pengguna dapat menambahkan, mengedit, menampilkan, dan menghapus data penulis yang terdiri dari nama, username, password, serta foto profil. Data password disimpan secara aman menggunakan enkripsi.

Pada bagian artikel, pengguna dapat mengelola konten artikel yang mencakup judul, isi, gambar, kategori, penulis, serta tanggal publikasi yang dihasilkan secara otomatis oleh sistem. Setiap artikel wajib memiliki gambar dan terhubung dengan data penulis serta kategori yang sudah tersedia.

Sementara itu, pada bagian kategori artikel, pengguna dapat mengelompokkan artikel berdasarkan kategori tertentu sehingga memudahkan dalam pengorganisasian konten.

Seluruh fitur dalam sistem ini menerapkan operasi CRUD (Create, Read, Update, Delete) yang berjalan secara asynchronous untuk meningkatkan pengalaman pengguna. Selain itu, sistem juga dilengkapi dengan validasi data dan keamanan seperti penggunaan prepared statements, pembatasan ukuran file upload, serta sanitasi output untuk mencegah serangan berbahaya.

Dengan adanya sistem ini, pengelolaan blog menjadi lebih mudah, cepat, dan terorganisir.
