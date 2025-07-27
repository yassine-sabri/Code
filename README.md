# SAGECODE

*Transforming Ideas into Innovative Digital Realities*

![Last Commit](https://img.shields.io/badge/last%20commit-last%20sunday-blue)  
![Languages](https://img.shields.io/badge/languages-4-blue)  
![Blade](https://img.shields.io/badge/blade-56.4%25-blue)

---

### 🚀 Built With

![JSON](https://img.shields.io/badge/-JSON-black)
![Markdown](https://img.shields.io/badge/-Markdown-black)
![npm](https://img.shields.io/badge/-npm-red)
![Composer](https://img.shields.io/badge/-Composer-orange)
![JavaScript](https://img.shields.io/badge/-JavaScript-yellow)
![PHP](https://img.shields.io/badge/-PHP-purple)
![Vite](https://img.shields.io/badge/-Vite-blueviolet)
![Tailwind](https://img.shields.io/badge/-Tailwind_CSS-06B6D4)
![Axios](https://img.shields.io/badge/-Axios-purple)

---

## 📚 Overview

**SageCode** est un outil de développement Laravel moderne, intégrant :  
- ⚙️ Une architecture modulaire (routes, sessions, background jobs)  
- 🎨 Une intégration frontend rapide (Vite + Tailwind)  
- 🤖 Une débogage intelligent avec l'API Gemini de Google  
- 💬 Un chatbot AI interactif pour l’assistance au code  
- 🔐 Une gestion sécurisée des utilisateurs  
- 🧠 Une structure simple et adaptée aux développeurs  

---

## ⚙️ Configuration Requise

### 🧪 Environnement

- PHP ≥ 8.1  
- Node.js ≥ 16.x  
- Composer ≥ 2.x  
- npm ≥ 8.x

---

## 🔐 Configuration .env

Ajoute les clés suivantes à ton fichier `.env` pour activer les fonctionnalités AI :

```env
# REQUIRED GEMINI SETTINGS
GEMINI_API_KEY=get_from_google_ai_studio
GEMINI_MODEL=gemini-2.0-flash
GEMINI_MAX_TOKENS=1000


📦 Installation des dépendances

# Installer les packages npm
npm install

# Installer les dépendances PHP
composer install


▶️ Lancer l'application

# Lancer via npm
npm start

# OU via l’entrée PHP (à adapter selon ton point d'entrée)
php [entrypoint]


🧪 Lancer les tests

# Tests JS
npm test

# Tests PHP
vendor/bin/phpunit
