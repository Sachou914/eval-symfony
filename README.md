
# JobStep – Plateforme de suivi de parcours professionnel

## 🎯 Objectif
Application Symfony 7 permettant d'accompagner des candidats dans leur reconversion professionnelle avec un système de parcours, ressources, rendus, messagerie et gestion de rôles.

---

Le site est hébergé sur alwaysdata à l'adresse suivante : http://sacha-cle.alwaysdata.net/evaluation/

## ✅ Fonctionnalités réalisées

### 🧱 Entités créées
- [x] User
- [x] Ressource
- [x] Message
- [x] Parcours
- [x] Etape
- [x] RenduActivite

---

### 🔐 Sécurité
- [x] Authentification (login)
- [x] Enregistrement (register)
- [x] Seul un **conseiller** peut :
  - créer un parcours
  - créer une étape
  - créer une ressource
- [x] Seul un **conseiller** peut se déclarer accompagnateur d’un candidat

---

### 🛠️ CRUD (création, lecture, mise à jour, suppression)
- [x] Ressource (conseiller uniquement)
- [x] Message (entre utilisateurs)
- [x] Parcours (conseiller uniquement)
- [x] Etape (conseiller uniquement)
- [x] Rendu (candidat uniquement)

---

### ✉️ Messagerie
- [x] Un message peut être envoyé entre deux utilisateurs
- [x] L’émetteur d’un message est automatiquement le user connecté
- [x] L’interface est personnalisée et empêche l’envoi à soi-même

---

### 📊 Tableau de bord "Mon Parcours"
- [x] Affiche les étapes du parcours du candidat
- [] Chaque étape liste ses ressources avec lien de téléchargement
- [] Affiche le dernier rendu du user connecté
- [x] Mini formulaire pour uploader un rendu d’activité
- [] Si un message est lié à un rendu, un lien vers ce message est proposé
- x] Le parcours affiché est bien le **parcours assigné au candidat connecté**

---
