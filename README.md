# Panduan Klien SaleSwiftDesk

Panduan lengkap untuk pemilik toko yang ingin menggunakan SaleSwiftDesk sebagai aplikasi kasir.

---

## 1. Apa itu SaleSwiftDesk?

SaleSwiftDesk adalah **aplikasi kasir desktop** yang berjalan di komputer Windows toko Anda. Aplikasi ini:

- ✅ Berjalan **offline** (tidak butuh internet untuk transaksi)
- ✅ Data tersimpan **lokal** di komputer toko
- ✅ Mendukung **printer thermal** untuk struk otomatis
- ✅ Cocok untuk **toko retail, cafe, restoran, warung, dan gym**
- ✅ Satu kali bayar lisensi, pakai selamanya (lifetime)

---

## 2. Cara Mendapatkan Aplikasi

### Langkah 1: Hubungi Vendor
Hubungi vendor melalui:
- **WhatsApp**: 0851-5614-5712
- **Instagram**: @dio_firman17
- **TikTok**: @ini_bumblebee

### Langkah 2: Dapatkan File Installer
Vendor akan memberikan:
- File installer **`.msi`** (aplikasi SaleSwiftDesk)
- File lisensi **`.lic`** (khusus untuk komputer toko Anda)

### Langkah 3: Install Aplikasi
1. Download file **`.msi`** dari vendor
2. Klik dua kali file installer
3. Ikuti instruksi instalasi sampai selesai
4. Buka aplikasi dari Desktop atau Start Menu

---

## 3. Aktivasi Lisensi

### Saat Pertama Kali Buka Aplikasi

Aplikasi akan menampilkan layar aktivasi dengan:
- **Device ID** (kode unik komputer Anda)
- Tombol **"Import Lisensi"**

### Cara Aktivasi

1. Klik tombol **"Import Lisensi"**
2. Pilih file **`.lic`** yang diberikan vendor
3. Klik **"Aktivasi"**
4. Jika berhasil, aplikasi akan membuka layar setup admin

**Catatan Penting:**
- File `.lic` hanya berlaku untuk **satu komputer** (sesuai Device ID)
- Simpan file `.lic` baik-baik untuk kebutuhan install ulang
- Jika ganti komputer, hubungi vendor untuk mendapatkan `.lic` baru

---

## 4. Setup Awal Setelah Aktivasi

### 4.1. Buat Akun Admin Pertama
- Masukkan username dan password admin
- Password minimal 8 karakter
- Simpan username/password dengan aman

### 4.2. Isi Profil Toko
Buka menu **Admin → Toko**, lalu isi:
- Nama toko
- Alamat lengkap
- Nomor telepon/kontak
- Email (opsional)
- Website atau sosial media (opsional)
- NPWP/ID pajak (opsional)
- Footer struk (contoh: "Terima kasih sudah berbelanja")
- Upload logo toko (akan muncul di struk)

### 4.3. Aktifkan Metode Pembayaran
Buka menu **Admin → Pembayaran**, lalu:

#### Tunai
Sudah aktif secara default.

#### QRIS Statis
1. Upload gambar QRIS toko
2. Kasir akan menampilkan QR saat checkout

#### E-Wallet Manual
Tambahkan akun e-wallet yang dipakai toko:
- ShopeePay: nama akun, nomor HP
- GoPay: nama akun, nomor HP
- OVO: nama akun, nomor HP
- DANA: nama akun, nomor HP
- LinkAja: nama akun, nomor HP

Kasir akan memilih akun tujuan saat checkout.

#### Transfer Bank Manual
Tambahkan rekening bank toko:
- Nama bank (BCA, Mandiri, BRI, BNI, dll)
- Nomor rekening
- Nama pemilik rekening

Kasir akan memilih rekening tujuan saat checkout.

### 4.4. Tambah Kategori Produk
Buka menu **Admin → Kategori**, contoh:
- Makanan
- Minuman
- Snack
- Membership (untuk gym)

### 4.5. Tambah Produk
Buka menu **Admin → Produk**, lalu:
1. Klik **"Tambah Produk"**
2. Isi nama produk, harga, kategori
3. Upload foto produk (opsional)
4. Isi stok awal
5. Simpan

