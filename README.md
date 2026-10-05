# SkillUp — Landing Page Startup Edukasi

Proyek Tugas 1 Pemrograman Web. Website satu halaman untuk simulasi startup edukasi digital.

## Struktur direktori

```text
pemweb-tugas1-[NIM]/
├── index.html
├── css/
│   └── style.css
├── assets/
│   ├── images/
│   └── icons/
│       └── arrow-up-right.svg
└── README.md
```

Folder `assets/images/` disiapkan untuk gambar tambahan. Desain utama saat ini menggunakan ilustrasi CSS sehingga tidak membutuhkan gambar eksternal.

## Fitur
- HTML5 semantik: `header`, `nav`, `main`, `section`, `article`, `aside` (tidak diperlukan untuk konten ini), dan `footer`.
- CSS murni tanpa Bootstrap, Tailwind, atau framework.
- Layout Flexbox dan CSS Grid.
- Pendekatan mobile-first.
- Breakpoint tablet `768px` dan desktop `1024px`.
- Skip link, landmark navigasi berlabel, heading berurutan, teks tautan deskriptif, fokus keyboard, dan dukungan `prefers-reduced-motion`.
- Bagian hero, fitur, kelas, testimoni, harga, CTA, dan footer.

## Cara menjalankan
1. Ekstrak folder proyek.
2. Buka `index.html` di browser.
3. Untuk pengembangan, gunakan editor seperti Visual Studio Code.
4. Ganti nama folder menjadi `pemweb-tugas1-[NIM]` sesuai instruksi dosen.

## Pengujian yang disarankan
- HTML: https://validator.w3.org/nu/
- CSS: https://jigsaw.w3.org/css-validator/
- Lighthouse: Chrome DevTools → Lighthouse → Accessibility (target tugas: minimal 90).
- Uji lebar layar sekitar 375px, 786px, dan 1280px.
- Pastikan tidak ada horizontal overflow.

## Contoh urutan Git commit
Sesuaikan pesan commit dengan perubahan yang benar-benar dilakukan.

```bash
git init
git add index.html README.md
git commit -m "feat(html): buat struktur semantik landing page"

git add css/style.css
git commit -m "style(css): tambahkan reset, warna, dan tipografi"

git add index.html css/style.css
git commit -m "feat(layout): buat kartu fitur dan kelas dengan grid"

git add css/style.css
git commit -m "responsive(css): atur breakpoint tablet dan desktop"
```

## Publikasi GitHub
Buat repository publik bernama `pemweb-tugas1-[NIM]`, lalu ikuti petunjuk GitHub untuk menghubungkan repository lokal dan mengaktifkan GitHub Pages. Jangan lupa ganti `[NIM]` dan username GitHub dengan milik sendiri.
