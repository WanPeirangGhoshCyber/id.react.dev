# id.react.dev

Repo ini berisi kode sumber dan dokumentasi yang mendukung [react.dev](https://react.dev/).

 ## Memulai

### Prasyarat

1. Git
1. Node: versi 12.x apa pun yang dimulai dengan v12.0.0 atau yang lebih baru
1. Yarn: Lihat [situs web Yarn untuk petunjuk instalasi](https://yarnpkg.com/lang/en/docs/install/)
1. Fork repo (untuk kontribusi apa pun)
1. Kloning [repo id.react.dev](https://github.com/reactjs/id.react.dev) di komputer lokal Anda

### Instalasi

1. `cd id.react.dev` untuk masuk ke root proyek
3. `yarn` untuk menginstal dependensi npm situs web

### Berjalan secara lokal

1. `yarn dev` untuk memulai server pengembangan (didukung oleh [Next.js](https://nextjs.org/))
1. `buka http://localhost:3000` untuk membuka situs  di peramban favorit Anda

## Kontribusi

### Pedoman

Dokumentasi dibagi menjadi beberapa bagian dengan nada dan tujuan yang berbeda. Jika Anda berencana untuk menulis lebih dari beberapa kalimat, mungkin akan membantu jika Anda memahami [pedoman kontribusi](https://github.com/reactjs/react.dev/blob/main/CONTRIBUTING.md#guidelines-for-text) untuk bagian yang sesuai.

 ### Buat cabang

1. `git checkout main` dari folder mana pun di repositori `react.dev` lokal Anda
1. `git pull origin main` untuk memastikan Anda memiliki kode utama terbaru
1. `git checkout -b the-name-of-my-branch` (ganti `the-name-of-my-branch` dengan nama yang sesuai) untuk membuat cabang

### Lakukan perubahan

1. Ikuti petunjuk ["Menjalankan secara lokal"](#running-locally)
1. Simpan file dan periksa di browser
1. Perubahan pada komponen React di `src` akan dimuat ulang secara otomatis
1. Perubahan pada file markdown di `content` akan dimuat ulang secara otomatis
1. Jika bekerja dengan plugin, Anda mungkin perlu menghapus direktori `.cache` dan memulai ulang server

### Uji perubahan

1. Jika memungkinkan, uji perubahan visual apa pun di semua versi terbaru browser umum, baik di desktop maupun seluler.  2. Jalankan `yarn check-all`. (Ini akan menjalankan Prettier, ESLint, dan memvalidasi tipe.)

### Dorong

1. `git add -A && git commit -m "Pesan saya"` (mengganti `Pesan saya` dengan pesan komit, seperti `Perbaiki logo header di Android`) untuk menyiapkan dan melakukan komit perubahan Anda
1. `git push my-fork-name the-name-of-my-branch`
1. Buka [repo id.react.dev](https://github.com/reactjs/id.react.dev) dan Anda akan melihat cabang yang baru saja didorong.
1. Ikuti petunjuk GitHub.
1. Jika memungkinkan, sertakan tangkapan layar perubahan visual. Pratinjau build dipicu setelah perubahan Anda didorong ke GitHub.

 ## Terjemahan

Jika Anda tertarik menerjemahkan `react.dev`, silakan lihat upaya penerjemahan terkini [di sini](https://github.com/reactjs/react.dev/issues/4135).

## Lisensi
Konten yang dikirimkan ke [react.dev](https://react.dev/) berlisensi CC-BY-4.0, sebagaimana ditemukan dalam berkas [LICENSE-DOCS.md](https://github.com/reactjs/react.dev/blob/main/LICENSE-DOCS.md).