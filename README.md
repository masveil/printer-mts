# Printer MTs

Pembungkus ringan portal printer-mts.local (layanan cetak dan pindai madrasah).

- Windows 64-bit, portable (tanpa installer). Unduh zip, ekstrak, jalankan.
- Aplikasi hanya menampilkan halaman lokal madrasah. Tidak ada data tersimpan.
- Server cetak dan pindai tetap berjalan di perangkat STB sekolah.

## Rilis

Buat tag lalu dorong:

git tag v1.0.0
/workspace/github/push.sh printer-mts v1.0.0

GitHub Actions membangun portable Windows otomatis dan menempelkannya ke halaman Rilis saat tag v* didorong.
