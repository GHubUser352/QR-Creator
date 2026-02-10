# 🛰️ QR Creator

Une application web moderne, rapide et élégante pour générer des QR Codes haute fidélité. Conçue avec une esthétique "Glassmorphism" et une interface utilisateur réactive, elle permet de transformer divers types de données en codes scannables instantanément.

## ✨ Fonctionnalités

- **🌐 Multi-formats** : Support complet pour :
  - **URL** : Liens web sécurisés (http/https).
  - **VCard** : Cartes de visite numériques avec nom, téléphone et email.
  - **WiFi** : Partage de réseau avec gestion du SSID, mot de passe et sécurité (WPA/WEP).
  - **SMS** : Pré-remplissage de messages avec sélecteur international.
  - **Crypto** : Adresses de portefeuilles (BTC, ETH, USDT, BNB, SOL) avec validation par Regex.
  - **Géolocalisation** : Coordonnées précises avec option "Use my location".
- **🎨 UI/UX Premium** :
  - **Mode Sombre/Clair** adaptatif.
  - **Sélecteur de pays intelligent** avec drapeaux, indicatifs et recherche intégrée.
  - **Validation en temps réel** des champs (bordures dynamiques).
  - **Formatage automatique** des numéros de téléphone selon les standards nationaux.
- **📥 Export & Partage** :
  - Copie directe dans le presse-papier.
  - Téléchargement en formats **PNG** et **SVG**.
  - Intégration de l'API de partage native (`navigator.share`).

## 🛠️ Stack Technique

- **Frontend** : React 18 (via UMD pour une portabilité totale sans build complexe).
- **Style** : Tailwind CSS (Design System Emerald).
- **Moteur QR** : [QRious](https://github.com/neocotic/qrious) (Génération côté client, niveau de correction H).
- **Icons** : Lucide Icons.
- **Typographie** : Plus Jakarta Sans.

## 🚀 Installation & Utilisation

Comme l'application utilise des CDN pour toutes ses dépendances, aucun processus d'installation `npm` n'est requis. 

1. Copiez le code du fichier `index.html`.
2. Ouvrez-le dans n'importe quel navigateur moderne.

## 📱 Aperçu Technique

L'application utilise un système de masquage pour les entrées de données :
- **Patterns Téléphoniques** : `[1, 2, 2, 2, 2]` pour la France, `[3, 3, 4]` pour les USA, etc.
- **Sécurité** : Les données sensibles comme les mots de passe WiFi ou les adresses Crypto sont traitées uniquement en local dans le navigateur.

---
*Développé avec un focus sur la performance et l'élégance.*