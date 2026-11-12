# Genivora — Enterprise Digital Solutions & AI Engineering
> Website Company Profile modern berbasis **PHP CodeIgniter 4** dan **CSS Bootstrap 5** dengan estetika Dark-Tech Glassmorphism.

---

## 🚀 Fitur Unggulan Website

1. **Desain Kelas Enterprise (Aesthetic & Responsive)**
   - Tema *Dark-Tech Obsidian* dengan aksen neon cyber cyan, vibrant blue, dan purple glow.
   - Glassmorphism dengan `backdrop-filter: blur`, subtle border gradients, dan animasi hover responsif.
   - Tipografi modern Google Fonts (*Outfit* & *Plus Jakarta Sans*).
   - Ikonografi Bootstrap Icons & vector assets SVG murni (ringan dan tajam di layar Retina 4K).

2. **Komponen & Arsitektur Interaktif**
   - **Sticky Glass Navbar**: Blur dinamis saat di-scroll dengan navigasi *smooth-scroll* & indikator tautan aktif.
   - **Hero Section**: Headline futuristik, tech pill badge, dan ilustrasi vektor interaktif *Nexus Core Infrastructure*.
   - **Partners / Cloud Ecosystem**: Marquee logo platform teknologi kelas dunia (AWS, GCP, Kubernetes, Docker, PostgreSQL, CodeIgniter 4).
   - **About Genivora**: 4 pilar nilai rekayasa software dan *Live Animated KPI Counters* (150+ Proyek, 99.8% Uptime SLA, 98% Retensi Klien, 10+ Tahun Pengalaman).
   - **Solusi & Layanan**: 6 kartu layanan enterprise dengan checklist fitur, tag teknologi, dan *Service Detail Modal* interaktif.
   - **Studi Kasus & Portofolio**: Filter instan tanpa reload halaman (Semua, Web App, AI & Machine Learning, Cloud & DevOps, IoT Logistics, MedTech/FinTech) dengan ilustrasi mockup SVG berkualitas tinggi.
   - **Kalkulator Estimasi Biaya Interaktif**: Pengunjung dapat memilih platform (Web, Mobile, Cloud, AI), skala sistem (MVP, Growth, Enterprise), serta opsi add-on modul untuk kalkulasi biaya dan timeline pengerjaan real-time dalam Rupiah (IDR), lengkap dengan integrasi tombol penawaran WhatsApp otomatis.
   - **Model Kerjasama & Skema Investasi**: Pilihan paket *Sprint MVP*, *Dedicated Tech Squad*, dan *Custom Enterprise Ecosystem*.
   - **Ulasan & Testimoni Klien**: Ulasan dari CTO dan VP of Engineering enterprise.
   - **FAQ Accordion**: Tanya jawab interaktif seputar kepemilikan IP 100%, jaminan garansi bug-free, dan NDA.
   - **Formulir Konsultasi & Penawaran**: Dilengkapi CSRF protection, validasi input, dan feedback interaktif.
   - **Floating Widgets**: Tombol pintas konsultasi WhatsApp langsung dan tombol *Back to Top*.

---

## 📂 Struktur Direktori Proyek

```
d:/Project/Genivora/Website/
├── app/
│   ├── Config/
│   │   ├── Routes.php           # Routing URL & API submit
│   │   ├── App.php              # Base URL & konfigurasi umum
│   │   └── Security.php         # Proteksi keamanan & CSRF
│   ├── Controllers/
│   │   ├── Home.php             # Controller utama untuk landing page
│   │   └── Contact.php          # Controller pemrosesan formulir & AJAX
│   └── Views/
│       ├── layouts/
│       │   └── main.php         # Master layout template
│       ├── partials/
│       │   ├── navbar.php       # Navigasi sticky glassmorphism
│       │   ├── footer.php       # Footer korporat
│       │   └── modals.php       # Modal penawaran, detail layanan & legalitas
│       └── home.php             # Halaman utama dengan 10+ section
├── public/
│   ├── assets/
│   │   ├── css/
│   │   │   └── genivora.css     # Master custom design system & styling
│   │   ├── js/
│   │   │   └── genivora.js      # Kontrol interaktif, kalkulator & animasi
│   │   └── img/                 # Vektor logo, icon & mockup SVG
│   └── index.php                # Front controller CodeIgniter 4
├── .env                         # Konfigurasi environment (CI_ENVIRONMENT = development)
└── spark                        # CodeIgniter 4 CLI tool
```

---

## 🛠️ Cara Menjalankan Proyek Secara Lokal

### Menggunakan Built-in Spark Server (Direkomendasikan)
Buka terminal PowerShell pada direktori proyek, lalu jalankan:

```powershell
php spark serve --port 8080
```
Buka browser dan akses: `http://localhost:8080`

### Menggunakan XAMPP / Laragon
1. Salin seluruh isi folder proyek ini ke `htdocs/genivora` (pada XAMPP) atau `www/genivora` (pada Laragon).
2. Konfigurasi `app.baseURL` pada file `.env` menjadi:
   ```env
   app.baseURL = 'http://localhost/genivora/public/'
   ```
3. Akses melalui browser pada alamat di atas.

---

## 🛡️ Standar Kualitas & Keamanan
- Built with **CodeIgniter 4.7.5** & **PHP 8.3**.
- CSRF Protection & XSS Escaping bawaan aktif.
- Semantic HTML5 & SEO Friendly Meta Tags (OpenGraph, Twitter Cards, Schema Ready).
