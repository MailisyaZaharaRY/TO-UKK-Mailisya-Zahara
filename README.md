# TO-UKK-Mailisya-Zahara
1. Fitur Utama:
Menambah Barang:
Form untuk menambah data barang baru ke dalam sistem.
Input untuk nama barang, kategori, stok, harga, dan tanggal masuk.
Menambah Kategori:
Form untuk menambah kategori baru.
Input untuk nama kategori yang dapat dipilih saat menambah barang.
Menampilkan Daftar Barang:
Tabel untuk menampilkan semua barang yang ada di sistem.
Setiap item memiliki informasi lengkap seperti nama barang, kategori, stok, harga, dan tanggal masuk.
Edit Barang:
Fitur untuk mengedit data barang yang ada.
Edit bisa dilakukan pada nama barang, kategori, stok, harga, dan tanggal masuk.
Hapus Barang:
Fitur untuk menghapus barang dari database setelah konfirmasi.
2. Tambahan Fitur:
Pencarian Barang:
Fitur pencarian untuk mencari barang berdasarkan nama barang, kategori, atau harga.
Pagination (Pembagian Halaman):
Menampilkan data barang dalam beberapa halaman agar tidak terlalu banyak data dalam satu halaman.
Pengguna bisa menavigasi halaman menggunakan tombol pagination.
Export Data ke Excel dan PDF:
Fitur untuk mengunduh data barang dalam format Excel (menggunakan PhpSpreadsheet) dan PDF (menggunakan TCPDF).
Data yang diekspor berisi informasi lengkap tentang barang dan kategori.
3. Desain Tampilan:
Bootstrap telah digunakan untuk mempercantik tampilan halaman, termasuk form input, tabel, dan tombol aksi seperti export dan edit.
Tampilannya responsif dan mudah digunakan di perangkat desktop maupun mobile.
4. Struktur Database:
Tabel Kategori (Kategori)
ID (INT) - Primary Key
NamaKategori (VARCHAR)
Tabel Barang (Barang)
ID (INT) - Primary Key
NamaBarang (VARCHAR)
KategoriID (INT) - Foreign Key, merujuk ke Kategori.ID
Stok (INT)
Harga (BIGINT)
TanggalMasuk (DATE)
5. Teknologi yang Digunakan:
PHP untuk server-side scripting.
MySQL sebagai database management system.
Bootstrap untuk desain antarmuka yang responsif.
