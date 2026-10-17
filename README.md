# Bangjeh Multipost Studio — Unduhan / Downloads

Publikasikan satu video ke TikTok, YouTube Shorts, Instagram Reels, Facebook, Pinterest, dan Shopee Video dari komputer Anda sendiri (Windows, macOS, Linux).

**➡ [Unduh versi terbaru / Download the latest version](../../releases/latest)**

**📘 [Panduan penggunaan (PDF, Bahasa Indonesia)](../../releases/latest/download/Panduan-Bangjeh-Multipost-Studio.pdf)**: langkah demi langkah dengan gambar.

## Bahasa Indonesia

### Sebelum memasang
- Pasang **Google Chrome** (https://www.google.com/chrome). Aplikasi memakai Chrome untuk membuka setiap platform.
- Siapkan **kode aktivasi** dari penjual Anda.

### Windows 10/11 (64-bit)
1. Unduh `Bangjeh-Multipost-Studio-<versi>-win-x64.exe`.
2. Jalankan file tersebut. Karena installer belum ditandatangani secara digital, Windows mungkin menampilkan **"Windows protected your PC"**. Pilih **More info → Run anyway**.
3. Ikuti langkah pemasangan (tidak perlu hak administrator). Aplikasi muncul di menu Start dan di desktop.

### Linux (64-bit)
- **Ubuntu / Debian:** unduh file `.deb`, lalu jalankan `sudo apt install ./Bangjeh-Multipost-Studio-<versi>-linux-amd64.deb`. Aplikasi muncul di menu aplikasi.
- **Distribusi lain:** unduh file `.AppImage`, jalankan `chmod +x Bangjeh-Multipost-Studio-*.AppImage`, lalu buka file tersebut. Di Ubuntu 22.04 atau lebih baru, mungkin perlu `sudo apt install libfuse2`.

### macOS (12 Monterey atau lebih baru)
1. **Cek jenis Mac Anda:** menu Apple  → **About This Mac / Tentang Mac Ini**.
   - Tertulis **"Chip Apple M1/M2/M3/M4"** → unduh `…-mac-arm64.dmg`.
   - Tertulis **"Processor … Intel"** → unduh `…-mac-x64.dmg`.
2. Buka file `.dmg`, lalu **seret ikon Bangjeh Multipost Studio ke folder Applications**.
3. Buka aplikasi dari folder Applications. Karena aplikasi belum ditandatangani oleh Apple, macOS akan menolak saat pertama kali: klik **Done / Selesai** (jangan "Move to Trash").
4. Buka **System Settings → Privacy & Security** (Pengaturan Sistem → Privasi & Keamanan), gulir ke bawah, lalu klik **Open Anyway / Tetap Buka** di samping pesan tentang Bangjeh Multipost Studio. Masukkan kata sandi Mac Anda, lalu klik **Open / Buka**. Ini hanya perlu sekali.
5. Jika muncul pertanyaan akses **Keychain** ("… Safe Storage"), pilih **Always Allow / Selalu Izinkan**. Ini untuk menyimpan lisensi Anda dengan aman.

Jika macOS menyebut aplikasi **"rusak" (damaged)**, buka aplikasi **Terminal** dan jalankan:
`xattr -dr com.apple.quarantine "/Applications/Bangjeh Multipost Studio.app"`
lalu buka aplikasi lagi.

### Setelah memasang
Buka aplikasi, masukkan kode aktivasi di halaman **Lisensi**, lalu hubungkan platform Anda di **Hubungkan Platform**. Bahasa dapat diganti ke English di bagian bawah menu samping.

### Memeriksa unduhan (opsional)
Setiap rilis menyertakan `SHA256SUMS`. Di Linux: `sha256sum -c SHA256SUMS --ignore-missing`. Di Windows (PowerShell): `Get-FileHash <file> -Algorithm SHA256`.

## English

- **Requirements:** Windows 10/11, Linux (64-bit) or macOS 12+; Google Chrome; and an activation code from your seller.
- **Windows 10/11 (64-bit):** run the `.exe`. The installer is not code-signed yet, so Windows may say "Windows protected your PC": choose **More info → Run anyway**. No administrator rights needed.
- **Linux (64-bit):** `sudo apt install ./…linux-amd64.deb` on Ubuntu/Debian, or make the `.AppImage` executable and run it (Ubuntu 22.04+ may need `libfuse2`).
- **macOS 12+:** Apple menu → About This Mac: "Apple M…" chip → `…-mac-arm64.dmg`, Intel → `…-mac-x64.dmg`. Open the DMG and drag the app to Applications. The app is not yet signed by Apple, so the first open is blocked: click **Done**, then System Settings → Privacy & Security → **Open Anyway** (once). Allow the Keychain request ("Safe Storage") with **Always Allow**. If macOS says the app is "damaged", run `xattr -dr com.apple.quarantine "/Applications/Bangjeh Multipost Studio.app"` in Terminal.
- **After installing:** enter your activation code on the License page (the app starts in Bahasa Indonesia; switch to English at the bottom of the sidebar).
- **Verify downloads** against `SHA256SUMS`.

Updates are not automatic yet: download new versions from this page. Your license, platform logins and history are kept when you install a newer version over an older one.
