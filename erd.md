# Portfolio Website — Aghna Damarula Prianta (Network Engineer)

Website portfolio premium bertema Network Engineer dengan desain modern dark-mode, animasi network nodes, dan fitur upload gambar.

## Informasi dari Asset

Berdasarkan gambar yang diberikan, berikut data yang akan dimasukkan:

### Profil
- **Nama**: Aghna Damarula Prianta
- **Panggilan**: Ben
- **Role**: Network Engineer | Asisten Dosen di Politeknik IDN Bogor
- **Lahir**: Bekasi, 14 Juni 2004
- **Bio**: Enthusiast Network Engineer, passionate about configuring servers, networking, dan teknologi

### Pengalaman Kerja
1. **HSP NET** — Jakarta Timur | 2022
   - 4 bulan kerja, installing backbone cable 48 cores 2km, access point, maintenance FTTH, monitoring traffic server
2. **Razanet** — Bekasi, Cibitung | 2023–2024
   - 1 tahun, backbone cable 7 countries, maintenance FTTH, OLT Huawei SmartAX MA5800, load balancing, failover system
3. **Asisten Dosen** — Politeknik IDN Bogor | Saat ini aktif

### Sertifikasi / Achievements
1. **MTCNA** — MikroTik Certified Network Associate (2024–2027)
2. **MTCRE** — MikroTik Certified Routing Engineer (2024–2027)

### Projects
1. **Buku "Jago BGP dalam Sehari"** — Final project di Politeknik IDN
2. **Buku "SUPERLAB REALITA"** — Final project di Politeknik IDN Bogor
2. **MAZNET (Business)** — May 2024 – Now
   - 150 clients FTTH, registered Kominfo via HSP NET, monitoring CHR MikroTik, expansion ke 3 lokasi
3. **PERURI (Badan Gizi Nasional)** — Setup nodes 3500 RUTX11 Configuration

---

## Design Concept

### Theme: Dark Cyber-Network
- **Background**: Dark (#0a0a0f) dengan animated network node particles (titik-titik yang terhubung garis, bergerak pelan)
- **Primary Color**: Crimson Red (#dc2626) — bold dan powerful
- **Accent**: Deep Red (#991b1b) / Dark Red (#7f1d1d) untuk highlights
- **Scheme**: Black & Red — dark aggressive tech aesthetic
- **Cards**: Glassmorphism (semi-transparent, blur backdrop)
- **Typography**: Google Fonts — "Inter" untuk body, "Space Grotesk" untuk headings
- **Animations**: Scroll reveal animations, hover effects, particle background

### Visual Elements
- Network topology-inspired decorations (nodes & edges)
- Terminal/console-style accent text
- Gradient borders pada cards
- Animated skill bars

---

## Proposed Changes

### Core Files

#### [NEW] [index.html](file:///c:/Users/ben/Documents/Portofolio/index.html)
Single-page portfolio dengan sections:
1. **Navbar** — Fixed, transparent, scroll-aware (berubah solid saat scroll)
2. **Hero Section** — Full viewport, nama besar + tagline + animated network background canvas
3. **About Me** — Photo + bio + role sebagai Asisten Dosen Politeknik IDN Bogor
4. **Experience Timeline** — Vertical timeline dengan cards (HSP NET, Razanet, Asisten Dosen)
5. **Achievements** — Sertifikasi MTCNA & MTCRE dengan card layout
6. **Projects** — Buku BGP & MAZNET business
7. **Gallery** — Section untuk menampilkan gambar via URL input (URL list disimpan di localStorage)
8. **Contact / Footer** — Info kontak dan social links

#### [NEW] [style.css](file:///c:/Users/ben/Documents/Portofolio/style.css)
- CSS variables untuk design tokens (colors, spacing, typography)
- Dark mode base styling
- Glassmorphism card components
- Timeline component styling
- Responsive grid layouts (mobile-first)
- Smooth animations & transitions
- URL gallery grid styling
- Particle canvas overlay styling

#### [NEW] [script.js](file:///c:/Users/ben/Documents/Portofolio/script.js)
- **Network particle animation** — Canvas-based animated nodes & connections di hero
- **Scroll animations** — Intersection Observer untuk reveal-on-scroll
- **Navbar behavior** — Transparent → solid on scroll
- **Smooth scrolling** — Navigasi antar section
- **Image URL gallery** — URL input, preview, localStorage URL persistence
- **Gallery management** — Display images from URLs, add/delete capability
- **Typing effect** — Terminal-style typing pada hero section

#### [NEW] [assets/](file:///c:/Users/ben/Documents/Portofolio/assets/)
- Folder untuk menyimpan gambar-gambar yang di-generate (profile photo placeholder, certificate images)

---

## Fitur Gallery / Image Display

Implementasi gallery berbasis URL:
- Input field untuk memasukkan **URL gambar** (bukan upload file)
- Preview gambar dari URL sebelum ditambahkan
- Simpan URL ke **localStorage** untuk persistence
- Gallery grid untuk menampilkan gambar-gambar
- Kemampuan hapus gambar dari gallery
- Mudah di-edit: cukup ganti URL untuk update gambar

> [!NOTE]
> Gambar ditampilkan via URL eksternal, sehingga tidak ada batasan storage. URL list disimpan di localStorage untuk convenience.

---

## Resolved Questions

- ✅ **Foto profil**: Akan menggunakan placeholder yang bisa diganti nanti dengan URL
- ✅ **Kontak/Social Media**:
  - Email: aghnadamarulaprianta@gmail.com
  - GitHub: https://github.com/Bensiddd
  - Instagram: @bens.id
- ✅ **Bahasa website**: English
- ✅ **Gambar sertifikat**: Ditampilkan sebagai gambar langsung (akan generate placeholder, bisa diganti URL nanti)
- ✅ **Color scheme**: Black & Red theme

---

## Verification Plan

### Manual Verification
- Buka `index.html` di browser dan verifikasi:
  - Semua section tampil dengan benar
  - Animasi particle background berjalan smooth
  - Scroll animations berfungsi
  - Navbar berubah saat scroll
  - Image upload berfungsi (upload, preview, simpan, hapus)
  - Responsive di berbagai ukuran layar (mobile, tablet, desktop)