# Bedrock Launcher

Aplikasi Android untuk memasang APK Minecraft Bedrock milik sendiri tanpa lewat Play Store, plus mod bawaan.

> **Risk!** Mod bisa ditolak atau memicu ban di server publik. Pakai atas risiko sendiri.

## Fitur

- Impor APK, APKS, dan XAPK dari penyimpanan HP, lalu pasang.
- Impor addon (.mcaddon, .mcpack, .mcworld) langsung ke Minecraft.
- Daftar file terimpor, dengan tombol Pasang dan Hapus.
- Tombol Buka Minecraft.
- Mod bawaan:
  - 6 crosshair: plus, plus gap, dot, circle, x, diamond.
  - Pintasan dan Inventory: klik kanan jam untuk membuka menu pintasan dan cek inventory.

## Cara build (GitHub Actions)

1. Upload isi folder proyek ke repo GitHub, termasuk `.github/workflows/build.yml`.
2. Buka tab **Actions**, pilih **Build APK**, lalu **Run workflow**.
3. Setelah selesai, download artifact `BedrockLauncher-debug` dan install APK-nya.

## Cara pakai

- **Pasang game:** Impor APK/APKS/XAPK > Pasang. Izinkan "pasang aplikasi tidak dikenal" saat diminta.
- **Crosshair:** Impor modnya, lalu aktifkan di Pengaturan > Sumber Daya Global di Minecraft.
- **Pintasan dan Inventory:** Impor addon, aktifkan di world milikmu, lalu klik kanan jam.

## Catatan

- Hanya untuk Minecraft yang dibeli secara legal.
- Memasang versi lebih lama butuh uninstall versi yang terpasang. Backup world dulu.
- Addon Pintasan dan Inventory hanya jalan di world atau server milik sendiri, dan sebagian perintah butuh cheats aktif.
- Versi modul Script API di addon ditebak untuk Minecraft 1.21.x. Kalau addon gagal aktif, sesuaikan versi di `manifest.json`.
