# Hospital Management System

Hospital Management System adalah aplikasi berbasis web yang digunakan untuk membantu pengelolaan layanan rumah sakit secara digital. Sistem ini menyediakan fitur pengelolaan dokter, janji temu pasien, pembayaran, serta dashboard admin untuk memantau seluruh aktivitas layanan kesehatan.

## Features

### User Features
- Dashboard User
- Login & Logout
- Registrasi Pasien
- Melihat Daftar Dokter
- Melihat Daftar Poli
- Melihat Daftar Obat
- Membuat Janji Temu
- Riwayat Janji Temu
- Pembayaran Online

### Admin Features
- Dashboard Admin
- Login Admin
- Manajemen Dokter (CRUD)
- Manajemen Janji Temu
- Persetujuan / Penolakan Janji
- Manajemen Pembayaran
- Update Status Pembayaran
- Export Data Pembayaran ke Excel

---

## Built With

- PHP 8+
- CodeIgniter 4
- MySQL
- Bootstrap 5
- HTML5
- CSS3
- JavaScript

---

## Project Structure

```text
app/
├── Controllers/
├── Models/
├── Views/
├── Filters/
├── Config/

public/
writable/
tests/
Installation
1. Clone Repository
git clone https://github.com/yourusername/hospital-management-system.git
2. Enter Project Directory
cd hospital-management-system
3. Install Dependencies
composer install
4. Configure Environment

Copy file:

cp env .env

Edit database configuration:

database.default.hostname = localhost
database.default.database = hospital_db
database.default.username = root
database.default.password =
database.default.DBDriver = MySQLi
5. Run Migration
php spark migrate
6. Start Development Server
php spark serve

Open browser:

http://localhost:8080
