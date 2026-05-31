---
title: Spesifikasi & Persyaratan
deprecated: false
hidden: false
icon: fad fa-cloud-exclamation
metadata:
  robots: index
---
Agar Billing Manager dapat berkomunikasi dengan jaringan Anda secara sempurna, terdapat beberapa spesifikasi standar yang harus dipenuhi oleh infrastruktur jaringan Anda.

Syarat Wajib Router Mikrotik:

1. Billing Manager menggunakan protokol API modern yang dioptimalkan untuk Mikrotik RouterOS versi 7 (v7.x).&#x20;
2. Pastikan router Anda sudah di-upgrade ke versi terbaru untuk menjamin kelancaran komunikasi data dan menghindari error timeout.
3. Konektivitas Jaringan: Router Mikrotik Anda harus dapat diakses dari luar jaringan (Internet) oleh server Billing Manager. Anda bisa menggunakan IP Publik Statis atau layanan VPN Remote (seperti L2TP/SSTP/Wireguard) agar server billing dapat menjangkau router Anda.
4. Port API Aktif: Layanan API atau API-SSL pada Mikrotik harus dalam keadaan aktif (di menu IP > Services).

<br />

Syarat Operasional Lainnya:

ℹ️ Nomor WhatsApp aktif yang didedikasikan khusus untuk bot notifikasi ke pelanggan.

ℹ️ Akun Payment Gateway (opsional) jika Anda ingin menerima pembayaran otomatis melalui Virtual Account, E-Wallet, atau QRIS.