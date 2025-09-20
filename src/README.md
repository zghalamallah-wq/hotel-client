# 🏨 Hotel Client App

Application client d'hôtel moderne développée avec React, TypeScript et Tailwind CSS v4.

## ✨ Fonctionnalités

- 🌍 **Système multilingue** (Français, Anglais, Espagnol, Allemand, Italien)
- 📱 **Interface mobile optimisée** 
- 🔑 **Clé digitale animée** avec QR Code
- 🛎️ **Room Service** avec suivi en temps réel
- ✅ **Check-in/Check-out** simplifié
- 👤 **Profil client** personnalisé
- 💬 **Messagerie concierge** (à venir)

## 🚀 Technologies

- **React 18** + TypeScript
- **Tailwind CSS v4** (dernière version)
- **Vite** (build ultra-rapide)
- **ShadCN/UI** (composants)
- **Lucide React** (icônes)

## 📱 Design

Interface luxueuse avec :
- Branding élégant blanc/noir avec dégradés
- Navigation mobile à 5 icônes
- Animations fluides
- Interface tactile optimisée

## 🛠️ Installation

```bash
# Cloner le projet
git clone [votre-repo]
cd hotel-client-app

# Installer les dépendances
npm install

# Lancer en développement
npm run dev

# Build pour production
npm run build
```

## 📁 Structure

```
src/
├── main.tsx              # Point d'entrée
├── App.tsx               # Application principale
├── components/           # Tous les composants
│   ├── WelcomeScreen.tsx
│   ├── Dashboard.tsx
│   ├── CheckInOut.tsx
│   ├── DigitalKey.tsx
│   ├── RoomService.tsx
│   ├── LanguageSelector.tsx
│   └── ui/               # ShadCN components
└── contexts/
    └── LanguageContext.tsx # Système multilingue
```

## 🌐 Déploiement

Compatible avec :
- **Vercel** (recommandé)
- **Netlify**
- **Firebase Hosting**
- Tout hébergeur statique

## 📄 Licence

MIT License - Voir LICENSE pour plus de détails.