# Portfolio Personnel – Pulcherie

Site portfolio personnel présentant mes services, mes projets et un formulaire de contact, avec une page de connexion séparée.

## Aperçu

Le site comprend :
- Une section **À propos** avec photo de profil
- Une section **Services**
- Une section **Projets**
- Un **formulaire de contact**
- Une **page de connexion** indépendante (`login/`)

## 🛠️ Technologies utilisées

- **HTML5** — structure des pages
- **CSS3** — mise en forme et design
- **JavaScript (Vanilla)** — interactions du site

##  Structure du projet

```
portfolio/
├── index.html            # Page principale du portfolio
├── css/
│   └── style.css          # Styles du portfolio
├── script/
│   └── script.js           # Scripts du portfolio
├── Pulcherie.jpeg         # Photo de profil
├── login/                 # Sous-projet : page de connexion
│   ├── index.html
│   └── css/
│       └── script.css      # Styles de la page login
└── README.md
```

> ⚠️ Le projet contient **deux parties indépendantes** : le portfolio principal (racine) et la page de connexion (`login/`). Chaque partie a son propre dossier `css/` — ne les mélangez pas, les chemins relatifs (`./css/...`) sont différents selon le fichier HTML.

## Utilisation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/sawadogopulcherie544-art/portfolio.git
   ```
2. Ouvrez `index.html` dans votre navigateur, ou publiez le site avec **GitHub Pages** :
   - Allez dans **Settings > Pages**
   - Sélectionnez la branche `main` et le dossier `/root`
   - Le site sera accessible à l'adresse générée automatiquement par GitHub
3. Le lien **Login** dans la barre de navigation redirige vers `login/index.html`

## Fonctionnalités

- Navigation fluide entre les sections (About, Projects, Contact)
- Formulaire de contact
- Page de connexion dédiée avec son propre style

## Auteur

Créé par [Pulcho](https://github.com/sawadogopulcherie544-art)
