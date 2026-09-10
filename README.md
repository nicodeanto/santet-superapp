# ⚡ Santet Online - SuperApp Occult Transmission System

Sebuah eksplorasi konsep UI/UX modern berbasis Web Application yang memadukan pola interaksi *SuperApp* kontemporer (ala Gojek, Grab, Halodoc) dengan tema transendental-satir. Proyek ini dibuat sebagai studi kasus perancangan antarmuka single-page, pengelolaan state reaktif tanpa framework berat, serta integrasi simulasi sensor perangkat (*NFC Tap*).

---

## 📱 Live Demo

Akses langsung prototipe aplikasi:  
👉 **[https://nicodeanto.github.io/santet-superapp/](https://nicodeanto.github.io/santet-superapp/)**

---

## ✨ Fitur Utama

- **Single-Viewport Layout**: Antarmuka terdesain pas 1 layar (`100vh` tanpa scrolling vertikal) dengan sistem alur 4 tahap wizard.
- **Validasi Data Target (DUKCAPIL Preset)**: Sistem verifikasi NIK 16 digit yang memetakan nama lengkap, jenis kelamin, domisili, hingga kalkulasi weton/neptu target secara otomatis.
- **Katalog Anomali Keseharian**: Pilihan gangguan kinetik ringan yang sangat spesifik (misal: *Kelingking Nabrak Meja*, *Bersin Ngga Jadi*, *Nguap Ngga Jadi*, dll).
- **Logika Eksekusi Fleksibel**:
  - **Instan**: Transmisi aktif segera setelah mahar terverifikasi (jalur PayLater otomatis terkunci).
  - **Sesuai Tanggal**: Penjadwalan tanggal anomali dengan opsi cicilan *PayLater Gaib 3x*.
- **Multi-Kanal Pembayaran**:
  - Simulasi Sensor **Tap E-Money NFC** (Flazz, e-Money, Brizzi) dengan audio feedback.
  - **QRIS Dinamis** & **Virtual Account**.
  - Proteksi sistem terhadap jalur riba kartu kredit.
- **Dual-Theme Engine**: Transisi instan antara *Emerald Light Mode* dan *CyberOccult Dark Mode*.
- **Tingkat Keanggotaan (PRO Tier)**: Akses instan untuk membuka tipe anomali eksklusif.
- **E-Resi & Integrasi WhatsApp**: Terbitan tanda transmisi resmi lengkap dengan kode unik resi yang dapat langsung dibagikan.

---

## 🛠️ Tech Stack

- **Markup & Struktur**: HTML5 (Single File Architecture)
- **Styling**: Tailwind CSS (via CDN)
- **Tipografi**: Google Fonts (*Plus Jakarta Sans* & *Cinzel*)
- **Ikonografi**: Google Material Symbols Outlined
- **Audio & Haptic**: Web Audio API (Synthesizer bawaan peramban tanpa aset eksternal)

---

## 📖 Panduan Penggunaan

1. **Tahap 1: Verifikasi Target**
   - Pilih salah satu dari 4 contoh profil preset cepat, atau masukkan NIK 16-digit secara manual.
   - Periksa data weton dan domisili yang terisi otomatis, lalu klik **Lanjut ke Pilihan Santet**.
2. **Tahap 2: Tentukan Jenis Anomali & Jadwal**
   - Pilih salah satu kartu gangguan (aktifkan tombol `PRO` di kanan atas untuk opsi khusus).
   - Tentukan mode transmisi: **Eksekusi Instan** atau **Sesuai Tanggal**.
3. **Tahap 3: Pembayaran Mahar**
   - Pilih metode pembayaran yang diinginkan (QRIS, VA Bank, atau Tap NFC).
   - Jika memilih NFC, klik tombol **Tap Kartu** pada modal simulasi sensor.
4. **Tahap 4: Resi Transmisi**
   - Sistem akan menerbitkan kode resi telemetri resmi.
   - Klik **Bagikan Resi** untuk mengirimkan ringkasan ke WhatsApp.

---

## 📂 Menjalankan Secara Lokal

Tidak memerlukan instalasi server lokal (Node.js/PHP/Python).

1. Clone repositori ini:
   ```bash
   git clone [https://github.com/nicodeanto/santet-superapp.git](https://github.com/nicodeanto/santet-superapp.git)
