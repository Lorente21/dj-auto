# Spotipi - Android APK Package

Aplikasi ini dikemas dari file HTML menjadi aplikasi Android APK mandiri dengan Android WebView, dukungan audio latar belakang, dan pemilih file musik asli.

---

## 🚀 3 CARA MENDAPATKAN FILE .APK

### Cara 1: Kompilasi Otomatis via GitHub Actions (PALING MUDAH - TANPA INSTALL APAPUN)
1. Ekstrak file zip ini ke sebuah folder.
2. Buat repository baru di **GitHub** (gratis): [github.com/new](https://github.com/new)
3. Upload semua file dalam folder ini ke GitHub.
4. Buka tab **Actions** di repository GitHub Anda.
5. Klik workflow **Build Android APK** lalu klik **Run workflow**.
6. Dalam waktu ~2 menit, file `Spotipi-debug-apk` siap di-download langsung ke HP Anda dan langsung dapat di-install!

---

### Cara 2: Buka di Android Studio (PC / Laptop)
1. Download dan buka **Android Studio**: [developer.android.com/studio](https://developer.android.com/studio)
2. Klik **Open** lalu pilih folder hasil ekstrak zip ini.
3. Tunggu hingga Gradle selesai sync.
4. Di menu atas, klik **Build** -> **Build Bundle(s) / APK(s)** -> **Build APK(s)**.
5. Setelah selesai, klik notifikasi **locate** untuk mendapatkan file `app-debug.apk`.
6. Kirim file `.apk` tersebut ke HP Android Anda melalui WhatsApp, Telegram, Google Drive, atau kabel USB, lalu install!

---

### Cara 3: Build Langsung di HP Android via Termux (Tanpa PC)
Jika Anda hanya menggunakan HP Android:
1. Buka aplikasi **Termux** di HP Android Anda.
2. Pasang JDK & Gradle:
   ```bash
   pkg update && pkg install openjdk-17 gradle
   ```
3. Masuk ke folder proyek ini dan jalankan:
   ```bash
   gradle assembleDebug
   ```
4. File APK berada di `app/build/outputs/apk/debug/app-debug.apk`.

---

## 📱 CARA INSTALL LANGSUNG KE HP TANPA COMPILE (WebAPK / PWA)
Jika Anda ingin aplikasi ini langsung terpasang di HP sekarang juga:
1. Buka aplikasi web ini di browser HP Android Anda (Google Chrome).
2. Ketuk tombol **Install ke Android (WebAPK)** atau ketuk menu **Titik Tiga (⋮)** di pojok kanan atas browser.
3. Pilih **"Install aplikasi"** atau **"Tambahkan ke Layar Utama"**.
4. Android secara otomatis membuatkan aplikasi mandiri dengan ikon dan fungsi penuh seperti aplikasi APK!

---

## ⚙️ Konfigurasi Aplikasi
- **Nama Aplikasi**: Spotipi
- **Package ID**: com.autodj.player
- **Versi**: 1.0.0 (1)
- **Min SDK**: Android 7.0 (API 24)
- **Target SDK**: Android 14 (API 34)