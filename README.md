# ⚡ Santet SuperApp - Occult Transmission System

Sebuah studi kasus UI/UX Web Application modern yang mengadaptasi pola interaksi *SuperApp* kontemporer (Gojek, Grab, OVO, Livin') dengan tema transendental-satir. Dirancang khusus dalam arsitektur *single-file* responsif tanpa scrolling vertikal (*single-viewport*), mendukung simulasi sensor perangkat (*NFC Tap*), verifikasi NIK mandiri, serta integrasi kanal pembayaran nasional.

---

## 📱 Live Demo

Akses langsung prototipe aplikasi:  
👉 **[https://nicodeanto.github.io/santet-superapp/](https://nicodeanto.github.io/santet-superapp/)**

---

## ✨ Fitur & Pembaruan Sistem

- **Beranda SuperApp & Loyalty Reward**: Tampilan ringkas berisi dompet *SantetPay Plus*, voucher promo diskon weton kliwon 30%, cashback transaksi perdana, dan menu jalan pintas layanan.
- **Verifikasi NIK Mandiri (DUKCAPIL Engine)**:
  - Validasi ketat format 16-digit angka.
  - Efek visual pemindaian sinkronisasi server DUKCAPIL berdurasi ~1,8 detik.
  - Pemetaan otomatis identitas target (nama lengkap, jenis kelamin, domisili, serta kalkulasi weton/neptu).
  - Basis data target terdaftar mencakup *Nicodemus Rusdiyanto*, *Astri Purnani*, *Ferdinand Arya*, dan *Vito Satria*.
- **Katalog 8 Sanksi Probabilitas (Termasuk 3 Tier PRO)**:
  - *Dislokasi Kinetik Kelingking* (Hantaman presisi sudut perabot)
  - *Malfungsi Refleks Bersin* (Gatal klimaks lenyap seketika)
  - *Kompensasi Rahang Menguap* (Mulut terbuka lebar, kantuk terhambat)
  - *Spasme Okular Waktu Genting* (Kedutan kelopak mata saat situasi krusial)
  - *Amnesia Kognitif Giliran Bicara* (Lupa materi presentasi di depan umum)
  - `[PRO]` *Fraktur Sandal di Kubangan* (Pengait putus di titik becek)
  - `[PRO]` *Drop Baterai 1% Pas Scan Kasir* (Layar padam di antrean pembayaran)
  - `[PRO]` *Gatal Kuping Tak Kena Titik* (Sensasi gatal yang tak kunjung terjangkau)
- **Kanal Pembayaran Terintegrasi**:
  - **QRIS Standar BI & ASPI**: Dilengkapi bingkai resmi nasional, identitas merchant, NMID, dan logo GPN.
  - **10 Bank Terbesar di Indonesia**: Pilihan Virtual Account dengan format kode bayar resmi (BCA, Mandiri, BRI, BNI, BSI, CIMB Niaga, BTN, Permata, Danamon, OCBC NISP) lengkap dengan fitur salin nomor.
  - **Simulasi Sensor Tap NFC**: Uji tempel kartu e-Money, Flazz, atau Brizzi dengan deteksi saldo instan.
  - **PayLater Karma**: Opsi cicilan 3x khusus untuk mode transmisi terjadwal.
- **Animasi Telemetri & Tabel Riwayat (History)**:
  - Efek pemrosesan transmisi sinyal satelit astral selama ~2,5 detik pasca konfirmasi mahar.
  - Pengalihan otomatis kembali ke beranda.
  - Pencatatan transaksi real-time ke dalam tabel riwayat (kode resi, target, jenis anomali, dan status).

---

## 🛠️ Arsitektur Teknologi

- **Markup & Struktur**: HTML5 (Single File Architecture)
- **Styling**: Tailwind CSS (via CDN)
- **Tipografi**: Google Fonts (*Plus Jakarta Sans* & *Cinzel*)
- **Ikonografi**: Google Material Symbols Outlined
- **Runtime**: Browser Engine Native (Zero Dependency / No Build Step)

---

## 📖 Alur Penggunaan

1. **Beranda & Promo**: Periksa saldo SantetPay, klaim voucher diskon weton kliwon, atau klik **Mulai Kalibrasi Target**.
2. **Verifikasi NIK**: Masukkan 16 digit NIK target, lalu klik **Cek NIK** untuk melihat animasi sinkronisasi basis data DUKCAPIL.
3. **Pemilihan Sanksi & Jadwal**: Pilih salah satu dari 8 sanksi probabilitas (aktifkan tombol `BASIC / PRO TIER` di kanan atas untuk membuka fitur eksklusif). Tentukan mode instan atau sesuai tanggal.
4. **Pembayaran Mahar**: Pilih kanal pembayaran (QRIS BI, salah satu dari 10 bank Virtual Account, atau Tap NFC).
5. **Transmisi & Riwayat**: Amati proses peluncuran frekuensi transmisi, lalu pantau statusnya kapan saja melalui menu **Riwayat Transaksi**.

---

## 📂 Menjalankan Secara Mandiri

Tidak membutuhkan instalasi server (Node.js/Python/PHP):

```bash
# Klon repositori
git clone [https://github.com/nicodeanto/santet-superapp.git](https://github.com/nicodeanto/santet-superapp.git)

# Masuk ke direktori
cd santet-superapp

# Buka file langsung di browser
open index.html    # macOS
xdg-open index.html # Linux
start index.html   # Windows
