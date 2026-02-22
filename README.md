# cek
konfigurasi

https://drive.google.com/drive/folders/1YqubFrdnW7pRYtI6XgPv9lx4c6KqsCPT?usp=sharing

https://drive.google.com/drive/my-drive

[sipma.zip](https://github.com/user-attachments/files/25467412/sipma.zip)

[sikma.zip](https://github.com/user-attachments/files/25467417/sikma.zip)

🔑 php artisan key:generate
Fungsi:
Membuat application key (APP_KEY) untuk aplikasi Laravel.
Penjelasan:
Perintah ini digunakan untuk menghasilkan kunci enkripsi yang akan disimpan secara otomatis pada file .env di bagian APP_KEY. Kunci ini digunakan oleh Laravel untuk proses enkripsi data, pengamanan session, cookie, serta autentikasi pengguna.

Jika application key belum dibuat, aplikasi Laravel tidak dapat berjalan dengan normal dan biasanya akan menampilkan pesan error terkait enkripsi.
  1️⃣ php artisan serve
Fungsi:
Menjalankan server lokal Laravel.
Penjelasan:
Digunakan untuk menjalankan aplikasi pada server development lokal. Secara default berjalan di:
http://127.0.0.1:8000

2️⃣ php artisan make:model NamaModel
Fungsi:
Membuat model baru.
Penjelasan:
Model digunakan sebagai penghubung antara aplikasi dan tabel di database.
Contoh:
php artisan make:model Anggota

3️⃣ php artisan make:controller NamaController
Fungsi:
Membuat controller baru.
Penjelasan:
Controller berfungsi untuk mengatur logika aplikasi dan menghubungkan model dengan view.
Contoh:
php artisan make:controller AnggotaController

4️⃣ php artisan make:migration create_nama_tabel
Fungsi:
Membuat file migration.
Penjelasan:
Migration digunakan untuk membuat atau mengubah struktur tabel pada database.
Contoh:
php artisan make:migration create_anggotas_table

5️⃣ php artisan migrate
Fungsi:
Menjalankan migration.
Penjelasan:
Digunakan untuk membuat tabel pada database sesuai dengan struktur yang telah didefinisikan dalam file migration.

6️⃣ php artisan migrate:rollback
Fungsi:
Membatalkan migration terakhir.
Penjelasan:
Digunakan untuk menghapus perubahan database pada batch migration terakhir.

7️⃣ php artisan migrate:fresh
Fungsi:
Menghapus seluruh tabel dan membuat ulang dari awal.
Penjelasan:
Perintah ini akan:
Menghapus semua tabel
Menjalankan ulang seluruh migration
Contoh:
php artisan migrate:fresh

8️⃣ php artisan migrate:fresh --seed
Fungsi:
Menghapus seluruh tabel, membuat ulang, dan mengisi data awal.
Penjelasan:
Perintah ini akan:
Menghapus semua tabel
Menjalankan migration
Menjalankan seeder
Contoh:
php artisan migrate:fresh --seed

9️⃣ php artisan db:wipe
Fungsi:
Menghapus seluruh tabel dalam database.
Penjelasan:
Digunakan untuk mengosongkan database tanpa menjalankan migration ulang.
Jika ingin membuat ulang tabel setelah itu:
php artisan migrate

🔟 php artisan make:seeder NamaSeeder
Fungsi:
Membuat file seeder.
Penjelasan:
Seeder digunakan untuk mengisi data awal ke dalam database.

1️⃣1️⃣ php artisan db:seed
Fungsi:
Menjalankan seeder.
Penjelasan:
Digunakan untuk memasukkan data awal ke dalam database berdasarkan file seeder yang telah dibuat.

1️⃣2️⃣ php artisan route:list
Fungsi:
Menampilkan daftar route.
Penjelasan:
Digunakan untuk melihat seluruh route yang terdaftar dalam aplikasi Laravel.

1️⃣3️⃣ php artisan make:middleware NamaMiddleware
Fungsi:
Membuat middleware baru.
Penjelasan:
Middleware digunakan untuk memfilter request sebelum masuk ke controller, misalnya untuk autentikasi pengguna.

1️⃣4️⃣ php artisan config:clear
Fungsi:
Menghapus cache konfigurasi.
Penjelasan:
Digunakan jika terjadi perubahan pada file konfigurasi tetapi belum terbaca oleh sistem.
