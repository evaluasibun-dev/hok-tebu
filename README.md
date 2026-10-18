# Sistem HOK Tebu 2026

Aplikasi web untuk pengisian dan pemantauan Hari Orang Kerja (HOK) kegiatan **Perluasan Tanaman Tebu** dan **Bongkar Ratoon**, Direktorat Jenderal Perkebunan.

- Kabupaten mengisi data poktan, pekerja dan kehadiran harian, mengunggah foto dan dokumen, lalu mencetak form F00–F11 dan F13.
- Setiap isian divalidasi langsung: NIK 16 digit, urutan tanggal dokumen, HOK maksimal sebesar target, dan pekerja yang tercatat hadir di dua poktan pada hari yang sama (hari ganda) di seluruh kabupaten.
- Provinsi dan pusat memantau progres, kelengkapan dokumen, temuan dan potensi kelebihan bayar.

Repositori ini **hanya berisi tampilan**. Data, berkas dan login tersimpan di Google Sheets/Drive dan Apps Script milik Tim Kerja Evaluasi dan Pelaporan, dan tidak ada di sini.

Coba tanpa server: buka halaman dengan tambahan `?demo=1` di alamat. Mode ini memakai data contoh fiktif yang hanya tersimpan di browser.

Pustaka pihak ketiga: [SheetJS](https://sheetjs.com) 0.18.5 (Apache-2.0), dimuat dari cdnjs untuk impor dan unduh Excel.
