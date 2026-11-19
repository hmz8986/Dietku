DIETTRACK HAFIZ

Kandungan:
- index.html: aplikasi
- manifest.webmanifest: tetapan pemasangan PWA
- sw.js: sokongan offline
- icon.svg: ikon

CARA GUNA PALING MUDAH
1. Muat naik semua fail ini ke hosting HTTPS statik, contohnya GitHub Pages.
2. Buka alamat laman tersebut menggunakan Chrome Android.
3. Tekan menu tiga titik Chrome, kemudian pilih "Install app" atau "Add to Home screen".
4. Selepas aplikasi dibuka sekurang-kurangnya sekali ketika online, fail aplikasi boleh dicache untuk kegunaan offline.

PENTING
- Pemasangan PWA dan service worker memerlukan HTTPS atau localhost. Membuka index.html terus sebagai fail tidak mengaktifkan pemasangan PWA/offline.
- Data diet disimpan dalam localStorage pada pelayar/peranti itu sahaja. Jangan padam data pelayar jika mahu mengekalkan rekod.
- Gunakan butang Eksport sandaran JSON secara berkala.
- Nilai nutrisi ialah anggaran umum per 100g. Jenama, resipi dan cara memasak boleh mengubah nilai sebenar.
- Sasaran kalori dan makro ialah titik permulaan, bukan preskripsi perubatan.