Ulangi untuk semua produk yang dijual.

### 4.6. Atur Printer Thermal (Opsional)
Jika punya printer thermal ESC/POS:

1. Buka menu **Admin → Printer Thermal**
2. Pilih jenis koneksi:
   - **USB**: klik "Daftar USB", pilih printer
   - **Bluetooth**: pastikan printer sudah paired, klik "Daftar Port", pilih COM port
   - **LAN/Wi-Fi**: isi IP printer dan port (default 9100)
3. Klik **"Cetak Halaman Test"** untuk cek koneksi
4. Simpan pengaturan

Jika tidak punya printer, biarkan mode **Simulator** (struk tetap bisa di-print lewat browser).

---

## 5. Cara Menggunakan Aplikasi

### 5.1. Login
- Masukkan username dan password
- Pilih role: Admin, Manager, atau Kasir

### 5.2. Buka POS (Kasir)
Tekan **F2** atau klik menu **POS**.

#### Cara Transaksi:
1. Klik produk untuk masukkan ke keranjang
2. Atur qty dengan tombol **+** / **-**
3. Tambah diskon item (opsional)
4. Klik **"Bayar"**
5. Pilih metode pembayaran:
   - **Tunai**: masukkan uang diterima, sistem hitung kembalian
   - **QRIS**: tampilkan QR ke customer, tandai setelah bayar
   - **E-Wallet**: pilih akun tujuan, tampilkan nomor HP ke customer
   - **Transfer Bank**: pilih rekening tujuan, tampilkan nomor rekening
6. Klik **"Selesaikan Transaksi"**
7. Struk otomatis muncul (bisa di-print atau di-save PDF)

### 5.3. Lihat Riwayat Transaksi
Tekan **F4** atau klik menu **Riwayat**.

- Admin/Manager: lihat semua transaksi
- Kasir: hanya lihat transaksi sendiri

### 5.4. Laporan Bulanan (Admin/Manager)
Tekan **F6** atau klik menu **Laporan Bulanan**.

- Pilih bulan dan tahun
- Lihat total penjualan, transaksi, dan metode pembayaran
- Export ke CSV atau print PDF

### 5.5. Shift Management (Opsional)
Jika admin mengaktifkan fitur shift:

#### Buka Shift (Kasir):
1. Klik menu **Shift**
2. Klik **"Buka Shift"**
3. Masukkan kas awal (uang di laci kasir)
4. Klik **"Mulai Shift"**

#### Tutup Shift (Kasir):
1. Klik menu **Shift**
2. Klik **"Tutup Shift"**
3. Hitung kas fisik di laci
4. Masukkan jumlah kas fisik
5. Sistem akan tampilkan variansi (selisih kas sistem vs fisik)
6. Klik **"Tutup Shift"**

---

## 6. Hotkey Navigasi

Untuk mempercepat kerja kasir:

| Tombol | Fungsi |
|--------|--------|
| **F2** | Buka POS |
| **F3** | Buka Beranda |
| **F4** | Buka Riwayat |
| **F6** | Buka Laporan Bulanan (Admin/Manager) |

---

## 7. Stok Opname

Stok opname digunakan untuk mencocokkan stok sistem dengan stok fisik di gudang/toko.

### Cara Stok Opname:
1. Buka menu **Admin → Stok Opname**
2. Klik **"Mulai Opname Baru"**
3. Hitung stok fisik setiap produk
4. Masukkan qty fisik ke kolom **"Qty Fisik"**
5. Sistem akan tampilkan selisih (qty sistem vs fisik)
6. Klik **"Selesaikan Opname"**
7. Stok sistem akan disesuaikan otomatis

**Kapan Perlu Stok Opname?**
- Setiap akhir bulan
- Setelah ada kehilangan/kerusakan barang
- Sebelum tutup buku

---

## 8. Membership Gym (Khusus Gym)

Jika toko Anda adalah gym/fitness center:

### Tambah Member:
1. Buka menu **Admin → Member**
2. Klik **"Tambah Member"**
3. Isi nama, nomor HP, email
4. Pilih paket membership (1 bulan, 3 bulan, 6 bulan, 1 tahun)
5. Sistem akan set masa aktif otomatis
6. Simpan

