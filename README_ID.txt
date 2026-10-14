LPB BARCODE OFFLINE - PROJECT ANDROID

Fitur yang sudah dibuat di source:
- Import file Excel .xlsx LPB dari penyimpanan HP.
- Membaca kolom PLU, BARCODE, NAMA PRODUK, dan QTY PO dari sheet pertama yang berisi header tersebut.
- Scan barcode dengan kamera (ZXing).
- Qty Actual diinput manual (opsi A).
- Simpan data lokal di HP.
- Export Excel .xlsx yang hanya berisi item selisih (kurang/lebih), dengan kolom PLU, BARCODE, NAMA PRODUK, QTY PO, QTY ACTUAL, SELISIH, STATUS.

CARA MEMBUAT APK:
1. Di komputer Windows/Mac, install Android Studio terbaru.
2. Extract ZIP ini.
3. Buka Android Studio > Open > pilih folder LPBBarcodeOffline hasil extract.
4. Tunggu Gradle Sync selesai; koneksi internet dibutuhkan sekali untuk mengunduh dependency build.
5. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Setelah selesai, klik Locate pada notifikasi build. File biasanya ada di app/build/outputs/apk/debug/app-debug.apk.
7. Kirim APK ke HP Xiaomi, buka file APK, lalu izinkan instalasi dari sumber tersebut jika diminta.
8. Buka aplikasi, import Excel LPB, lalu scan dan cek barang. Setelah aplikasi terpasang dan file LPB diimpor, proses pemeriksaan bisa offline.

CATATAN:
- Ini source project awal; belum dikompilasi atau diuji di perangkat Android pada lingkungan pembuatan ini.
- Barcode diperlakukan sebagai teks agar angka tidak dibulatkan.
- Format Excel sumber harus .xlsx dan punya header PLU, BARCODE, NAMA PRODUK, QTY PO.
