# Evidence Folder - UTS Praktikum PPL Kelompok 7 (Katalog)

Folder ini digunakan untuk menyimpan seluruh bukti pengujian aplikasi CilacapTools (AUT).

## Struktur Subfolder:
- `screenshots/` : Tangkapan layar penuh (Fullscreen) untuk temuan bug atau komparasi layout.
- `recordings/`  : Rekaman layar (video) untuk bug yang intermiten atau membutuhkan alur aksi berurutan.
- `logs/`        : Salinan console log DevTools jika ditemukan error JavaScript / network 500.
- `session-notes/`: Dokumen Session Notes pengujian SBTM dari R3.

## Aturan Penamaan Berkas:
Pola: `BUG-XXX_judul-singkat.[ekstensi]`  
Contoh:
- `BUG-001_search-filter-error.png`
- `BUG-002_slider-price-jump.webm`
- `BUG-003_uncaught-typeerror-console.log`
