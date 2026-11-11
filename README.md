# Carousel Studio

Alat gratis untuk membuat carousel Instagram 4:5 (1080x1350 px) dari template tetap. Semua proses berjalan di browser, tanpa server dan tanpa API key.

## Fitur

- Pilih template (bawaan Sandiana.art atau unggah PNG sendiri)
- Banyak slide: judul, isi, kata sorot, dan gambar referensi per slide
- Tampilan: Minimalis, Editorial, Futuristik, Lembut
- Gambar menyatu dengan background: fade tepi, hapus latar, kartu bulat, duotone palet
- Unduh per slide (PNG) atau semua slide (ZIP)
- Prompt AI per slide untuk Google Flow (opsional)
- Ilustrasi vektor otomatis per slide lewat Gemini (SVG, tanpa teks dan tanpa figur manusia)
- Gambar latar (layer di atas template) per slide: ukuran, posisi, fade empat sisi, opasitas, dan lapisan peredam teks
- Impor rangkuman dari website atau YouTube (manual lewat Claude/Gemini, atau otomatis lewat Gemini API dengan key milikmu sendiri; website dibaca lewat URL context Gemini)

## Palet warna

| Warna | Hex |
|---|---|
| Background | `#050D19` |
| Cyan Blue | `#00A8FF` |
| Ice Blue | `#A5E8FF` |
| Text | `#F4FAFF` |

## Menjalankan

Buka `index.html` di browser. Tidak perlu instalasi.

Font Montserrat dimuat dari Google Fonts, jadi butuh koneksi internet.

## Hosting (GitHub Pages)

1. Buka **Settings > Pages**.
2. Pada **Source**, pilih **Deploy from a branch**.
3. Pilih branch `main` dan folder `/ (root)`, lalu **Save**.
4. Tunggu 1-2 menit. Alamat: `https://USERNAME.github.io/carousel-studio/`

---

by [Fajar Umarsandi](https://www.instagram.com/sandiana.art/)


## Catatan keamanan

API key Gemini hanya diketik di browser dan, kalau kamu centang "Ingat key", disimpan di localStorage browsermu. Jangan menulis key ke dalam file HTML atau mengunggahnya ke GitHub.
