<div align="center">
  <img src="assets/images/Buzzer.png" alt="Buzzer Logo" width="120"/>
  
  # ⚡ Buzzer
  
  **L'application de jeu de buzzer multijoueur en temps réel**
  
  ![Flutter](https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter)
  ![Firebase](https://img.shields.io/badge/Firebase-Realtime%20DB-orange?logo=firebase)
  ![Version](https://img.shields.io/badge/version-3.1.0-purple)
  ![Platform](https://img.shields.io/badge/platform-Android-green?logo=android)
</div>

---

## 📱 C'est quoi Buzzer ?

Buzzer est une application Android multijoueur qui transforme n'importe quelle soirée en jeu de quiz interactif. Crée une partie, invite tes amis avec un code, et que le meilleur gagne !

---

## 🎮 Modes de jeu

| Mode | Description |
|------|-------------|
| ⚡ **Classique** | Premier à buzzer remporte le point |
| ⏱️ **Chrono caché** | Le chrono tourne en secret, timing parfait requis |
| 🌀 **Crazy Countdown** | Compte à rebours avec des règles qui changent |
| ❓ **Questions / Réponses** | Quiz en équipe avec validation par l'hôte |

---

## ✨ Fonctionnalités

- 🔴 **Buzzer en temps réel** via Firebase Realtime Database
- 👥 **Multijoueur** — jusqu'à plusieurs joueurs dans la même partie
- 🏠 **Lobby** — rejoins une partie avec un code à 6 caractères
- 🧑‍🎤 **Avatars personnalisés** — 16 personnages au choix, sauvegardés localement
- 👫 **Système d'amis** — ajoute des amis, vois qui est en ligne
- 🔊 **Effets sonores** — sons de buzz et de victoire
- 📊 **Scores en direct** — classement mis à jour en temps réel

---

## ❓ Mode Questions / Réponses

Le mode QnA est le plus complet de l'application :

- **6 listes prêtes à jouer** : Culture générale, Science, Sport, Cinéma & Séries, Histoire, Géographie
- **🤖 Génération IA** : entre un thème libre (*Harry Potter, la cuisine française, les années 90...*) et l'IA génère 10 questions instantanément
- **🙈 Anti-triche** : la question disparaît dès qu'un joueur buzz, impossible de lire la réponse avant de répondre
- **✏️ Liste personnalisée** : crée tes propres questions/réponses
- **🎙️ Saisie manuelle** : pose tes questions à la volée
- **🔒 Réponse visible uniquement par l'hôte** pour valider ou invalider

---

## 🚀 Installation

### Télécharger l'APK
👉 [Dernière release](../../releases/latest) — télécharge le fichier `.apk` et installe-le sur ton Android.

> Active **"Sources inconnues"** dans les paramètres de sécurité de ton téléphone si besoin.

### Compiler depuis les sources

```bash
