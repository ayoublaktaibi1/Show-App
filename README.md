# ShowApp - Application de Gestion de Films, Séries et Animés

![Bannière ShowApp](assets/banner.png) *(Remplacez par une image représentative de votre application)*

## 📌 Description

ShowApp est une application mobile développée avec **Flutter** qui permet aux utilisateurs de gérer une liste de films, séries et animés. Elle offre des fonctionnalités CRUD (Create, Read, Update, Delete) et interagit avec un backend **Node.js** pour stocker les données. L'application inclut une interface intuitive avec navigation fluide, gestion des images, et authentification utilisateur.

---

## 🎯 Fonctionnalités

### 🔹 Pour les Utilisateurs
- **Connexion/Déconnexion** : Authentification sécurisée via un formulaire.
- **Navigation** : Accès aux différentes sections via un menu latéral et une barre de navigation inférieure.
- **Gestion des Shows** :
  - 📝 Ajouter un nouveau show (titre, description, catégorie, image).
  - 👀 Afficher la liste des shows classés par catégorie (films, animés, séries).
  - ✏️ Modifier un show existant.
  - 🗑️ Supprimer un show avec confirmation.
- **Profil Utilisateur** : Visualiser et mettre à jour les informations du compte.

### 🔹 Pour les Développeurs
- **Backend Node.js** : API RESTful avec Express, SQLite pour la base de données, et Multer pour la gestion des images.
- **État Réactif** : Mise à jour dynamique de l'interface sans rechargement manuel.
- **Sécurité** : Validation des entrées côté serveur et client.

---

## 🛠️ Technologies Utilisées

### 📱 Frontend (Flutter)
- **Flutter** : Framework pour le développement multiplateforme.
- **Packages** :
  - `http` : Pour les requêtes API.
  - `image_picker` : Pour sélectionner des images depuis la galerie ou l'appareil photo.
  - `shared_preferences` : Pour stocker le token d'authentification.

### ⚙️ Backend (Node.js)
- **Express** : Framework pour créer l'API.
- **SQLite** : Base de données légère et portable.
- **Multer** : Middleware pour gérer l'upload des images.
- **CORS** : Autorise les requêtes cross-origin.
- **Dotenv** : Gestion des variables d'environnement.

---

## 🚀 Installation et Exécution

### Prérequis
- Flutter SDK (dernière version stable)
- Node.js (v14 ou supérieur)
- Un émulateur ou un appareil physique pour tester l'application.
