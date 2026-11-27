# DigiSkola — Struktur Proyek

```
digiskola/
├── index.html              ← Halaman utama (landing page)
│
├── css/
│   └── main.css            ← Semua styling global (variabel, layout, komponen)
│
├── js/
│   ├── navbar.js           ← Sticky navbar, hamburger menu, mobile menu
│   ├── slider.js           ← Image slider (autoplay, dots, swipe, prev/next)
│   └── animations.js       ← Scroll animations (fade-up), counter stats
│
├── pages/
│   └── (halaman tambahan di sini, misal: about.html, layanan.html)
│
└── assets/
    └── img/
        └── (simpan gambar lokal di sini, misal: profile.jpg, myspensix-1.jpg)
```

## Cara Pakai

1. Buka `index.html` di browser (bisa langsung klik dua kali atau pakai Live Server di VS Code).
2. Untuk menambah halaman baru, buat file `.html` di folder `pages/` dan tambahkan link CSS + JS yang sama.
3. Ganti gambar placeholder dari Unsplash dengan foto nyata — simpan di `assets/img/`.

## Teknologi

- **HTML5** semantik + aksesibilitas (ARIA)
- **CSS3** — variabel CSS, grid, flexbox, animasi murni CSS
- **Vanilla JS** modular — tidak perlu framework
- Font: **Sora** (heading) + **DM Sans** (body) dari Google Fonts

## Catatan Developer

- Tidak ada ketergantungan eksternal (zero npm, zero build step)
- Bisa langsung di-deploy ke Netlify / Vercel / GitHub Pages
- Mobile-first responsive di semua breakpoint
