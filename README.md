# Syariah Pusrawi — Pusat Rujukan Syariah Digital

Dashboard Unit Syariah, Jabatan Perundangan & Perkhidmatan Syariah, Hospital Pakar Pusrawi Kuala Lumpur.

## Cara terbit di GitHub Pages

1. Muat naik semua fail dalam folder ini ke repositori GitHub anda (root repo).
2. Buka **Settings → Pages**.
3. Bahagian **Build and deployment**, pilih **Source: Deploy from a branch**.
4. Pilih branch (cth. `main`) dan folder `/ (root)`, kemudian **Save**.
5. Selepas beberapa minit laman akan tersedia di `https://<username>.github.io/<repo>/`.

## Fail

- `index.html` — dashboard lengkap (satu fail, boleh berfungsi luar talian).
- `manifest.webmanifest` — untuk "Add to Home Screen" (PWA).
- `app-icon-192.png`, `app-icon-512.png` — ikon aplikasi.
- `app-icon-180.png` — ikon Apple (iPhone / iPad).

Untuk paparan ikon "Add to Home Screen" berfungsi sepenuhnya, kekalkan `manifest.webmanifest` dan fail ikon di lokasi yang sama dengan `index.html`.
