# Release Notes — Lumio v1.10.2

**Build:** 24
**Commit:** b72d139
**Tanggal:** 2026-05-28 12:51 UTC

## Perubahan

Lumio v1.10.2 (Build 24) — Staging Release  Fitur Baru & Penyempurnaan: - Integrasi Metode QRIS & Virtual Account (VA): Menambahkan pemilih metode pembayaran secara inline saat transaksi checkout untuk kemudahan pembayaran. - Registrasi Lebih Cepat: Menyederhanaan pendaftaran dengan meniadakan alur verifikasi manual via WhatsApp Admin di tahap awal registrasi.  Perbaikan Bug & Optimalisasi: - Perbaikan Visualisasi Data Owner: Menambahkan provider KPI dashboard yang sempat hilang (dashboard_kpi_provider.dart) agar data bisnis pemilik toko terisi akurat. - Pembenahan Navigasi Login: Halaman LoginScreen kini otomatis di-pop setelah sukses masuk agar sistem AppBootstrap langsung mengarahkan rute secara benar. - Penyempurnaan UI: Melakukan penyesuaian tata letak (UI) pada Dashboard Owner serta optimalisasi stabilitas POS providers.  Infrastruktur & Staging: - Migrasi Konektivitas API & Web: Mengarahkan koneksi aplikasi ke domain staging permanen yang baru dideploy di Easypanel (https://api-lumio.wahyukurnia.com dan https://lumio.wahyukurnia.com).