### Check-in Member:
1. Buka menu **POS** atau **Member**
2. Cari nama member atau scan kartu member
3. Klik **"Check-in"**
4. Sistem akan catat waktu check-in dan tampilkan status member (aktif/expired)

### Perpanjang Membership:
1. Buka menu **Admin → Member**
2. Cari member yang akan diperpanjang
3. Klik **"Perpanjang"**
4. Pilih paket baru
5. Buat transaksi pembayaran
6. Masa aktif akan diperpanjang otomatis

---

## 9. Troubleshooting

### Aplikasi Tidak Bisa Dibuka
- Pastikan Windows sudah update
- Restart komputer
- Install ulang aplikasi

### Lisensi Ditolak
- Pastikan file `.lic` sesuai dengan Device ID komputer
- Hubungi vendor untuk cek status lisensi

### Printer Tidak Terdeteksi
- Pastikan printer sudah nyala dan terhubung
- Cek kabel USB/Bluetooth/LAN
- Restart printer dan aplikasi
- Coba mode **Simulator** sebagai fallback

### Struk Tidak Keluar
- Cek kertas thermal masih ada
- Cek printer tidak paper jam
- Coba **"Cetak Halaman Test"** di menu Printer Thermal

### Stok Tidak Akurat
- Lakukan **Stok Opname** untuk sinkronkan stok sistem dengan fisik
- Cek riwayat penyesuaian inventori di menu **Admin → Stok**

### Lupa Password Admin
- Hubungi vendor untuk reset password
- Vendor akan remote atau buat akun admin baru

---

## 10. Backup Data

**PENTING:** Data aplikasi tersimpan lokal di komputer. Jika komputer rusak/hilang, data tidak bisa dikembalikan.

### Cara Backup Manual:
1. Tutup aplikasi SaleSwiftDesk
2. Buka folder:
   ```
   C:\Users\<NamaUser>\AppData\Roaming\id.saleswift.desk\data\
   ```
3. Copy file **`saleswift.db`** ke USB/cloud storage
4. Simpan backup di tempat aman

### Cara Restore Backup:
1. Tutup aplikasi SaleSwiftDesk
2. Copy file **`saleswift.db`** dari backup
3. Paste ke folder:
   ```
   C:\Users\<NamaUser>\AppData\Roaming\id.saleswift.desk\data\
   ```
4. Replace file lama
5. Buka aplikasi

**Rekomendasi:** Backup setiap akhir hari/minggu.

---

## 11. Kontak Vendor

Jika ada pertanyaan, butuh bantuan, atau ingin upgrade fitur:

- **WhatsApp**: 0851-5614-5712
- **Instagram**: @dio_firman17
- **TikTok**: @ini_bumblebee
- **Facebook**: Dio Firman

---

## 12. FAQ (Pertanyaan Umum)

### Apakah aplikasi butuh internet?
Tidak. Aplikasi berjalan offline. Internet hanya dibutuhkan untuk update aplikasi (opsional).

### Apakah data aman?
Ya. Data tersimpan lokal di komputer toko, tidak dikirim ke server manapun.

### Apakah bisa dipakai di banyak komputer?
Tidak. Satu lisensi untuk satu komputer. Jika butuh lisensi tambahan, hubungi vendor.

### Apakah bisa ganti komputer?
Bisa. Hubungi vendor untuk mendapatkan file `.lic` baru sesuai Device ID komputer baru. Biasanya ada biaya transfer lisensi.

### Apakah ada biaya bulanan?
Tidak. Lisensi lifetime, bayar sekali pakai selamanya.

### Apakah bisa custom fitur?
Bisa. Hubungi vendor untuk diskusi kebutuhan custom.

### Apakah bisa integrasi dengan e-commerce?
Saat ini belum. Fitur ini dalam roadmap pengembangan.

### Apakah bisa multi-cabang?
Saat ini belum. Setiap cabang butuh lisensi terpisah dan data tidak tersinkron antar cabang.

---

**Terima kasih sudah memilih SaleSwiftDesk!**

Semoga aplikasi ini membantu operasional toko Anda lebih efisien. 🚀
