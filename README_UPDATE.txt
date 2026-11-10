DESA KRONJO KKN 12 - UPDATE STRUKTUR HALAMAN

Struktur:
desa-kronjo-kkn12/
├── index.html
├── css/
│   └── style.css              <- gunakan CSS project kamu yang sekarang
├── js/
│   └── script.js              <- gunakan JS project kamu yang sekarang
├── assets/
│   ├── images/
│   └── logo/
└── pages/
    ├── profil.html
    ├── informasi.html
    ├── potensi.html
    ├── pelayanan.html
    ├── galeri.html
    ├── kkn.html
    ├── anggota.html
    ├── program-kerja.html
    └── pulau-cangkir.html

Perubahan utama:
- Navbar homepage sekarang menuju halaman baru, bukan anchor #.
- Tombol "Selengkapnya" Profil Desa -> pages/profil.html.
- Pulau Cangkir -> pages/pulau-cangkir.html.
- Potensi -> pages/potensi.html dengan anchor masing-masing.
- Informasi -> pages/informasi.html.
- KKN 12 -> pages/kkn.html.
- Galeri -> pages/galeri.html.
- Semua navbar/footer pada halaman dalam folder pages memakai path ../index.html atau link antar-page yang benar.
- Halaman pelayanan.html belum dibuat karena belum ada isi spesifik yang disepakati; file struktur folder tetap bisa kamu pertahankan.

CARA PAKAI:
1. Backup project lama.
2. Salin index.html dan folder pages dari paket ini ke project kamu.
3. Pertahankan css/style.css, js/script.js, dan assets milik project kamu.
4. Buka index.html.
5. Jika browser masih membuka tampilan/link lama, tekan Ctrl + F5.
