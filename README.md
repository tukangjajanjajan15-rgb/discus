# Royal Discus Farm

Aplikasi katalog ikan Discus dengan halaman publik dan dashboard admin. Dibuat menggunakan HTML, Tailwind CSS CDN, dan JavaScript tanpa proses build; data katalog disimpan di `localStorage` browser.

## Menjalankan

1. Buka `index.html` langsung di browser, atau jalankan server lokal dari folder ini, misalnya `python -m http.server 8000`.
2. Kunjungi `http://localhost:8000` jika memakai server lokal.
3. Pilih **Admin** dan masuk menggunakan PIN awal `admin123`.

Dashboard mendukung perubahan stok, tambah/edit/hapus jenis ikan, serta **Reset ke Data Awal**. Katalog akan diperbarui langsung dan tersimpan pada browser yang digunakan. Ubah `WHATSAPP_NUMBER` di bagian script `index.html` ke nomor WhatsApp farm dalam format internasional tanpa tanda `+` sebelum dipublikasikan.

Tailwind CSS, Google Fonts, dan gambar katalog dimuat dari internet, sehingga tampilan lengkap memerlukan koneksi internet.
