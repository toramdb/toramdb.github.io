# ToramCodex — Toram Online Database

Fan-made database untuk game **Toram Online**, dihosting lewat GitHub Pages.

## 🗂️ Struktur Halaman

```
/
├── index.html            # Homepage — hero, kategori, spotlight, item & monster terbaru
├── css/style.css         # Mobile-first stylesheet (dark RPG theme)
├── js/main.js            # Hamburger menu, filter, search, back-to-top, animasi angka
└── pages/
    ├── items.html        # Database item (senjata, armor, aksesori, material)
    ├── monsters.html     # Database monster (boss, mini-boss, mob) + tabel drop
    ├── skills.html       # Database skill (aktif, pasif, combo)
    ├── maps.html         # Database map / area
    └── quests.html       # Database quest (main story, side, daily, event)
```

## 🎨 Tema & Desain

| Aspek | Detail |
|---|---|
| **Palet warna** | Navy `#0d1117` · Cyan `#58a6ff` · Gold `#d4a017` |
| **Typography** | Segoe UI / system-ui, sans-serif |
| **Layout** | Mobile-first CSS Grid & Flexbox |
| **Navigasi** | Sticky navbar + hamburger drawer di mobile |
| **Komponen** | Card grid, data table, filter bar, pagination, breadcrumb, back-to-top |

## ✨ Fitur

- ✅ Fully mobile-friendly (responsive di semua ukuran layar)
- ✅ Search bar tersinkron di navbar, mobile drawer, dan hero
- ✅ Filter real-time (nama + kategori) tanpa reload
- ✅ Animated counter stats di hero
- ✅ Dark RPG theme — zero external CSS dependency (pure CSS vars)
- ✅ Aksesibilitas: ARIA labels, roles, `aria-expanded`, semantic HTML

## 🚀 GitHub Pages

Aktifkan di **Settings → Pages → Deploy from branch `main`** (root `/`).

---

> **Disclaimer:** ToramCodex adalah proyek fan-made dan tidak berafiliasi dengan Asobimo, Inc.  
> Toram Online™ adalah merek dagang milik Asobimo, Inc.
