# Danîa✨ V1

Application Flutter de personnalisation de fonds d'écran.

## Fonctionnalités V1
- Accueil Danîa✨
- Import galerie
- Appareil photo
- Éditeur de fond d'écran
- Texte, couleur et taille
- Filtres visuels
- Cadres
- Sauvegarde dans la galerie
- Définition comme fond d'écran Android
- Catégories
- Favoris locaux (base prête)
- Profil local

## Démarrage local
```bash
flutter create --platforms=android .
flutter pub get
flutter run
```

## Compilation Android
```bash
flutter build apk --release
flutter build appbundle --release
```

Le fichier AAB est celui destiné à Google Play.

## Codemagic
Le fichier `codemagic.yaml` génère les fichiers Android si nécessaire, installe les dépendances et produit APK + AAB.

Avant une publication officielle, configurer la signature Android dans Codemagic avec le keystore permanent de Danîa✨.
