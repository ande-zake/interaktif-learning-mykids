Saya sedang membangun web pembelajaran interaktif anak SD (umur 9 tahun) berbasis GitHub Pages (pure Vanilla HTML/CSS/JS tanpa build tools).

Konteks Proyek:
- Struktur File:
  ├── index.html (Dashboard utama bertema 'Taman Belajar Petualang', kids-friendly, card grid per kategori)
  └── math/persamaan-simple.html (Game aljabar persamaan matematika dasar bertema Demon Slayer)
- Aturan Teknis Penting:
  1. No external frameworks (harus 100% Native HTML, inline/internal CSS & Vanilla JS).
  2. iPad / Touchscreen Ready: Wajib mendukung event touch (`touchstart`, `touchend`) dan `touch-action: none` agar tidak bentrok dengan scroll/zoom Safari.
  3. Single-file architecture per modul agar mudah di-host langsung via GitHub Pages.

Tugas Saya Selanjutnya:
[Tulis tugas Anda di sini, contoh: "Buatkan halaman baru di folder math/pecahan-pizza.html dengan konsep drag slice pizza ke piring"]