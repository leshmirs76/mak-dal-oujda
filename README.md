# Mak'Dal Oujda — Landing Page

Site vitrine du fast-food **Mak'Dal Oujda** (Maroc).
Single-page, ultra-moderne, premium — burgers, naan, pizzas, sandwichs et configurateur de tacos sur-mesure.

## Aperçu

- Hero parallax avec disque rose-fuchsia + halo gold rotatif
- Menu complet par catégories (Burgers, Naan, Naan Burger, Pizzas, Sandwichs)
- **Configurateur "Compose ton Tacos"** interactif — taille, viandes, sauces, suppléments
- Carrousel Naan avec drag, prev/next, dots
- Localisation Google Maps intégrée
- Marquee défilant, animations au scroll, glassmorphism
- 100% responsive mobile-first

## Stack

- HTML5 single-file (aucun build)
- Tailwind CSS via CDN avec config étendue (palette `brand` rose + `gold`)
- Lucide Icons
- Google Fonts : Anton (titres impact) + Inter (corps)
- Vanilla JS pour interactivité (configurateur, carrousels, reveal au scroll)

## Lancer en local

Aucun build, aucune dépendance npm.

```bash
# Option 1 — ouvrir directement
start index.html

# Option 2 — serveur local (recommandé pour les chemins d'images)
python -m http.server 8000
# puis http://localhost:8000
```

## Structure

```
.
├── index.html          # Landing page complète
├── BURGER/             # PNGs transparents burgers
├── NAAN/               # PNGs naan signature
├── NAAN BURGER/        # PNGs nouveautés
├── PIZZA/              # PNGs pizzas
├── SANDWICH/           # PNGs sandwichs
└── TACOS/              # Image tacos (configurateur)
```

## Déploiement GitHub Pages

Le site étant statique, il se déploie automatiquement via GitHub Pages :

1. Settings → Pages → Source : `main` branch, `/root`
2. URL publiée : `https://<user>.github.io/<repo>/`

---

Conçu avec passion à Oujda 🇲🇦
