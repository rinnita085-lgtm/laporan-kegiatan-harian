# Laporan Kegiatan Harian

Website single-page untuk membuat **Laporan Kegiatan Harian** (Sekolah Rakyat Terintegrasi).

## Fitur
- Form laporan harian dengan multi kegiatan & RHK
- Upload foto dokumentasi & file pendukung
- Tanda Tangan Digital + QR Code (otomatis dari Nama & NIP)
- Pratinjau real-time
- Export ke **PDF** dan **Word (.docx)**
- File PDF pendukung otomatis digabung saat export PDF
- Data tersimpan di localStorage
- Tema biru, siap dipakai offline maupun online

## Cara Menjalankan Lokal
1. Download / clone repository ini
2. Buka `index.html` dengan Live Server (VS Code) atau double-click file-nya
3. Isi data → QR Code otomatis muncul
4. Download PDF atau Word

## Publish ke GitHub Pages
1. Buat repository baru di GitHub
2. Upload file `index.html` (dan `README.md` jika mau)
3. Buka **Settings → Pages**
4. Source: pilih branch `main` dan folder `/ (root)`
5. Tunggu beberapa saat, lalu akses link:
   `https://username.github.io/nama-repo`

## Catatan
- Membutuhkan koneksi internet saat pertama dibuka (karena library dimuat dari CDN)
- Setelah terbuka, data dan export bisa digunakan selama browser tidak ditutup
- QR Code berisi teks:
  ```
  Nama: ...
  NIP: ...
  Status: Dokumen ini sah dan terverifikasi
  ```

---
Created by Agung Pradana
