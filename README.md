# 🌤️ Weather_App - Application Météo en Dart

**Weather_App** est une application mobile simple développée en **Dart** avec **Flutter** pour afficher les conditions météorologiques en temps réel d'une ville donnée. Elle utilise l'API de **OpenWeatherMap** pour récupérer les informations météorologiques telles que la température, l'humidité, la vitesse du vent, etc.

## 🎯 Objectif du Projet

L'objectif de **Weather_App** est d'offrir une interface intuitive pour consulter les données météorologiques locales ou mondiales en temps réel. L'application permet d'entrer le nom d'une ville et d'obtenir instantanément les informations météorologiques actuelles.

## 🚀 Fonctionnalités

- ☀️ **Affichage des conditions météorologiques** : température, humidité, vitesse du vent, et description du temps actuel (ensoleillé, nuageux, etc.).
- 🗺️ **Recherche par ville** : l'utilisateur peut entrer le nom d'une ville pour obtenir les données météo correspondantes.
- 🌍 **Support pour plusieurs pays** : recherche de villes du monde entier avec des informations mises à jour en temps réel.
- 📅 **Prévision** : affichage de la météo pour les prochains jours (optionnel).
- 🔔 **Notifications** : alertes météo importantes (tempêtes, canicules, etc.) (optionnel).

## 🛠️ Technologies Utilisées

- **Langage** : Dart 🐦
- **Framework** : Flutter 📱
- **API Météo** : OpenWeatherMap API 🌍
- **Gestion d'état** : Provider (ou Riverpod, selon préférence)
- **Déploiement** : Android et iOS

## 📂 Structure du Projet

```bash
weather_app/
├── lib/
│   ├── models/
│   ├── services/
│   ├── ui/
│   ├── widgets/
│   └── main.dart
├── assets/
│   ├── images/
│   └── fonts/
├── pubspec.yaml
├── README.md

