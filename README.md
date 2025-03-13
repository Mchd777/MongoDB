Projet de Gestion des Tâches
Description
Ce projet est une petite API pour gérer des tâches. On peut ajouter, voir, modifier et supprimer des tâches.

Outils utilisés
Node.js
Express.js
MongoDB

git clone https://github.com/ton-utilisateur/nom-du-repo.git
cd nom-du-repo

Installer les outils nécessaires
npm install
Lancer le projet
node index.js
Le projet fonctionne sur http://localhost:3000.

Routes API
POST /tasks	Ajouter une nouvelle tâche

GET /tasks	Voir toutes les tâches

GET /tasks/:id	Voir une tâche avec son ID

PUT /tasks/:id	Modifier une tâche existante

DELETE /tasks/:id	Supprimer une tâche
