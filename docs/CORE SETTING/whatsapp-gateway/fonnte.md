---
title: Fonnte
deprecated: false
hidden: false
icon: fad fa-1
metadata:
  robots: index
---
Gunakan provider ini jika akun WhatsApp Gateway Anda menggunakan layanan Fonnte.


<Image src="https://files.readme.io/e633355c982063f1176f1c2c21dafcbbdb89366590b3f08a295ca081a2f5340e-image.png" align="center" framed={true} />


Klik Menu Device

<br />


<Image src="https://files.readme.io/c15ae0f27f432e026793a0710e91beb405d213dec059737baa48e15af28d8b1a-image.png" align="center" framed={true} />


Kemudian Pilih Button Add Device

<br />


<Image src="https://files.readme.io/434655c8ea902875b582e6d5aec962d27b72f638723e46ee9927c210a113d95f-image.png" align="center" framed={true} />


Isikan data Sender WhatsaApp anda dan dipastikan tidak menggunakan WhatsApp Utama (Wa Perusahaan), Direkomendasikan menggunakan WhatsApp Terpisah

<br />


<Image src="https://files.readme.io/0a1d0514f2e300dc58761d4db7e21df07f1ed0e326d7309e7f2150bb23d716ad-image.png" align="center" framed={true} />


Klik Tombol Connect dan setelah itu scan QR yang sudah tampil

<br />


<Image src="https://files.readme.io/752bc3a761fb60e91534e59e1f3f749e0fe1f27aa59e9504f454dca7c1cd8262-image.png" align="center" framed={true} />


Setelah Berhasil Connect Klik tombol token maka otomatis Tercopy untuk data token Fonnte nya

<br />


<Image src="https://files.readme.io/876bffc5199ae3573a9968948586b5c0c244dafafde0ab8a4cfd4581d20f8e4a-image.png" align="center" framed={true} />


Masukkan Token yang dari Fonnte ke dalam kolom Billing&#x20;

<br />

Field yang perlu diisi:

1. Base URL: [https://api.fonnte.com/send](https://api.fonnte.com/send) (otomatis)
2. Token: masukkan token Fonnte

Token Fonnte dapat diambil dari menu device pada dashboard Fonnte. Pada dokumentasinya, token dikirim melalui header Authorization tanpa tambahan Bearer. Fonnte juga mendukung lebih dari satu token yang dipisahkan dengan koma, misalnya token1,token2.

Di aplikasi ini, token dapat diisi lebih dari satu dengan koma atau baris baru. Token pertama akan digunakan sebagai fallback utama.
