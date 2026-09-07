# TikTok Enhancer - LSPosed Module

[![Release](https://img.shields.io/github/v/release/Luckyfr1945/tiktok-enhancer?style=for-the-badge&logo=github&color=00A884)](https://github.com/Luckyfr1945/tiktok-enhancer/releases/latest)
[![Build APK](https://img.shields.io/github/actions/workflow/status/Luckyfr1945/tiktok-enhancer/build.yml?style=for-the-badge&logo=githubactions&logoColor=white&label=Build%20APK)](https://github.com/Luckyfr1945/tiktok-enhancer/actions)
[![Downloads](https://img.shields.io/github/downloads/Luckyfr1945/tiktok-enhancer/total?style=for-the-badge&logo=android&color=25D366)](https://github.com/Luckyfr1945/tiktok-enhancer/releases)

Modul LSPosed modern berdesain identik **WaEnhancer** khusus untuk aplikasi **TikTok** (`com.ss.android.ugc.trill` & `com.zhiliaoapp.musically`). Dilengkapi antarmuka *floating glassmorphism pill* ala iOS, dukungan multi-bahasa, fitur anti-tarik pesan, blokir iklan, bypass wilayah, dan optimasi performa ekstrem.

📥 **Unduh Versi Terbaru:** [GitHub Releases](https://github.com/Luckyfr1945/tiktok-enhancer/releases/latest)

---

## 🌟 Fitur Utama

### 1. Obrolan DM
- **Anti-Hapus Pesan DM:** Pesan masuk tetap tersimpan di inbox obrolan meskipun pengirim menekan tombol tarik pesan.
- **Kustomisasi Penanda Pesan:** Pilihan tanda ditarik (`🚫`, `🗑️`, `[Ditarik]`, atau kustom teks).
- **CrashShield Zero-Lag:** Struktur cache memory terikat (LRU & WeakHashMap) tanpa query DAO berlebih.

### 2. Feed & Pemutaran
- **Blokir Iklan:** Menghilangkan video bersponsor dan iklan komersial di FYP secara instan.
- **Bilah Durasi Video:** Memaksa progress seek bar selalu muncul di semua video untuk navigasi durasi yang mudah.
- **Putar Otomatis:** Otomatis scroll ke video berikutnya saat video selesai diputar.
- **Kualitas Tertinggi:** Memaksa streaming video pada resolusi dan bitrate terbaik.

### 3. Wilayah & Jaringan
- **Bypass Wilayah:** Membuka pembatasan regional TikTok tanpa perlu mencabut kartu SIM fisik.

### 4. Performa & Hemat RAM (Level 4 Extreme & Ultra-Lite)
- **Hemat RAM Otomatis:** Memangkas beban RAM fisik hingga 40-60% saat aplikasi berjalan maupun di latar belakang.
- **Mode RAM Ekstrem (Ultra-Lite):** Menetralkan ByteDance GC Blocker dan menekan alokasi heap hingga konsumsi RAM < 700 MB.
- **Kunci Buffer Video (TTVideoEngine):** Membatasi ring buffer video dan cache AVMDL dengan zero-copy GPU texture rendering.
- **Blokir Siaran Live di FYP (Dual-Layer):** Menyaring kartu Live langsung dari `FeedItemList` dan menonaktifkan engine live streaming agar tidak menyedot ratusan megabyte RAM.
- **Blokir Analitik & Telemetri:** Mematikan thread pengumpul log ByteDance (*TeaAgent*, *AppLog*, *APM Monitor*) di latar belakang.
- **Pembersihan Cache Otomatis:** Membersihkan cache video lama saat aplikasi dibuka.

### 5. Unduhan
- **Unduh Tanpa Watermark:** Menyimpan video bersih langsung tanpa logo watermark TikTok saat menekan tombol simpan.

---

## 🎨 Desain & Tampilan
- **Arsitektur 2 Tab:** Tab Beranda (*Hero Status Card*, *Info Perangkat*, *Deteksi Versi TikTok*, & *Cadangan Pengaturan*) dan Tab Fitur.
- **iOS Glassmorphism Floating Pill:** Navigasi bawah mengambang dengan efek kaca akrilik transparan multi-lapis dan pantulan cahaya kristal.
- **Multi-Bahasa & Gaya Todep:** Bahasa Indonesia & English dengan copywriting lugas dan to-the-point tanpa istilah bertele-tele.
- **Bebas Akses Root (su):** Menerapkan mekanisme broadcast receiver internal dan dialog pop-up restart langsung di layar TikTok.

---

## 📱 Kompatibilitas
- **Target Aplikasi:**
  - `com.ss.android.ugc.trill` (TikTok SEA / Indonesia)
  - `com.zhiliaoapp.musically` (TikTok Global)
  - `com.dong.multirun` (Dukungan Cloner / Dual App)
- **Framework:** LSPosed / Zygisk Next / Shamiko
- **Android:** Android 8.0 (API 26) hingga Android 15/16 (API 36)

---

## 📥 Unduh & Pasang

1. Unduh file APK versi terbaru dari halaman [GitHub Releases](https://github.com/Luckyfr1945/tiktok-enhancer/releases/latest).
2. Pasang (*install*) APK pada perangkat Android Anda.
3. Buka **LSPosed Manager**, aktifkan modul **TikTok Enhancer**, dan centang target aplikasi TikTok.
4. Buka aplikasi TikTok Enhancer untuk mengaktifkan fitur dan optimasi sesuai kebutuhan Anda.
