# Oumra Prestige

Plateforme web de réservation de pèlerinages Oumra.

## Structure

```
oumra_prestige/
├── index.html
├── package.json
└── src/
    ├── pages/
    │   ├── about/about.html
    │   ├── contact/contact.html
    │   ├── reservation/reservation.html
    │   ├── login/login.html
    │   └── signup/signup.html
    └── style/
        └── output/output.css
```

## Pages

| Page | Description |
|------|-------------|
| index.html | Accueil |
| about.html | Mission et valeurs |
| reservation.html | Formulaire réservation multi-étapes |
| contact.html | Formulaire + coordonnées + FAQ |
| login.html | Connexion + OAuth (Google, Facebook) |
| signup.html | Inscription |

## Tech Stack

- HTML5 sémantique
- Tailwind CSS (responsive)
- SVG icons

## Design System

- **Primaire** : Jaune/Or (from-yellow-600 to-yellow-500)
- **Secondaire** : Gris (gray-800, gray-600, gray-400)
- **Responsive** : Mobile-first, md: (768px), lg: (1024px)
- **Spacing** : p-8, px-6, py-3, mb-4
- **Radius** : rounded-2xl (inputs), rounded-3xl (cards)
- **Shadow** : shadow-lg default, shadow-2xl hover

## Liens

- Repository : https://github.com/abbas001900/oumra_prestige.git
- Demo : https://abbas001900.github.io/oumra_prestige/
