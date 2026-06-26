# DRIP<span>.</span>id

> **Perangkat lunak untuk bisnis yang sedang bergerak.**

Website resmi **PT. DRIP RINTISAN INOVASI PERKASA** — software atelier Indonesia yang melayani UMKM, korporasi, dan instansi pemerintah di seluruh nusantara.

🌐 **Live:** [drip.id](https://drip.id)

---

## Tentang

DRIP adalah software atelier kecil yang dikelola solo oleh Maulana — software engineer dengan 11+ tahun pengalaman. Kami menulis kode untuk bisnis yang ingin benar-benar berjalan, bukan sekadar tampilan yang cantik.

### Segmen Klien

| Segmen | Cocok untuk | Mulai dari |
| --- | --- | --- |
| **UMKM** | Toko online, kasir, landing page, integrasi QRIS | Rp 15 juta |
| **Korporasi** | ERP, CRM, dashboard, integrasi API, SSO/RBAC | Rp 50 juta |
| **Pemerintah** | Sistem informasi SPBE, e-procurement LKPP, hosting PDN | via tender |

### Layanan

1. **Aplikasi Custom** — web, mobile, dashboard internal
2. **AI Agent & Otomasi** — chatbot WhatsApp, workflow, analisis data
3. **Integrasi Sistem & API** — payment gateway, accounting, marketplace, API pemerintah
4. **Konsultasi & Perencanaan IT** — roadmap, audit, arsitektur
5. **Migrasi & Modernisasi** — legacy → stack modern
6. **Pemeliharaan & Support** — monitoring 24/7, update keamanan

### Produk Kami

Kami tidak hanya jasa — kami juga punya produk sendiri yang dipakai ribuan pengguna:

- **[Mesjid.app](https://mesjid.app)** — display TV digital untuk 100+ masjid di Indonesia
- **[DripSender.id](https://dripsender.id)** — otomasi WhatsApp marketing untuk UMKM
- **[DripForm.id](https://dripform.id)** — form builder + CRM + landing page
- **[Laju.dev](https://laju.dev)** — framework SaaS berperforma tinggi (258k RPS, open source)
- **[Antre.in](https://antre.in)** — sistem antrian digital untuk klinik & bisnis jasa

---

## Tech Stack

- **Framework:** [Astro](https://astro.build) v5
- **Styling:** [Tailwind CSS](https://tailwindcss.com) v4 (via `@tailwindcss/vite`)
- **Fonts:** Instrument Serif (display) · Inter (body) · JetBrains Mono (specs)
- **Output:** Static site (`output: 'static'`)

---

## Design Language

Situs ini menggunakan konsep **"Editorial Atelier"** — visual language yang terinspirasi dari majalah premium:

- 📰 Warm cream background (`#F4EFE6`) dengan paper noise texture
- ✒️ Instrument Serif untuk headline editorial + Inter untuk body
- 🔢 Section bernomor (`01`, `02`, `03`...) seperti halaman majalah
- 🇬🇷 Greek letters (`α`, `β`, `γ`) untuk penanda segmen klien
- 🔢 Roman numerals (`I`, `II`, `III`, `IV`) untuk proses kerja
- 📋 FACT SHEET spec card dengan dashed borders
- 🏛️ Stamp-style badges untuk NDA & "Paling Diminati"
- 📜 Pull quotes untuk testimonials dengan mono small caps attribution
- 🎨 Accent: deep emerald (`#064E3B`) · gold (`#A88A4D`) · rust (`#B45309`)

---

## Struktur Project

```
drip-id/
├── astro.config.mjs        # Astro config + Tailwind plugin
├── package.json
├── public/
│   ├── laju.png            # Logo produk untuk portfolio
│   ├── antrein.png
│   └── slugpost.png
└── src/
    ├── layouts/
    │   └── Layout.astro    # Masthead header + colophon footer
    ├── pages/
    │   └── index.astro     # Homepage (8 section editorial)
    └── styles/
        └── global.css      # Fonts, custom utilities, paper texture
```

---

## Development

```bash
# Install dependencies
npm install

# Jalankan dev server (http://localhost:4321)
npm run dev

# Build untuk production
npm run build

# Preview hasil build
npm run preview
```

---

## Kontak

| | |
| --- | --- |
| **WhatsApp** | [0859-1069-563-90](https://wa.me/62859106956390) |
| **Email** | [maulana@drip.id](mailto:maulana@drip.id) |
| **Lokasi** | Yogyakarta, Indonesia |
| **Wilayah layanan** | Seluruh Indonesia (remote) |
| **Jam kerja** | Sen–Jum · 09–18 WIB |

---

## Legal

© 2026 **PT. DRIP RINTISAN INOVASI PERKASA**

NPWP: `39.474.371.0-732.000`

---

## License

Source code website ini adalah **proprietary** — semua hak dilindungi.

Konten, desain, dan teks adalah milik PT. DRIP RINTISAN INOVASI PERKASA. Tidak boleh diperbanyak atau digunakan ulang tanpa izin tertulis.

Namun, kalau Anda tertarik dengan pendekatan desainnya, silakan [kontak kami](https://wa.me/62859106956390) untuk project serupa. Kami senang membantu. ✨
