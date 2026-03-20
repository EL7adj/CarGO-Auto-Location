# 🚗 CarGO AutoLocation — Prototype Site Web

Prototype d'un site web de **location de voiture en ligne**, développé dans le cadre d'un mini-projet universitaire (Analyse des besoins & Conception de base de données).

---

## 🎯 Objectif

Visualiser les fonctionnalités principales de chaque acteur du système :
- **Client** : recherche, réservation, paiement, avis
- **Agent / Responsable** : gestion du parc automobile
- **Administrateur** : dashboard, statistiques, gestion complète

---

## 📂 Structure du projet

```
autolocation/
├── index.html              # Page d'accueil
├── css/
│   └── style.css           # Système de design complet
├── js/
│   ├── shared.js           # Données partagées & utilitaires
│   └── nav.js              # Navigation dynamique
└── pages/
    ├── login.html          # Connexion
    ├── register.html       # Inscription
    ├── catalogue.html      # Catalogue véhicules + filtres
    ├── detail.html         # Fiche véhicule + formulaire réservation
    ├── reservations.html   # Mes réservations (espace client)
    ├── profil.html         # Profil utilisateur
    ├── admin.html          # Dashboard administrateur
```

---

## 🗂️ Pages disponibles

| Page | URL | Acteur |
|------|-----|--------|
| Accueil | `index.html` | Public |
| Connexion | `pages/login.html` | Tous |
| Inscription | `pages/register.html` | Nouveau client |
| Catalogue | `pages/catalogue.html` | Client |
| Fiche & Réservation | `pages/detail.html?id=1` | Client |
| Mes réservations | `pages/reservations.html` | Client |
| Mon profil | `pages/profil.html` | Client |
| Dashboard Admin | `pages/admin.html` | Admin |
| Parc automobile | `pages/fleet.html` | Admin / Agent |

---

## ✨ Fonctionnalités du prototype

### 👤 Espace Client
- ✅ Inscription et connexion (démo)
- ✅ Recherche avec filtres (catégorie, carburant, boîte, prix, disponibilité)
- ✅ Fiche détaillée d'un véhicule
- ✅ Formulaire de réservation avec calcul automatique du montant
- ✅ Sélection d'options (GPS, siège enfant, assurance…)
- ✅ Confirmation de réservation (modale)
- ✅ Historique et gestion des réservations
- ✅ Annulation de réservation
- ✅ Dépôt d'avis avec notation par étoiles
- ✅ Gestion du profil et sécurité

### 🛠️ Espace Admin / Agent
- ✅ Dashboard avec statistiques (CA, véhicules, clients, incidents)
- ✅ Tableau des dernières réservations avec actions (confirmer/refuser)
- ✅ Gestion du parc : ajout, modification, suppression de véhicules
- ✅ Toggle de disponibilité en temps réel
- ✅ Filtres du parc par catégorie / disponibilité

---

## 🚀 Déploiement sur GitHub Pages

1. Créez un dépôt GitHub (ex: `autolocation`)
2. Poussez tous les fichiers :
   ```bash
   git init
   git add .
   git commit -m "Initial commit — Prototype AutoLocation"
   git remote add origin https://github.com/VOTRE_USERNAME/autolocation.git
   git push -u origin main
   ```
3. Dans les paramètres du dépôt → **Pages** → Source : `main` / `root`
4. Le site sera disponible sur : `https://VOTRE_USERNAME.github.io/autolocation/`

---

## 🛠️ Technologies utilisées

- **HTML5** sémantique
- **CSS3** avec variables CSS (design system dark mode)
- **JavaScript** vanilla (ES6+) — aucune dépendance
- Polices : [Syne](https://fonts.google.com/specimen/Syne) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts

> Aucune installation requise. Ouvrez simplement `index.html` dans un navigateur.

---

## 📚 Contexte académique

Mini-projet — Analyse des besoins, conception de la base de données et prototype  
**Thème** : Site web de location de voiture  
**Technologie** : HTML / CSS / JavaScript  
**Base de données** : Modèle conçu avec [draw.io](https://draw.io)

---

*© 2025 — Prototype universitaire. Toutes les données sont fictives.*
