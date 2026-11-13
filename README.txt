ALTHEA NINJABRAIN BOT - Android starter project (v1.1)

Fitur:
- Aplikasi Android native Kotlin.
- Floating overlay di atas Minecraft.
- Jendela dapat dipindahkan melalui bar judul.
- Tombol MINIMIZE / EXPAND dan TUTUP.
- Input posisi X, posisi Z, dan yaw Minecraft.
- Simpan pengamatan pertama, lalu hitung triangulasi dari pengamatan kedua.
- Menampilkan perkiraan koordinat Stronghold.

Build APK:
1. Ekstrak ZIP.
2. Buka folder AltheaNinjaBot di Android Studio.
3. Tunggu Gradle Sync selesai (internet diperlukan saat pertama kali).
4. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK debug: app/build/outputs/apk/debug/app-debug.apk.
6. Install APK, buka aplikasi, izinkan "Display over other apps", lalu tampilkan jendela.
7. Buka Minecraft. Geser jendela melalui bar judul.

PENTING:
- ZIP ini adalah source project Android Studio, bukan APK siap instal.
- Kalkulator memakai yaw Minecraft: 0 = selatan (+Z), -90 = timur (+X), 90 = barat (-X), ±180 = utara (-Z).
- Perhitungan saat ini adalah triangulasi garis dasar dari dua arah lemparan. Belum setara Ninjabrain Bot penuh: belum ada model ketidakpastian sudut/pixel, estimasi error, kalibrasi screenshot, atau prediksi stronghold ring.
- Jika overlay tidak muncul, periksa izin "Display over other apps" pada pengaturan Android.
