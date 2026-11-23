# Pindai MTs

Pembungkus ringan layanan pindai madrasah (printer-mts.local:8080).

- Windows 64-bit, portable (tanpa installer). Unduh exe, jalankan.
- Aplikasi hanya menampilkan halaman pindai. Tidak ada data tersimpan.
- Untuk mencetak dari Windows, tambah printer jaringan dari Pengaturan
  memakai alamat http://printer-mts.local:631/printers/L3210
  (cadangan memakai alamat IP bila nama tidak ketemu).
- Server cetak dan pindai tetap berjalan di perangkat STB sekolah.

## Rilis

Buat tag lalu dorong:

git tag v1.0.0
/workspace/github/push.sh printer-mts v1.0.0

GitHub Actions membangun portable Windows otomatis dan menempelkannya ke halaman Rilis saat tag v* didorong.
