# ☕ Le Café Numérique — Site Vitrine

> *Où chaque tasse est une connexion, chaque pixel une saveur.*

## Description

Site vitrine du **Café Numérique**, un café fictif parisien situé dans le 11e arrondissement, dédié à la communauté tech et créative.

## Structure des fichiers

```
cafe-numerique/
├── index.html      → Page d'accueil (Hero, Features, CTA)
├── menu.html       → La Carte (boissons & prix)
├── apropos.html    → À Propos (histoire, équipe, valeurs)
├── contact.html    → Contact (adresse, horaires, formulaire)
├── style.css       → Feuille de styles commune
└── README.md       → Ce fichier
```

## Pages

| Fichier | Section | Contenu |
|---|---|---|
| `index.html` | Accueil | Logo, nom, slogan, navigation, features |
| `menu.html` | La Carte | 6 catégories de boissons avec prix |
| `apropos.html` | À Propos | Histoire, statistiques, valeurs, équipe |
| `contact.html` | Contact | Adresse, horaires, formulaire, événements |

## Design

- **Palette** : Fond sombre (`#0e0c0a`), or (`#c9923a`), crème (`#f2e8d5`)
- **Typographie** : Playfair Display (titres) + DM Sans (corps) + DM Mono (labels)
- **Style** : Editorial / Art Deco — ambiance café premium & digital
- **Boutons** : `border-radius: 0` sur tous les boutons et inputs (requis)

## Règles CSS importantes

Tous les boutons (`.btn`, `.btn-primary`, `.btn-outline`, `.btn-accent`) ont `border-radius: 0`.
Tous les champs de formulaire (`input`, `textarea`, `select`) ont également `border-radius: 0`.

## Lancer le projet

Ouvrir `index.html` directement dans un navigateur, ou utiliser un serveur local :

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (npx)
npx serve .
```

Puis visiter `http://localhost:8000`

## Déploiement GitHub Pages

1. Créer un dépôt GitHub : `cafe-numerique`
2. Pousser tous les fichiers :
   ```bash
   git init
   git add .
   git commit -m "feat: site vitrine Café Numérique"
   git branch -M main
   git remote add origin https://github.com/VOTRE_USERNAME/cafe-numerique.git
   git push -u origin main
   ```
3. Dans les **Settings** du dépôt → **Pages** → Source : `main` / `/ (root)`
4. Le site sera disponible sur `https://VOTRE_USERNAME.github.io/cafe-numerique/`

---

*Projet réalisé dans le cadre d'un TP — Mise en ligne d'un projet sur GitHub.*
