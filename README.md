# Ruang Cemerlang — Website Astronomi Club

Versi awal landing page untuk menyimpan materi, latihan, simulasi, tautan, dan arsip Astronomi Club.

## Cara memakai

1. Buka `index.html` langsung di browser.
2. Untuk menerbitkan secara gratis, unggah folder ini ke GitHub Pages, Netlify, atau Vercel.
3. Materi Gravitasi sudah disertakan di folder `materi/` dan langsung terhubung dari halaman utama.
4. Saat menambahkan file baru, simpan file di dalam folder website atau gunakan tautan Google Drive.
5. Masukkan URL yang sama pada atribut `href` dan `data-link`.

Contoh:

```html
<a class="resource-link" href="materi/nama-file.html" target="_blank" rel="noopener">Buka materi</a>
<button class="icon-link copy-link" data-link="materi/nama-file.html">...</button>
```

## Menambah kartu materi

Duplikasikan salah satu elemen `<article class="resource-card">...</article>` di bagian `resourceGrid`, lalu ubah:

- `data-category`: materi / latihan / simulasi / arsip
- `data-search`: kata kunci pencarian
- judul dan deskripsi
- tag
- tautan file

Semua fitur memakai HTML, CSS, dan JavaScript murni tanpa pustaka eksternal.
