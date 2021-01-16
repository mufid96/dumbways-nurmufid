a. Deploy Jenkins dan mulai server
b. Buka halaman utama Jenkins kemudian klik Manage Jenkins. 
c. Di halaman Manage Jenkins, klik Setup Security.
d. Kemudian centang pilihan kotak Enable Security.
e. Di menu Security Realm pilih Jenkins own user database dan centang kotak Allow users to sign up.
f. Kemudian akan muncul menu konfigurasi Sign Up, dilanjut isi form sesuai keinginan, maka akun berhasil dibuat.
g. saat sudah login akan terlihat di pojok kanan atas akun yang sudah dibuat.
h. Lalu kembali ke Manage Jenkins dan pilih Configure Global Security. Hilangkan centang untuk kotak opsi Allow users to sign up untuk memastikan tidak ada pengguna lain membuat akun tanpa izin. 
i. Langkah selanjutnya mengatur hak akses dan izin tiap akun user yang sudah dibuat. Ada pilihan Matrix-based security & Project-base project authorization strategy.
j. Simpan. Logout kemudian login lagi.
k. Halaman login sudah muncul. 
