# Dokumen Arsitektur Website UMKM - Kopi Kita

**Tugas Kelompok Mata Kuliah Arsitektur Website**
- **Anggota Kelompok:**
  1. Zulfikar
  2. Arya

## 1. Pendahuluan & Latar Belakang
"Kopi Kita" adalah UMKM yang bergerak di bidang penjualan minuman kekinian berbasis es kopi dan non-kopi. Website ini dibuat sebagai media promosi digital untuk menjangkau pelanggan muda (mahasiswa dan pekerja) agar dapat mengakses daftar menu, lokasi kedai, serta melakukan pemesanan secara langsung.

## 2. Tujuan Website
- Memperkenalkan identitas merek dan varian produk Kopi Kita.
- Menyediakan daftar menu dan harga yang jelas dan up-to-date.
- Memudahkan proses pemesanan secara langsung melalui integrasi tombol WhatsApp.
- Menampilkan lokasi fisik dan jam operasional kedai.

## 3. Target Pengguna
- Mahasiswa dan pelajar.
- Pekerja kantoran dan masyarakat umum penyuka kopi/minuman dingin.

## 4. Komponen Utama Website & Fungsinya
1. **Header & Navigation Bar**: Navigasi cepat menuju bagian Menu, Tentang Kami, dan Kontak.
2. **Hero Section**: Area promosi utama dengan gambar menarik dan slogan produk.
3. **Daftar Menu (Products)**: Menampilkan gambar, nama minuman, harga, dan deskripsi singkat.
4. **Tentang Kami (About Us)**: Ringkasan profil usaha dan keunggulan produk.
5. **Kontak & Pemesanan (Call to Action)**: Tombol pemesanan via WhatsApp dan info lokasi.
6. **Footer**: Hak cipta dan link sosial media.

## 5. Diagram Arsitektur Website

```mermaid
flowchart TD
    A[Landing Page Website] --> B[Header & Navigasi]
    A --> C[Hero Section / Promo]
    A --> D[Daftar Menu Minuman]
    A --> E[Tentang Kami]
    A --> F[Kontak & Pemesanan]
    A --> G[Footer]

    B --> B1[Menu Navigasi]
    C --> C1[Tombol Pesan Sekarang]
    D --> D1[Gambar Produk & Harga]
    F --> F1[Tombol WhatsApp Direct]

    ## 6. Alur Penggunaan Website (User Workflow)
1. Pengunjung membuka halaman utama (*Landing Page*).
2. Pengunjung melihat promo utama di *Hero Section*.
3. Pengunjung melakukan *scroll* ke bagian *Daftar Menu* untuk memilih minuman.
4. Pengunjung menekan tombol **Pesan via WhatsApp**.S
5. Sistem mengarahkan pengunjung langsung ke obrolan WhatsApp dengan format pesan otomatis.

## 7. Teknologi yang Digunakan
- **HTML5**: Struktur halaman website.
- **CSS3**: Penataan tampilan, tata letak, warna, dan responsivitas.
- **Git & GitHub**: Version control dan repositori penyimpanan kode.
- **GitHub Pages**: Layanan hosting gratis untuk publikasi website.S