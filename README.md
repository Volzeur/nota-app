# nota-app

Web app untuk mengelola transaksi toko

---

## Cara Menjalankan

### 1. Download Project

> Download folder project [Google Drive](https://drive.google.com/drive/folders/1HLNesRkd6mN1ub6TYv_4RkP_OlvW4XWc?usp=sharing)
extract ke folder Laragon kalian (`C:\laragon\www\`).

---

### 2. Buka Laragon → Start All

Buka **Laragon** → klik **"Start All"**.

Pastikan Apache dan MySQL sudah hijau 

---

### 3. Buka Terminal

Laragon → **Terminal**

---

### 4. Masuk ke Folder Project

    cd nota-app

---


### 6. Setup Database

Di laragon, klik terminal lalu jalankan:

    mysql -u root -e "CREATE DATABASE db_pembayaran;"

Migrate

    php artisan migrate:fresh

---

### 7. Jalankan

    php artisan serve

Buka browser → **http://127.0.0.1:8000/nota**

### 8. Edit UI

Ubah index.blade.php aja yang lain jangan disentuh gaada hubungan sama ui/tampilan soalnya
