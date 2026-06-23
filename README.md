# 📋 Politique de confidentialité de Buzzer
*Dernière mise à jour : juin 2026*

Buzzer ("l'application") est développée par Evan ("le développeur"). Cette politique explique quelles données sont collectées lors de l'utilisation de l'application et comment elles sont traitées.

## 1️⃣ Données collectées
L'application collecte les données suivantes :
- **Pseudo et identifiant utilisateur** : généré via Firebase Authentication (connexion anonyme automatique, aucun email ni mot de passe requis)
- **Données de jeu** : pseudo, tag, avatar choisi, liste d'amis, scores et historique de parties, stockés via Firebase Realtime Database
- **Messages** : les messages échangés dans le chat de partie sont stockés temporairement le temps de la session de jeu
- **Historique d'achat** : si vous achetez "Buzzer+", la transaction est traitée par Google Play Billing puis vérifiée par notre fonction serveur sécurisée (Supabase) pour activer le contenu débloqué
- **Identifiants publicitaires et données de diagnostic** : collectés par Google AdMob pour l'affichage de publicités et la prévention de la fraude

## 2️⃣ Utilisation des données
Ces données sont utilisées exclusivement pour :
- Faire fonctionner les fonctionnalités de jeu (parties, amis, scores)
- Activer le contenu premium après vérification d'un achat légitime
- Afficher des publicités via Google AdMob et prévenir la fraude publicitaire

**Nous ne vendons aucune donnée personnelle à des tiers.**

## 3️⃣ Partage des données avec des tiers
Certaines données sont partagées avec les prestataires suivants, nécessaires au fonctionnement de l'application :
- **Google Firebase** (authentification et base de données)
- **Google AdMob** (affichage de publicités, identifiant publicitaire, diagnostics)
- **Google Play Billing** (traitement des achats intégrés)
- **Supabase** (vérification serveur des achats)

## 4️⃣ Conservation et suppression des données
Les données sont conservées tant que votre profil existe. Pour demander la suppression de vos données personnelles, contactez le développeur (voir section 8) : nous traiterons votre demande dans un délai raisonnable.

## 5️⃣ Sécurité
Toutes les données transitent de manière chiffrée (TLS) entre l'application et nos serveurs.

## 6️⃣ Enfants
Buzzer n'est pas spécifiquement destinée aux enfants de moins de 13 ans et ne collecte pas sciemment de données auprès de ce public.

## 7️⃣ Modifications de cette politique
Cette politique peut être mise à jour. Toute modification importante sera reflétée sur cette page avec une nouvelle date de mise à jour.

## 8️⃣ Contact
Pour toute question relative à cette politique ou à vos données, contactez : **Evan.BARREIROS.pro@gmail.com**
