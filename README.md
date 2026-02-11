# 🛰️ QR Creator - Premium Edition

QR Creator est une application web de **nouvelle génération**, ultra-rapide et élégante, permettant de générer des **QR Codes haute fidélité** en un instant. Conçue avec une esthétique **Glassmorphism** et optimisée pour desktop & mobile, elle transforme vos données en codes scannables **sans jamais les envoyer sur un serveur**.

![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-orange.svg)
![React](https://img.shields.io/badge/React-18.x-blue)
![Tailwind](https://img.shields.io/badge/Tailwind-3.x-cyan)
![QRious](https://img.shields.io/badge/QRious-4.0.2-green)
![Single File](https://img.shields.io/badge/Single%20File-100%25-purple)

---

## ✨ Fonctionnalités Avancées

### 🌐 **6 Formats QR Intelligents**

| Type | Description | Cas d'usage |
|------|-------------|-------------|
| **🔗 URL** | 7 protocoles (https, http, ftp, ftps, mailto, tel, sms) | Sites web, emails, appels directs |
| **👤 vCard** | Carte de visite digitale complète | Networking, events professionnels |
| **📡 WiFi** | 5 types de sécurité (WPA, WPA2, WPA3, WEP, Open) | Partage réseau instantané |
| **💬 SMS** | Message pré-rempli avec 150+ indicatifs pays | Marketing, confirmations |
| **💰 Crypto** | 12 blockchains (BTC, ETH, SOL, XRP, ADA, DOGE, TRX, DOT, LTC, AVAX...) | Paiements crypto, donations |
| **📍 Geo** | Coordonnées GPS **OU** adresse textuelle | Points de rendez-vous, navigation |

### 🎨 **UI/UX Premium**

- **🌓 Thème Dynamique** : Bascule instantanée Dark Mode (Deep Emerald) ↔ Light Mode
- **🌍 150+ Pays** : Sélecteur avec drapeaux HD, recherche instantanée et indicatifs téléphoniques
- **✉️ 15 Fournisseurs Email** : Gmail, Outlook, Proton, Tutanota, iCloud, Yahoo, AOL...
- **⌨️ Navigation Clavier** : Arrow keys (↑↓), Enter, Escape, Home, End dans tous les menus
- **✅ Validation Temps Réel** : Bordures colorées (vert/rouge) avec regex strictes
- **📱 Responsive Mobile** : Interface adaptive pour smartphones & tablettes

### 🔒 **Sécurité & Confidentialité**

- ✅ **0% Cloud** : Toutes les données restent dans votre navigateur
- ✅ **Pas de trackers** : Aucune analytics, aucun cookie
- ✅ **Offline-ready** : Fonctionne sans connexion internet (après 1er chargement)
- ✅ **Open Source** : Code auditable en un seul fichier HTML

### 📥 **Export & Partage Natif**

- **PNG** : Téléchargement haute résolution (600x600px, Level H)
- **SVG** : Format vectoriel pour impression professionnelle
- **📋 Clipboard** : Copie directe de l'image (Ctrl+V dans n'importe quelle app)
- **🔗 Web Share API** : Partage mobile natif (WhatsApp, Instagram, Email...)

---

## 🛠️ Stack Technique

| Composant | Version | CDN |
|-----------|---------|-----|
| **React** | 18.x Production | unpkg.com |
| **React DOM** | 18.x Production | unpkg.com |
| **Babel Standalone** | Latest | unpkg.com |
| **Tailwind CSS** | 3.x | cdn.tailwindcss.com |
| **QRious** | 4.0.2 | cdnjs.cloudflare.com |
| **Lucide Icons** | Latest | unpkg.com |
| **Google Fonts** | Plus Jakarta Sans | fonts.googleapis.com |

**Architecture** :
- **Single-File App** : 100% du code dans un seul `index.html` (2629 lignes)
- **Pas de build** : Aucun webpack, vite, npm, node_modules requis
- **Production-Ready** : React en mode production (minifié)

---

## 🚀 Installation & Déploiement

### **Option 1 : Utilisation Locale**
```bash
# Télécharger le fichier
curl -O https://raw.githubusercontent.com/GHubUser352/qr-creator/main/index.html

# Ouvrir dans le navigateur
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### **Option 2 : Déploiement GitHub Pages**
1. Créer un repo `qr-creator`
2. Upload `index.html`
3. Settings → Pages → Branch: `main` → Save
4. Accéder via `https://username.github.io/qr-creator/`

### **Option 3 : Netlify Drop**
1. Glisser `index.html` sur [app.netlify.com/drop](https://app.netlify.com/drop)
2. Site live en < 10 secondes

### **Option 4 : Vercel**
```bash
vercel --prod index.html
```

---

## 📖 Guide d'utilisation

### **Générer un QR Code URL**
1. Sélectionner l'onglet **QRWeb**
2. Choisir le protocole (`https://`, `mailto:`, `tel:`, etc.)
3. Entrer la destination (ex: `google.com`, `contact@example.com`, `+33612345678`)
4. Le QR s'affiche instantanément
5. Cliquer **Download PNG** ou **Copy** pour partager

### **Créer une carte de visite (vCard)**
1. Onglet **QRCard**
2. Remplir : Prénom, Nom, Téléphone (avec indicatif pays), Email
3. Scanner le QR → Le contact s'ajoute automatiquement au téléphone

### **Partager un réseau WiFi**
1. Onglet **QRWiFi**
2. Entrer SSID, mot de passe, type de sécurité (WPA2/WPA3 recommandé)
3. Partager le QR → Connexion en 1 scan (iOS 11+, Android 10+)

### **Envoyer une demande de paiement crypto**
1. Onglet **QRCrypto**
2. Sélectionner la blockchain (Bitcoin, Ethereum, Solana...)
3. Coller l'adresse wallet (validation automatique)
4. (Optionnel) Montant
5. Scanner le QR → Ouvre l'app wallet avec pré-remplissage

### **Partager une localisation**
1. Onglet **QRGeo**
2. **Mode Coordinates** : Entrer Lat/Long ou cliquer "Use my location"
3. **Mode Address** : Taper l'adresse complète (ex: "10 Downing Street, London, UK")
4. Scanner le QR → Ouvre Google Maps/Apple Plans

---

## ⚙️ Fonctionnalités Avancées

### **Sélecteur de Pays avec Recherche**
- **150+ pays** avec drapeaux (flagcdn.com)
- **Recherche temps réel** : Taper "fra" → France, "jap" → Japan
- **Navigation clavier** : ↑↓ pour naviguer, Enter pour sélectionner
- **Formatage automatique** : Les numéros s'adaptent au pattern du pays

### **Validation Blockchain**
| Crypto | Format validé | Exemple |
|--------|---------------|---------|
| Bitcoin | bc1... / 1... / 3... | `bc1qxy2kgdygjrsqtzq2n0yrf2493p83kkfjhx0wlh` |
| Ethereum | 0x[40 hex] | `0x742d35Cc6634C0532925a3b844Bc9e7595f0bEb` |
| Solana | Base58 32-44 | `7xKXtg2CW87d97TXJSDpbD5jBkheTqA83TZRuJosgAsU` |
| XRP | r[24-34 chars] | `rN7n7otQDd6FczFgLdSqtcsAUxDkw6fzRH` |
| Cardano | addr1... | `addr1qxy2kgdygjrsqtzq2n0yrf2493p83kkfjhx0wlh...` |

### **Modes Géolocalisation**
```
Mode Coordinates:
geo:48.8566,2.3522?q=48.8566,2.3522(Tour Eiffel)

Mode Address:
geo:0,0?q=10+Downing+Street,+London,+UK
```

---

## 🎨 Personnalisation

### **Modifier les couleurs**
Ligne 1955 dans `index.html` :
```javascript
foreground: "#000000", // Couleur du QR Code
background: "#ffffff", // Couleur de Fond
```

### **Ajouter un pays**
Ligne 321 dans `COUNTRY_DATA` :
```javascript
"+33": { 
  flag: "fr", 
  label: "(+33) France", 
  shortLabel: "France", 
  max: 9, 
  placeholder: "X XX XX XX XX", 
  pattern: [1, 2, 2, 2, 2] 
},
```

### **Ajouter un fournisseur email**
Ligne 2030 dans `emailDomainOptions` :
```javascript
{ value: "@custom.com", label: "@custom.com" },
```

---

## 🐛 Dépannage

### **Le QR ne s'affiche pas**
- Vérifier la console (F12) pour les erreurs
- Confirmer que les CDNs sont accessibles (connexion internet)
- Vider le cache navigateur (Ctrl+Shift+R)

### **"Download PNG" ne fonctionne pas**
- Vérifier que le QR est généré (border verte)
- Essayer "Copy" puis Ctrl+V dans Paint/Photoshop
- Utiliser un navigateur moderne (Chrome 90+, Firefox 88+, Safari 14+)

### **Erreurs VSCode (page blanche localement)**
- Les erreurs TypeScript dans VSCode sont normales (JSX dans HTML)
- Le fichier fonctionne parfaitement dans le navigateur
- Ignorer ou désactiver validation JS : Settings → `"javascript.validate.enable": false`

---

## 📜 Licence

Ce projet est sous licence **Creative Commons Attribution - Pas d'Utilisation Commerciale 4.0 International (CC BY-NC 4.0)**.

### ✅ **Vous POUVEZ** :
- ✅ Utiliser gratuitement
- ✅ Modifier le code
- ✅ Partager avec attribution
- ✅ Forker sur GitHub
- ✅ Utiliser en interne (entreprise, école, ONG)

### ❌ **Vous NE POUVEZ PAS** :
- ❌ Vendre l'application
- ❌ Intégrer dans un service payant
- ❌ Retirer le crédit "GHubUser352"
- ❌ Distribuer sans licence

**Voir [LICENSE](LICENSE) pour les détails complets.**

---

## 🤝 Contribution

Les contributions sont les bienvenues ! 

1. Fork le projet
2. Créer une branche feature (`git checkout -b feature/AmazingFeature`)
3. Commit les changements (`git commit -m 'Add AmazingFeature'`)
4. Push (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

**Guidelines** :
- Code en anglais, commentaires en français acceptés
- Respecter la structure single-file (pas de npm, webpack, etc.)
- Tester sur Chrome, Firefox, Safari avant PR

---

## 🙏 Remerciements

- **QRious** : Moteur QR ultra-léger
- **Lucide** : Icons magnifiques
- **Tailwind** : Design system moderne
- **FlagCDN** : Drapeaux HD gratuits
- **Communauté React** : Pour l'écosystème incroyable

---

## 📞 Contact & Support

- **GitHub** : [@GHubUser352](https://github.com/GHubUser352)
- **Issues** : [github.com/GHubUser352/qr-creator/issues](https://github.com/GHubUser352/qr-creator/issues)
- **Discussions** : [github.com/GHubUser352/qr-creator/discussions](https://github.com/GHubUser352/qr-creator/discussions)

---

<div align="center">

**⭐ Si ce projet vous est utile, n'hésitez pas à lui donner une étoile ! ⭐**

*Fait avec 💚 en France • Focus sur la performance, la confidentialité et l'élégance*

</div>
