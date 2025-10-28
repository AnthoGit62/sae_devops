# 🎯 SAE DevOps - TryHackMe Rooms Documentation

[![Firebase Hosting](https://img.shields.io/badge/Firebase-Hosting-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://saedevops62.web.app)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Rooms-88cc14?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com)
[![Status](https://img.shields.io/badge/Status-En%20ligne-success?style=for-the-badge)](https://saedevops62.web.app/code/pages/index.html)

## 📋 Description

Projet réalisé dans le cadre de la SAE DevOps, ce site web documente notre parcours d'apprentissage en cybersécurité à travers la plateforme **TryHackMe**. Des explications écrites et des démonstrations vidéo.

**🌐 Site en ligne :** [saedevops62.web.app](https://saedevops62.web.app/code/pages/index.html)

## ✨ Contenu du projet

### 🏆 Rooms TryHackMe

Documentation complète de différentes rooms TryHackMe avec :
- 📝 **Explications écrites** détaillées de chaque étape
- 🎥 **Vidéos de démonstration** pour visualiser les techniques

### 🔐 Configuration VPN TryHackMe

### 🎓 Modules théoriques

#### 👤 Man In The Middle (MITM)
- Concepts fondamentaux des attaques MITM
- Techniques et outils utilisés
- Méthodes de détection et de prévention
- Démonstrations pratiques

#### 🛠️ Living Off The Land (LOTL)
- Introduction aux techniques LOTL
- Utilisation d'outils légitimes du système
- Cas d'usage et scénarios réels
- Stratégies de défense

## 🛠️ Technologies utilisées

### Frontend
- HTML5, CSS3, JavaScript
- Design responsive pour tous les appareils

### DevOps & Hébergement
- **Firebase Hosting** : Hébergement et déploiement
- **GitHub Actions** : CI/CD pour déploiement automatique
- **Git** : Versioning du code

### Outils de cybersécurité
- **TryHackMe** : Plateforme d'apprentissage
- **OpenVPN** : Connexion aux labs TryHackMe
- Divers outils de pentest et d'analyse



## 📁 Structure du projet

```
sae_devops/
├── code/
│   ├── pages/
│   │   ├── index.html              # Page d'accueil
│   │   ├── rooms/                  # Documentation des rooms
│   │   ├── vpn-setup.html          # Guide VPN
│   │   ├── mitm.html               # Module Man In The Middle
│   │   └── lotl.html               # Module Living Off The Land
│   ├── css/
│   │   └── styles.css              # Styles du site
│   ├── js/
│   │   └── main.js                 # Scripts JavaScript
│   ├── assets/
│   │   ├── images/                 # Images et screenshots
│   │   └── videos/                 # Vidéos de démonstration
├── .github/
│   └── workflows/
│       └── firebase-hosting.yml    # Pipeline CI/CD
├── firebase.json                   # Configuration Firebase
├── .firebaserc                     # Projet Firebase
├── .gitignore
└── README.md
```

## 🔄 Pipeline CI/CD

Le projet utilise GitHub Actions pour un déploiement automatique :

1. **Push** vers la branche `main`
2. **Validation** du code HTML/CSS
3. **Build** du projet
4. **Deploy** automatique sur Firebase Hosting
5. **Notification** de succès/échec

## 🎯 Fonctionnalités

- ✅ Navigation intuitive entre les différentes sections
- ✅ Intégration de vidéos explicatives
- ✅ Code snippets avec coloration syntaxique
- ✅ Design responsive (mobile, tablette, desktop)
- ✅ Chargement rapide et optimisé
- ✅ Interface moderne et professionnelle

## 📚 Ressources et références

- [TryHackMe](https://tryhackme.com) - Plateforme d'apprentissage
- [Firebase Hosting Docs](https://firebase.google.com/docs/hosting)
- [OpenVPN](https://openvpn.net/) - Client VPN
- [OWASP](https://owasp.org/) - Ressources de sécurité

## 👨‍💻 Auteurs

**Anthony** - [@AnthoGit62](https://github.com/AnthoGit62)
**Nolan** - [@NolanGGT](https://github.com/NolanGGT)
**Dracodyk** - [@Dacodik](https://github.com/Dacodik)

*Projet réalisé dans le cadre de la SAE DevOps*

## 🔒 Avertissement

Ce projet est à des fins éducatives uniquement. Les techniques présentées doivent être utilisées de manière éthique et légale, uniquement sur des systèmes pour lesquels vous avez l'autorisation explicite.

## 📧 Contact

Pour toute question concernant le projet :
- Ouvrir une issue sur GitHub
- Contacter via le profil GitHub

---

⭐ Si ce projet vous a aidé dans votre apprentissage, n'hésitez pas à lui donner une étoile !

🔐 **Happy Hacking!** (Ethically, of course 😉)
