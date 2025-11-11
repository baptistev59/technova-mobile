# 📱 TechNova Mobile (Flutter)

![Flutter](https://img.shields.io/badge/Flutter-3.24-blue)
![Dart](https://img.shields.io/badge/Dart-3.5-lightblue)
![REST API](https://img.shields.io/badge/API-REST-green)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow)

## 🚀 Présentation
Le projet **TechNova Mobile** est une application développée sous **Flutter 3**, connectée à l’API Symfony.
Deux applications sont prévues :
- **App Client** : navigation produit, panier, paiement Stripe
- **App Vendeur** : gestion de boutique, produits et commandes

---

## ⚙️ Stack technique
- **Flutter 3 / Dart 3**
- **http** pour la communication API
- **Provider** ou **Riverpod** pour la gestion d’état
- **JWT** pour l’authentification sécurisée
- **Material Design 3** pour l’UI

---

## 🧩 Installation locale
```bash
git clone https://github.com/baptistev59/technova-mobile.git
cd technova-mobile
flutter pub get
flutter run
```

---

## 🔧 Configuration
Créer un fichier `lib/config/api.dart` :
```dart
class ApiConfig {
  static const baseUrl = "http://localhost:8000/api";
}
```

---

## 🧱 Build de production
```bash
flutter build apk   # Android
flutter build ios   # iOS
```

---

## 👤 Auteur
**Développé par : Baptiste VANDAELE**

---

## 📜 Licence
Ce projet est sous licence **MIT**. Voir le fichier `LICENSE` pour plus d’informations.
