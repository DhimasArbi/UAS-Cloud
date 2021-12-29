# UAS - Komputasi Awan

|                |                                  |
| -------------- | -------------------------------- |
| Dosen Pengampu | Grezio Arifiyan P. S.Kom., M.Kom |
| Email          | grez.arifiyan@gmail.com          |
| Institusi      | jti.polinema.ac.id               |

## Data Diri

|              |                               |
| ------------ | ----------------------------- |
| NIM          | **1941720169**                |
| Nama Lengkap | **Dhimas Arbi Sukma Himawan** |
| Kelas        | TI-3B                         |

#### Deploy untuk lokal testing:

1. Buka project dengan [VSCode](https://code.visualstudio.com/), kemudian buka new terminal
2. Pada terminal ketikkan perintah dibawah ini, dan tunggu sampai proses selesai
   > composer install
3. Kemudian copy .env.example menjadi .env
   > cp .env.example .env
4. Lalu menjalankan perintah berikut
   > php artisan key:generate
5. Kemudian buat database baru dengan nama "sikma"
6. Lalu kembali ke terminal sebelumnya dan ketikkan perintah berikut untuk membuat tabel pada database
   > php artisan migrate
7. Kemudian ketikkan perintah berikut untuk mengisi tabel pada database
   > php artisan db:seed
8. Lalu untuk menjalankan web ketikkan perintah berikut
   > php artisan serve

#### Deploy pada server: soon
