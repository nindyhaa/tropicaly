# Tropical Fresh 🌴🥭

Website katalog & pemesanan minuman tropical yang siap dipasang di **GitHub Pages**.

## Cara upload ke GitHub Pages

1. Buat repository baru, misalnya `tropical-fresh`.
2. Buka repository tersebut.
3. Klik **Add file → Upload files**.
4. **Penting:** upload file `index.html`, `styles.css`, dan `app.js` langsung ke halaman utama repository. Jangan upload folder `tropical-fresh-github-v2` sebagai satu folder.
5. Commit changes.
6. Buka **Settings → Pages**.
7. Pada **Build and deployment**, pilih **Deploy from a branch**.
8. Pilih branch `main` dan folder `/ (root)`, lalu **Save**.
9. Tunggu beberapa saat dan buka alamat GitHub Pages yang diberikan GitHub.

## Struktur yang benar

```text
repository/
├── index.html
├── styles.css
├── app.js
└── README.md
```

## Catatan

Aplikasi ini adalah prototype front-end. Data keranjang disimpan di browser menggunakan localStorage. Foto produk memakai URL gambar eksternal sehingga koneksi internet diperlukan agar foto tampil.
