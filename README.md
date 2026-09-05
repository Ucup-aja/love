# Love — About Her 💖

> A quiet, sincere space dedicated to Zahra Nur'Aeni — by Ahmad Yusuf Firdaus. _Made with love <3_

![Love](https://img.shields.io/badge/Made%20with-Love-e91e8c?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Yes-9c27b0?style=flat)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=flat)

---

## ✨ Tentang Project

Website statis romantis yang bercerita tentang **Zahra Nur'Aeni** — bukan sekadar profil, tapi bentuk apresiasi kecil atas kehadiran, kesabaran, dan rasa aman yang ia bawa.

> _"Dia bukan hanya hadir dalam hidupku, tetapi alasan kenapa hari-hariku terasa lebih berarti. She makes ordinary days feel special."_
> — Home `about_her/index.html`

Dibuat tanpa framework, fokus pada **tipografi, layout yang bersih, dan nuansa pink–purple yang hangat.**

**Live Preview:** Buka `about_her/index.html` langsung di browser.

## 📸 Preview Halaman

| Home / About Her                          | Gallery                                                                             | Contact                                     |
| :---------------------------------------- | :---------------------------------------------------------------------------------- | :------------------------------------------ |
| Hero image + artikel personal untuk Zahra | 11 memori dengan caption manis (Kartini, JC, X'Door, Pilketos, Classmeet, CNP, dll) | Kartu kontak Email, WhatsApp & Social Media |

> Semua foto ada di `about_her/img/` — `her.png` sebagai hero, `g1.jpg` - `g11.jpg` untuk gallery.

## 🎯 Fitur

- **Home (`index.html`)** — Artikel personal _29 Desember 2025_ tentang Zahra
- **Gallery (`gallery.html`)** — Grid responsif 11 foto dengan caption story (`frame` + `frame-spesial`)
- **Contact (`contact.html`)** — Card kontak rapi dengan hover effect
- **Design System Modern** — Gradient `var(--primary) #e91e8c → var(--secondary) #9c27b0`, shadow, radius 16px
- **Fully Responsive** — Breakpoint `768px` & `480px`, mobile-first
- **No Build Step** — HTML + CSS murni, tinggal buka

## 🛠️ Tech Stack

- **HTML5** — Struktur semantik
- **CSS3** — Custom Properties, Flexbox, Grid (`repeat(auto-fill, minmax(260px, 1fr))`), `linear-gradient`, transitions
- **Google Fonts** — [Poppins 300, 400, 600, 700](https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap)
- **No JS / No Framework**

## 📁 Struktur Project

```
love/
├── README.md
└── about_her/
    ├── index.html      # Home - Artikel Zahra
    ├── gallery.html    # Gallery 11 foto + caption
    ├── contact.html    # Contact card
    ├── style.css       # Satu stylesheet untuk semua halaman (364 lines)
    └── img/
        ├── her.png     # Hero image
        └── g1.jpg - g11.jpg
```

## 🚀 Cara Menjalankan

**Opsi 1 — Double Click (Paling Simple)**

```bash
# clone
git clone https://github.com/<username>/love.git
cd love
# buka di file explorer
about_her/index.html
```

**Opsi 2 — Live Server (Recommended)**

```bash
# VS Code: install extension Live Server -> Right Click index.html -> Open with Live Server
# atau dengan npx
npx serve about_her
# atau python
python -m http.server 8000 --directory about_her
```

Lalu buka `http://localhost:8000`

## 🎨 Design System

Disalin dari `style.css:3-17`

| Token            | Value                         | Penggunaan              |
| :--------------- | :---------------------------- | :---------------------- |
| `--primary`      | `#e91e8c`                     | Gradient, hover, accent |
| `--primary-dark` | `#c2186b`                     | Text contact hover      |
| `--secondary`    | `#9c27b0`                     | Gradient                |
| `--dark`         | `#1a1a2e`                     | Body text               |
| `--light`        | `#fef6fb`                     | Background gradient     |
| `--shadow`       | `0 4px 20px rgba(0,0,0,0.08)` | Card                    |
| `--radius`       | `16px`                        | Card, Hero              |

Background: `linear-gradient(135deg, #fef6fb 0%, #f3e5f5 50%, #fce4ec 100%)`

## 🔧 Kustomisasi Cepat

Ganti hero: `style.css:102` -> `background-image: url(img/her.png)`
Ganti warna tema: edit `:root` di `style.css:3`
Tambah foto gallery: duplikasi `<div class="frame">` di `gallery.html:23`

## 🌍 Deploy ke GitHub Pages

1. Push ke GitHub
2. Settings -> Pages -> Source: `main` / `root`
3. Karena halaman di `about_her/`, set **Pages source** ke folder tersebut atau pindahkan `index.html` ke root jika perlu `https://username.github.io/love/`

## 👩‍❤️‍👨 Author

**Ahmad Yusuf Firdaus (her bf)** & **Zahra Nur'Aeni**
Ditulis 29 Desember 2025

- Email: `ahmdyusuf1211@gmail.com` / `zahranuraeni28@gmail.com`
- IG: `@_ahmd.ysf_` / `@shouarietty`
- TikTok: `@yz_128_` / `@zy128_`

## 📌 Roadmap

- [ ] Light/Dark mode toggle
- [ ] Lightbox untuk gallery
- [ ] Animasi scroll reveal
- [ ] Halaman timeline cerita
- [ ] Send message dari page contact

## 📄 Lisensi

MIT — bebas pakai, modifikasi, dan bagikan dengan tetap mencantumkan credit. Made with love <3

---

<p align="center"><i>This is my quiet way of saying thank you — but always felt deeply.</i> 💌</p>
<p align="center">© 2026 Ahmad Yusuf Firdaus & Zahra Nur'Aeni</p>
