# ⚡ Santetly - Occult Cloud Platform

![Visitor Count](https://komarev.com/ghpvc/?username=nicodeanto-santetly&label=Views&color=00AA13&style=flat)

Sebuah studi kasus UI/UX Web Application modern yang mengadaptasi pola interaksi *SuperApp* kontemporer dengan tema transendental-satir. Dirancang khusus dalam arsitektur *single-file* responsif tanpa scrolling vertikal (*single-viewport*), mendukung simulasi sensor perangkat (*NFC Tap*), verifikasi NIK mandiri, multi-select santet, dan integrasi kanal pembayaran nasional.

---

## 📱 Live Demo

Akses langsung prototipe aplikasi:  
👉 **[https://nicodeanto.github.io/santet-superapp/](https://nicodeanto.github.io/santet-superapp/)**

---

## ✨ Fitur & Pembaruan Sistem

- **Beranda Santetly & Dompet SantetPay**:
  - Saldo terpadu *SantetPay Plus* dengan akses kilat kirim mahar, cek NFC, dan aktivasi PRO Tier.
  - Carousel voucher promo (Diskon Weton Kliwon 30% dan Cashback Rp50.000).
- **Verifikasi NIK Terintegrasi DUKCAPIL**:
  - Validasi ketat format 16 digit angka.
  - Dropdown contoh cepat langsung di kolom input (mencakup *Nicodemus Rusdiyanto*, *Astri Purnani*, *Ferdinand Arya*, dan *Vito Satria*).
  - *Dynamic Target Generator*: Menghasilkan identitas nama, tanggal lahir, domisili, dan weton/neptu otomatis jika pengguna mengetik NIK bebas lainnya.
  - Animasi pemindaian sinkronisasi server DUKCAPIL berdurasi ~1,4 detik.
- **Katalog Jenis Santet (Multi-Select & Akumulasi Otomatis)**:
  - Kemampuan memilih lebih dari 1 jenis gangguan sekaligus dengan perhitungan mahar real-time.
  - Nominal harga di atas 100k menggunakan 3 digit unik acak.
  - Pilihan sanksi reguler & PRO:
    - *Dislokasi Kelingking* (Hantaman sudut perabot) — Rp25.000
    - *Malfungsi Bersin* (Gatal klimaks lenyap) — Rp20.000
    - *Rahang Menguap* (Mulut terbuka, kantuk macet) — Rp22.000
    - *Spasme Okular* (Kedutan mata pas meeting) — Rp27.000
    - *Amnesia Bicara* (Lupa total materi penting) — Rp30.000
    - `[PRO]` *Fraktur Sandal* (Putus di kubangan hitam) — Rp125.484
    - `[PRO]` *Drop 1% Scan Kasir* (Layar padam pas antre) — Rp150.592
    - `[PRO]` *Gatal Tak Kena Titik* (Dikorek tak pernah pas) — Rp115.871
- **Kasir Mahar Terintegrasi**:
  - Rincian list lengkap santet yang dipilih beserta harga satuannya.
  - Pilihan voucher promo interaktif (Diskon 30% & Potongan Langsung Rp50.000).
  - **QRIS Standar BI & ASPI**: Lengkap dengan NMID resmi merchant dan logo GPN nasional.
  - **Virtual Account**: Pilihan 10 bank teratas di Indonesia (BCA, Mandiri, BRI, BNI, BSI, CIMB Niaga, BTN, Permata, Danamon, OCBC NISP) dengan format prefix resmi dan tombol salin.
  - **Simulasi Tap NFC**: Uji tempel kartu e-Money, Flazz, atau Brizzi.
- **Animasi Jam Pasir & Tabel Riwayat (History)**:
  - Animasi telemetri rotasi jam pasir (*hourglass*) presisi 3 detik pasca konfirmasi.
  - Notifikasi modal native app (tanpa browser alert kaku).
  - Penyimpanan otomatis ke tabel riwayat transaksi (kode resi, target, daftar santet, dan status).

---

## 🛠️ Arsitektur Teknologi

- **Markup & Struktur**: HTML5 (Single-File Architecture)
- **Styling & Theme**: Tailwind CSS (CDN) + Emerald Light & Occult Dark Mode
- **Tipografi**: Plus Jakarta Sans & Cinzel (Google Fonts)
- **Ikonografi**: Google Material Symbols Outlined
- **Runtime**: Browser Engine Native (Zero Dependency / No Build Step)

---

## 📖 Alur Penggunaan

1. **Beranda**: Klik **Mulai Kalibrasi Target Sasaran**.
2. **Tahap 1 - Verifikasi NIK**: Masukkan 16 digit NIK atau pilih dari dropdown contoh, lalu klik **Cek NIK** untuk verifikasi identitas.
3. **Tahap 2 - Jenis Santet**: Centang 1 atau lebih jenis santet yang diinginkan (aktifkan status PRO di kanan atas jika memilih santet PRO).
4. **Tahap 3 - Kasir Pembayaran**: Tinjau list santet yang dipilih, terapkan voucher diskon, pilih metode (QRIS, Virtual Account, atau NFC), lalu klik **Konfirmasi & Luncurkan Sanksi**.
5. **Transmisi & Riwayat**: Tunggu animasi jam pasir berputar 3 detik hingga notifikasi sukses muncul, lalu cek pencatatannya di menu **Riwayat**.

---

## 📂 Menjalankan Secara Lokal

```bash
# Klon repositori
git clone [https://github.com/nicodeanto/santet-superapp.git](https://github.com/nicodeanto/santet-superapp.git)

# Masuk ke direktori
cd santet-superapp

# Buka langsung di browser
open index.html    # macOS
xdg-open index.html # Linux
start index.html   # Windows
