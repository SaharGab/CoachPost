# 🧘‍♂️ Coach Posture – Projet Nuit de l’Info 2024 x Decathlon

Une application web simple et interactive qui aide l’utilisateur à :
- mieux comprendre son **profil sportif**,
- recevoir des **exercices adaptés** à son niveau / objectif,
- visualiser la **bonne posture**,
- découvrir une sélection de **produits Decathlon** en lien avec sa pratique.

---

## 🎯 Objectif du projet

L’objectif est d’accompagner les utilisateurs dans une pratique sportive plus **saine**, **progressive** et **sécurisée**, en limitant les mauvaises postures et les blessures, tout en mettant en avant des produits adaptés (Decathlon).

Ce projet a été réalisé dans le cadre de la **Nuit de l’Info**.

---

## 🧩 Niveaux réalisés

### ✅ Niveau 1 – Profilage Sportif

- Mise en place d’un **QCM** (niveau, sport principal, objectif, douleurs).
- Le formulaire permet de générer un profil comme :
  > "Débutant, objectif remise en forme, douleurs au dos, pratique : aucun sport / running / yoga..."

### ✅ Niveau 2 – Instructions Personnalisées

À partir des réponses :
- Génération de **consignes textuelles** adaptées :
  - exemples : échauffement, séries/reps, tempo, consignes de respiration, variantes selon le niveau.
- Affichage dans une section dédiée : `Tes consignes personnalisées`.

### ✅ Niveau 3 – Illustration & Visualisation

- Affichage d’**illustrations / schémas / images** pour chaque mouvement.
- Mise en forme en cartes (cards) avec :
  - nom de l’exercice,
  - description,
  - visuel (placeholder ou image réelle),
  - conseils posturaux.

### ✅ Niveau 4 – Lien Commercial Pertinent (Bonus)

- Section **“Sélection Decathlon pour toi”** :
  - produits liés au profil (ex : tapis de yoga, bandes de résistance, haltères, rouleau de massage…),
  - chaque carte contient :
    - nom du produit,
    - usage,
    - type de pratique,
    - lien cliquable (placeholder ou lien vers decathlon.fr).

---

## 🏗️ Stack & choix techniques

- **Front-end :**
  - HTML + CSS
  - [Tailwind CSS (CDN)](https://tailwindcss.com/)
- **Aucune base de données / backend** :
  - tout se fait côté navigateur (JavaScript simple).
- **Responsive design** :
  - structure en sections (`hero`, `à propos`, `profil`, `instructions`, `visualisation`, `produits`).

---

## 🚀 Lancer le projet

### 1️⃣ Prérequis

- Un simple navigateur web moderne (Chrome, Firefox, Edge…).
- (Optionnel) L’extension **Live Server** de VS Code pour recharger automatiquement.

### 2️⃣ Installation

```bash
git clone https://github.com/TON_USER/TON_REPO.git
cd TON_REPO
