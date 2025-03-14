---
description: >-
  Monster Juara adalah monster yang dipanggil secara dinamis oleh server setelah
  kondisi tertentu terpenuhi.
---

# 🏆 Monster Juara

<figure><img src="../.gitbook/assets/mmmm.gif" alt=""><figcaption><p><mark style="color:red;"><strong>Monster Juara dalam Aksi</strong></mark></p></figcaption></figure>

## **Karakteristik**

* Ketika **Juara** muncul, itu diumumkan kepada semua pemain di peta.
* **Juara memberikan 30 kali lebih banyak pengalaman dan memiliki tingkat drop item 10 kali lipat.**

***

## **Rumus Pemanggilan**

Perhitungan yang diterapkan saat membunuh monster untuk menentukan apakah Juara dipanggil adalah sebagai berikut:

```
mathematicaCopiarEditarSummon Chance += [(Monster Level / 100) * Number of Players on the Map]%
```

### **Contoh:**

\
Jika Anda berada dalam kelompok dengan 5 teman di peta dan membunuh monster level 25 **25 kali**, maka:

Peluang monster ini untuk menjadi Juara adalah **1,25%**.

Jika pemanggilan tidak terjadi, peluang berikutnya akan meningkat menjadi **2,50%**, dan seterusnya.

***

## **Tipe Juara*** Jenis Champion yang dipanggil adalah acak. Tabel di bawah ini menunjukkan karakteristik masing-masing monster.

<table><thead><tr><th width="102">Tipe</th><th width="92">Damage</th><th width="151">Kesehatan</th><th width="147">Resist</th><th>Fitur</th></tr></thead><tbody><tr><td><mark style="background-color:green;">Ventus</mark></td><td>+7%</td><td>30</td><td>Angin = 90%</td><td>Nome</td></tr><tr><td><mark style="background-color:yellow;">Solid</mark></td><td>+7%</td><td>700</td><td>Bumi = 90%</td><td>1% peluang untuk menghancurkan senjata</td></tr><tr><td><mark style="background-color:purple;">Necro</mark></td><td>+7%</td><td>1500</td><td>Undead = 90%</td><td>Memulihkan 3% HP mob</td></tr><tr><td><mark style="background-color:orange;">Fairer</mark></td><td>+7%</td><td>Tidak terputus</td><td>Api = 90%</td><td>Memiliki [Endure] aktif</td></tr><tr><td><mark style="background-color:blue;">Elusive</mark></td><td>+7%</td><td>Tidak terputus</td><td>Nome</td><td>Tidak menerima kerusakan fisik</td></tr></tbody></table>## **Spesifikasi Sistem**

<table><thead><tr><th width="169">Spesifikasi</th><th>Jenis</th></tr></thead><tbody><tr><td>Link</td><td>Tidak ada</td></tr><tr><td>Restriksi</td><td>Tidak berfungsi dengan <strong>monster epik</strong>, dan hanya satu <strong>Monster Juara</strong> yang dapat dipanggil pada satu waktu sementara yang lain masih hidup di peta yang sama.</td></tr></tbody></table>