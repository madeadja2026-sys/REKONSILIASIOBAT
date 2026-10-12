# Kartu Stok Obat — Puskesmas Ngalupolo

PWA ringan untuk daftar item obat/BMHP, mutasi, stok opname fisik, pemantauan ED, dan ekspor laporan.

## Publikasi GitHub Pages
1. Buka **Settings → Pages** pada repository.
2. Pada **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch **main** dan folder **/(root)** lalu tekan **Save**.
4. Tunggu proses publikasi; URL biasanya `https://madeadja2026-sys.github.io/REKONSILIASIOBAT/`.
5. Buka URL di Chrome Android, menu ⋮ → **Tambahkan ke layar utama** / **Instal aplikasi**.

## Penting
- Data saat ini disimpan di localStorage pada browser/perangkat yang digunakan. Data tidak otomatis tersinkron ke HP lain dan dapat hilang jika data situs dibersihkan.
- Ekspor CSV secara rutin untuk cadangan. CSV bisa dibuka di Excel/Google Sheets; PDF melalui Cetak → Simpan sebagai PDF.
- PWA dapat membuka aplikasi yang sudah pernah dimuat saat offline, tetapi tidak menggantikan pencadangan data.
- Ini adalah versi awal operasional lokal; belum ada login, hak akses, database bersama, audit trail, atau sinkronisasi multi-perangkat.
- Jangan gunakan data pasien atau data rahasia di repository publik.
