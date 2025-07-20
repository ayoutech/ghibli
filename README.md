# Ghibli Flutter App

Une application Flutter qui permet de parcourir et d'explorer les films du Studio Ghibli.

## ✨ Fonctionnalités

- Affichage de la liste des films du Studio Ghibli (données issues de l'API publique).
- Navigation vers une page de détails pour chaque film.
- Page de détails responsive :
  - Colonne gauche : image du film
  - Colonne droite :
    - Titre
    - Titre original
    - Titre romanisé
    - Description
    - Réalisateur
    - Producteur
    - Année de sortie
    - Durée
    - Note (étoiles, basée sur le score Rotten Tomatoes)
- Affichage de la note du film sous forme d'étoiles (package `flutter_rating_stars`).
- UI moderne, responsive, et claire.

## 🚀 Installation

1. **Cloner le repo**
   ```bash
   git clone <url-du-repo>
   cd ghibli
   ```
2. **Installer les dépendances**
   ```bash
   flutter pub get
   ```
3. **Lancer l'application**
   ```bash
   flutter run
   ```

## 📦 Dépendances principales
- [go_router](https://pub.dev/packages/go_router) : gestion de la navigation
- [http](https://pub.dev/packages/http) : requêtes API
- [flutter_rating_stars](https://pub.dev/packages/flutter_rating_stars) : affichage des notes en étoiles

## 🗂️ Structure du projet
```
lib/
  models/         # Modèles de données (Movie)
  screens/        # Écrans principaux (Home, Movie)
  services/       # Services (API, routing)
  theme/          # Thème et styles
  widgets/        # Widgets réutilisables
```

## 🌐 API utilisée
- [Ghibli API](https://ghibliapi.vercel.app/)

## 👤 Auteur
- Projet réalisé dans le cadre d'un exercice Flutter (Digital School Paris)

