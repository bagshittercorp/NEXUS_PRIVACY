# NEXUS_PRIVACY // DIGITAL RESISTANCE KIT

```text
  _   _  _______  __  _   _  ____  
 | \ | || ____\ \/ / | | | |/ ___| 
 |  \| ||  _|  \  /  | | | |\___ \ 
 | |\  || |___ /  \  | |_| | ___) |
 |_| \_||_____/_/\_\  \___/ |____/ 
                                   
 [ SYSTEM STATUS: ONLINE ]
 [ PROTOCOL: ZERO_KNOWLEDGE ]
```

> **"Pas de logs. Pas de maîtres. Combattez la machine."**

## 💀 MANIFESTE

**NEXUS_PRIVACY** est une suite d'outils web légers, autonomes et exécutés entièrement côté client (Client-Side). Conçue pour les activistes, les journalistes et toute personne soucieuse de sa vie privée dans un environnement de surveillance de masse.

🔒 **Aucune donnée n'est envoyée à un serveur.** Tout le traitement (chiffrement, nettoyage, stéganographie) se fait localement dans votre navigateur.

---

## 🛠️ ARSENAL (MODULES)

Le kit comprend 4 protocoles distincts accessibles via le Dashboard `index.html` :

### 1. DEAD_DROP // Stéganographie
*   **Fichier :** `deaddropsteganography.html`
*   **Fonction :** Dissimulation de messages textuels à l'intérieur d'images PNG via la méthode LSB (Least Significant Bit).
*   **Usage :** Communication secrète invisible à l'œil nu.
*   **Capacité :** Chiffrement XOR léger intégré avant injection.

### 2. CRYPTO_VAULT // Chiffrement de Fichiers
*   **Fichier :** `fileencryptor.html`
*   **Fonction :** Chiffrement de fichiers locaux (n'importe quel format) via **AES-GCM-256**.
*   **Usage :** Sécurisation de documents sensibles avant stockage ou envoi.
*   **Tech :** Utilise l'API Web Crypto native du navigateur (PBKDF2 pour la dérivation de clé).

### 3. LINK_DETOX // Nettoyage d'URL
*   **Fichier :** `linkdetoxtool.html`
*   **Fonction :** Suppression des paramètres de pistage (UTM, Facebook Click ID, Google Analytics).
*   **Usage :** Partage de liens propres sans alimenter le capitalisme de surveillance.
*   **Modes :** Chirurgical (liste noire connue) ou Agressif (suppression totale des paramètres).

### 4. META_WIPE // Anonymisation d'Images
*   **Fichier :** `metadatawipertool.html`
*   **Fonction :** Reconstruction de l'image pixel par pixel pour éliminer toutes les métadonnées (EXIF, GPS, Modèle appareil, Date).
*   **Usage :** Publication de photos sans révéler votre localisation ou votre identité numérique.

---

## 🚀 DÉPLOIEMENT

Aucune installation complexe, aucun `npm install`, aucune base de données.

1.  **Cloner le dépôt :**
    ```bash
    git clone https://github.com/VOTRE_NOM/nexus-privacy.git
    ```
2.  **Lancer :**
    Ouvrez simplement le fichier `index.html` dans n'importe quel navigateur web moderne.

### ⚠️ Note sur l'utilisation Hors-Ligne (Air-Gap)
Les outils utilisent **Tailwind CSS** via un CDN pour le style.
*   **En ligne :** Fonctionne immédiatement.
*   **Hors ligne (Air-Gap) :** Pour une sécurité maximale sur une machine déconnectée, vous devez télécharger le script Tailwind ou compiler le CSS localement.

---

## ⚖️ AVERTISSEMENT LÉGAL

Ce logiciel est fourni à des fins éducatives et de protection personnelle.
L'auteur décline toute responsabilité quant à l'utilisation de ces outils. Le chiffrement est robuste, mais la sécurité dépend aussi de la force de vos mots de passe et de l'intégrité de votre machine.

---

## 🤝 CONTRIBUTION

Les Pull Requests sont les bienvenues.
*   Optimisation des algorithmes.
*   Nouveaux modules de résistance.
*   Traductions.

---

<p align="center">
  <img src="https://img.shields.io/badge/SECURITY-CLIENT_SIDE-green?style=for-the-badge&logo=shield" alt="Client Side Security">
  <img src="https://img.shields.io/badge/TRACKING-DISABLED-red?style=for-the-badge" alt="No Tracking">
</p>
