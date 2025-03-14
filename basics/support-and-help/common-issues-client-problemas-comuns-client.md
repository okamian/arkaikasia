---
description: >-
  Jika Anda tidak menemukan solusi di bawah ini, silakan hubungi tim dukungan kami di
  Discord atau WhatsApp.
---

# 🪛 Masalah Umum (Klien)

## Arkaik.exe terbuka, tetapi saat mengklik "Mainkan," tidak ada yang terjadi, dan itu menutup

**Penyebab:**

* **Antivirus** atau **perlindungan eksploitasi** Anda mungkin memblokir file `.exe` klien.

**Solusi:**\
Pergi ke:\
➡ **Keamanan Windows** > **Kontrol Aplikasi & Browser** > **Pengaturan Perlindungan Eksploitasi** > **Pengaturan Program (Tab Atas)** > **(+) Tambahkan Program untuk Kustomisasi**

Ketik `Client.exe` dan aktifkan semua proses. (Periksa semua kotak pilihan; beberapa mungkin diaktifkan secara default—nonaktifkan juga jika perlu.)\


<figure><img src="../../.gitbook/assets/image (149).png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (150).png" alt="" width="410"><figcaption></figcaption></figure>

## **Arkaik.exe tidak terbuka, tidak ada di pengelola tugas, dan tidak ada kesalahan yang muncul**

**Penyebab:*** Antivirus atau perlindungan eksploitasi Anda mungkin memblokir file `exe` dari **Arkaik**.

**Solusi:**\
➡ **Keamanan Windows** > **Kontrol Aplikasi & Browser** > **Pengaturan Perlindungan Eksploitasi** > **Pengaturan Program (Tab Atas)** > **(+) Tambahkan Program untuk Kustomisasi**

Ketik **Arkaik.exe** dan aktifkan semua proses. (Centang semua kotak pilihan; beberapa mungkin sudah diaktifkan secara default—nonaktifkan juga jika perlu.)

📌 **Gambar:** Prosedur yang sama seperti di atas!

## **Kesalahan: Tidak dapat menemukan File dengan karakter khusus "????"**

**Masalah:**

* Saat menjalankan `Client.exe`, setelah memilih karakter, permainan menampilkan karakter khusus sebagai `???`, menyebabkan permainan **crash**.

<figure><img src="../../.gitbook/assets/image (151).png" alt=""><figcaption></figcaption></figure>

**Penyebab:**

* Paket bahasa **gagal mengonversi encoding UTF-8** untuk karakter **Korea (Eropa Barat 1252)**.

**Solusi:**\
➡ **Panel Kontrol** > **Ubah format tanggal, waktu, atau angka** > **Administratif (Tab Atas)** > **Ubah lokal sistem**

🔹 **Hapus centang** pada kotak **UNICODE UTF-8** jika diaktifkan, restart, dan uji permainan.

<figure><img src="../../.gitbook/assets/image (152).png" alt="" width="329"><figcaption></figcaption></figure>

## **Kesalahan di Client.exe: "Tidak dapat menginisialisasi d3d ATAU file grf memiliki masalah" atau Layar Putih**

<figure><img src="../../.gitbook/assets/Cannot_init_d3d_or_grf_file_has_problem.png" alt="" width="188"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/800px-Telabranca.png" alt="" width="375"><figcaption><p>Tela Putih</p></figcaption></figure>

**Masalah:**

* Ketika mengklik **Client.exe**, tidak ada yang terjadi, layar putih muncul, dan permainan langsung ditutup, bahkan setelah memilih **kartu grafis** di **RO/OpenSetup.exe**.

**Masalah 2:*** Ketika mengklik **Play** melalui **Arkaik.exe** atau **Client.exe**, pesan kesalahan **"Tidak dapat menginisialisasi d3d ATAU file grf bermasalah"** muncul (ini adalah kasus yang paling umum).

***

#### **Solusi untuk Masalah 2:**

1. Buka **RO/OpenSetup.exe**
2. Pilih **kartu grafis** Anda
3. Klik **Terapkan**

➡ Jika masalah masih berlanjut, coba **Solusi 1** di bawah ini.

#### **Kemungkinan Penyebab:**

* **Driver kartu grafis** Anda mungkin sudah usang atau tidak dikenali oleh **Ragnarok**.
* Beberapa **laptop RTX 3050** dari **Asus Gaming** memiliki masalah ini.

***

#### **Cara Menguji Masalah Ini:**

