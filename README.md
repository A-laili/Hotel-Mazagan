# Application de Gestion d'un Hôtel

## Aperçu

Le Système de Gestion d'Hôtel est une application web construite avec Spring Boot, React + Vite, et JWT Spring Security. Il offre une plateforme pour gérer les opérations hôtelières, y compris les réservations de chambres, les informations sur les clients et les tâches administratives.

## Fonctionnalités

- **Authentification et Autorisation d'Utilisateur :** Sécurisez votre application avec une authentification basée sur JWT et une autorisation utilisant Spring Security.

- **Gestion des Chambres :** Ajoutez, modifiez et supprimez des chambres. Capturez les détails de la chambre tels que le type de chambre, le prix et la disponibilité.

- **Système de Réservation :** Permettez aux clients de réserver des chambres. Gérez et visualisez les détails de réservation, y compris les dates d'arrivée et de départ.

- **Tableau de Bord :** Surveillez les principales métriques et visualisez les données pour une meilleure prise de décision.

## Video démonstrative
- **Mode Client :**


https://github.com/A-laili/Projet_Hotel/assets/147451080/0f0abc75-2f77-4e7c-a664-a459a9ef8c43

- **Mode Admin :**

  




https://github.com/A-laili/Projet_Hotel/assets/147451080/3a01a3db-d68c-4d41-b4ec-aee71268a105









## Technologies Utilisées

- **Backend :**
  - Spring Boot : Framework basé sur Java pour construire des applications backend robustes et évolutives.
  - Spring Security : Gère l'authentification et l'autorisation.
  - JWT (JSON Web Tokens) : Transmettez des informations de manière sécurisée entre les parties.

- **Frontend :**
  - React : Bibliothèque JavaScript pour la construction d'interfaces utilisateur.
  - Vite : Outil de construction rapide pour le développement web moderne.

## Configuration

### Cloner le projet depuis GitHub
git clone https://github.com/A-laili/Projet_Hotel
### Utiliser Docker
- Build the Docker images :
docker-compose build

- Run the Docker containers :
docker-compose up

- Connect to phpMyadmin server on port 8081 ( user:"root"-password:"root") and restart the backend from Docker Desktop
### Utiliser un deploiment local
- cd back-Hotel-MazagaO :
cmd --> mvn clean install
    --> mvn spring-boot:run
- cd hotel-front :
cmd --> npm install
    --> npm run dev
- Ouvrir l'url suivant : http://localhost:5173/









