Jika Anda membuat QR Code untuk link: [https://wahyusetiawan.github.io/resto/?meja=1](https://wahyusetiawan.github.io/resto/?meja=1), maka aplikasi otomatis mengenali itu Meja 1.

Jika Anda membuat QR Code untuk link: [https://wahyusetiawan.github.io/resto/?meja=2](https://wahyusetiawan.github.io/resto/?meja=2), maka otomatis angka di pojok kanan atas berubah jadi Table 2, dan pesanan akan masuk ke kasir sebagai Meja 2.

Begitu seterusnya untuk ?meja=3, ?meja=4, ?meja=99.

Anda cukup men-generate gambar QR Code yang berbeda-beda untuk masing-masing link tersebut, lalu cetak dan tempel di meja fisik yang sesuai.

Sistem kita sudah menggunakan Decoupled Architecture (terpisah antara pelanggan dan kasir demi keamanan).

File index.html (kode di atas) adalah yang akan diakses oleh Pelanggan (lewat HP saat scan QR).

Sedangkan untuk Kasir, Anda harus menggunakan file kasir.html yang kode penuhnya sudah saya berikan di balasan saya sebelumnya (yang ada tampilan Login PIN dan Dashboard warna putih/indigo).

Cara Praktis Membukanya:

Di komputer atau tablet Kasir (di meja kasir fisik), buka browser (Chrome/Safari).

Ketik alamat repositori GitHub Anda, dan tambahkan /kasir.html di belakangnya.

Contoh: [https://wahyusetiawan.github.io/resto/kasir.html](https://wahyusetiawan.github.io/resto/kasir.html)

Simpan halaman tersebut sebagai Bookmark di komputer kasir, sehingga karyawan Anda tinggal mengekliknya setiap pagi, login menggunakan PIN yang ada di Google Sheets, dan memantau pesanan yang masuk secara otomatis!