1. **Klik kanan** pada **Client.exe**
2. Pilih **"Perbaiki Kompatibilitas"**
3. Klik **"Uji Program"**

Jika game **berjalan tetapi mengalami kesalahan** (_seperti tekstur yang hilang atau visual yang tidak tepat_), lanjutkan ke **solusi berikutnya**.

<figure><img src="../../.gitbook/assets/image (153).png" alt="" width="387"><figcaption></figcaption></figure>

\
**Solusi Tambahan: "Tidak dapat menginisialisasi d3d ATAU file grf bermasalah"**

**Solusi:**1. Buka **Device Manager**
2. Pergi ke **Display Adapters**
3. **Nonaktifkan** **kartu grafis RTX** Anda (atau GPU khusus Anda)
4. Buka **Client.exe** lagi

**Penjelasan:**

* Jika permainan **dibuka dan berfungsi**, itu berarti renderer **Vodoo** sedang digunakan.
* Kartu grafis Anda mungkin **terlalu modern** dan **tidak mendukung versi DirectX yang lebih lama**.

[<mark style="color:purple;">Link do Video Tutorial</mark>](https://www.youtube.com/watch?v=2dStctdLMeE)

<figure><img src="../../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

## **Kesalahan Memuat Modul Arkaik.exe Sebelum Layar Login (Tanggal & Waktu)**

**Masalah:**

* Ketika membuka **Arkaik.exe**, selama proses memuat modul, muncul **kesalahan merah** yang menyatakan:\
  &#xNAN;**"Server gagal untuk mengautentikasi permintaan"**.

<figure><img src="../../.gitbook/assets/image (155).png" alt="" width="563"><figcaption></figcaption></figure>

**Penyebab:**

* Masalah ini umum terjadi di **Windows 11** karena bergantung pada server online untuk menyinkronkan waktu sistem.

**Solusi:**

1. **Pergi ke:*** **Panel Kontrol** > **Tanggal & Waktu** > **Sinkronkan Sekarang**

<figure><img src="../../.gitbook/assets/image (156).png" alt="" width="332"><figcaption></figcaption></figure>

1. Buka **pengaturan Tanggal & Waktu klasik** di Windows.
2. **Sesuaikan secara manual** tanggal dan waktu.
3. Pastikan waktu sesuai dengan menit saat ini dari **Brasilia (Server Waktu Google)**.
4. Juga, aktifkan:
   * **"Ubah Zona Waktu"**
   * **Sinkronisasi Waktu Internet** dengan server yang benar.

**Jika Masalah Berlanjut:**

<figure><img src="../../.gitbook/assets/image (157).png" alt=""><figcaption><p><mark style="color:red;"><strong>Klik pada Waktu Internet</strong></mark></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (158).png" alt=""><figcaption><p><mark style="color:red;"><strong>Ubah Zona Waktu</strong></mark></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (159).png" alt=""><figcaption></figcaption></figure>## **Error: Gagal mendapatkan URL pembaruan (saat membuka arkaik.exe)**

**Masalah:** Saat menjalankan **arkaik.exe**, muncul kesalahan pembaruan: **"Gagal mendapatkan URL pembaruan"**, yang berarti server pembaruan menolak koneksi.

**Solusi:** Unduh **https://1.1.1.1**. Jika masalah tetap ada, **Cloudflare** dapat mengoptimalkan rute terbaik untuk internet Anda.

<figure><img src="../../.gitbook/assets/image (160).png" alt=""><figcaption></figcaption></figure>

## **Layar Kotak Berwarna Saat Menjalankan Client.exe**

<figure><img src="../../.gitbook/assets/800px-Tela_com_quadrados_coloridos_arkaik_online.png" alt="" width="563"><figcaption></figcaption></figure>

**Masalah:**

* Konfigurasi ini dirancang untuk **kartu grafis yang lebih tua**. **GPU RTX** dan **chipset** yang lebih baru mungkin mengalami masalah ini.

**Solusi:**

1. Pergi ke folder tempat Anda menginstal game:
   * **ArkaikOnline/RO/OpenSetup.exe**
   * Atau buka **arkaik.exe** > **Pengaturan** > **ROSETUP Eksternal**2. Cari kotak centang yang bertuliskan **"Aktifkan akselerator perangkat keras"**, **nonaktifkan**, simpan, dan restart permainan.
3. Jika masalah masih berlanjut, kembali ke lokasi yang sama dan:
   * **Tambahkan kartu grafis**
   * **Atur resolusi lebih rendah dari 1366x768**