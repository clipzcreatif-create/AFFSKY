# AFFSKY Studio & Rental

Static landing page untuk **AffSky Studio & Rental** di domain `affsky.web.id`.

## Isi Website

- Hero / lobby
- Layanan Creative Studio
- Layanan Drone Rental
- Portfolio video Google Drive
- Pricelist rental drone
- FAQ
- Kontak WhatsApp, Instagram, dan Maps

## Teknologi

- HTML statis
- Tailwind CSS via CDN
- Google Fonts Inter
- PWA basic: `manifest.webmanifest` + `sw.js`
- Deploy: GitHub Pages + custom domain dari `CNAME`

## File Penting

```text
index.html              # halaman utama
CNAME                   # custom domain GitHub Pages
manifest.webmanifest    # konfigurasi PWA
sw.js                   # service worker cache basic
icons/                  # ikon PWA SVG
```

## Cara Edit Cepat

1. Edit `index.html`.
2. Cek link WhatsApp, harga, dan embed portfolio.
3. Commit dan push ke branch `main` atau branch PR.
4. GitHub Pages akan update otomatis.

## Catatan

- Jangan hapus `CNAME` kalau domain `affsky.web.id` masih dipakai.
- Jangan taruh password, token, atau akses hosting di repo.
- Kalau pindah dari GitHub Pages ke hosting/FTP, backup dulu file live.
