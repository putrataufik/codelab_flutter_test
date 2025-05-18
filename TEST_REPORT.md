
#  Flutter App Testing - Tugas Praktikum

Repositori ini merupakan hasil pengerjaan tugas **pengujian aplikasi Flutter** berdasarkan panduan Google Codelab: [How to test a Flutter app](https://codelabs.developers.google.com/codelabs/flutter-app-testing).

---

## Jenis Pengujian yang Dilakukan

- **Unit Test** — Memvalidasi logika bisnis `Favorites` (add/remove, notifyListeners).
- **Widget Test** — Menguji tampilan dan interaksi UI di halaman Home dan Favorites.
- **Integration Test** — Menjalankan simulasi end-to-end: tambah → navigasi → hapus favorit.
- **Performance Test** — Mengukur performa scroll aplikasi menggunakan `flutter drive`.

---

##  Cara Menjalankan Pengujian

###  Jalankan semua unit & widget test
- flutter test

### Jalankan widget test tertentu
- flutter test test/home_test.dart

### Jalankan integration test
- flutter test integration_test/app_test.dart
- Saat dijalankan, pilih device seperti:
[1]: Windows (windows) → pilih angka 1

### Jalankan performance test
- flutter drive --driver=test_driver/perf_driver.dart --target=integration_test/perf_test.dart --profile --no-dds
- Saat dijalankan, pilih device seperti:
[1]: Windows (windows) → pilih angka 1

#### Tantangan
Sebenarnya ketika mengikuti insturksi dari codelab tidak ada error yang berarti. 
instruksi dari codelab sangat mudah di mengerti sih, dijelaskan cukup detail bagaimana cara untuk membuat unit testing, widget testing, bahkan integratioin test. dan sangat menarik ketika melihat semua testing yang dibuat seperti bergerak sendiri secara otomatis.

### lINK Gdrive

