# projet-technologique

## Liste des sujets

- [Dev] ToDo List Web
- [Dev] Petit site de quiz
- [Data] Analyse de résultats sportifs
- [Data] Tableau de bord météo + prévisions
- [Cyber] Générateur de mot de passe
- [Cyber] Monitoring de sécurité réseau


## Explication et attendu

### [Cyber] Monitoring de sécurité réseau

En utilisant grafana, mettre en place un tableau de board de surveillance des informations d'un serveur (Ram, Disque Dur, réseau...)

- Collecte de données système (CPU, RAM, IO…)
- Stockage des données (time series DB type InfluxDB)
- Visualisation (Grafana)

Le projet final montrera dans une page web les données en temps réel (grafana)

### [Cyber] Générateur de mot de passe

Développement d'une application de génération de mot de passe sécurisé (au moins 12 caractères, des minuscules, majuscules, caractères spéciaux). Ajout de recherche de mot de passe connus.

- Création d'une page de login et de register
- Arrivé sur une page pour créer des mots de passe sécurisé
- Chiffrement des mots de passe stockés.
- Analyse de la robustesse des mots de passe (machine learning simple possible).

### [Data] Tableau de bord météo + prévisions

Connexion a une API Méteo et affichage des prévisitions à la journée, à la semaine, avec le choix de la ville.

- Création d'une page de login et de register
- Possibilité de sauvegarder les villes de l'utilisateur
- Page pour afficher la météo dans la ville choisit.

### [Data] Analyse de résultats sportifs

Fichier CSV contenant des résultats de matchs de foot ou de basket :
- Date
- Équipe A
- Équipe B
- Score A / Score B

Travail à faire:
- Calcul des classements
- Nombre de victoires/défaites par équipe
- Séries de victoires consécutives
- Visualisation de la progression de chaque équipe


### [Dev] Petit site de quizz

On veut créer un site web pour des profs qui voudrait proposer un quizz à leur élève.  Trouver des solutions pour minimiser l'utilisation de ChatGPT

- Création d'une page de login et de register
- Si on est prof, on peut créer des quizz, les publier, et correction automatique.
- Si on est élève on peut voir et répondre aux quizz et voir ses résultats lorsqu'ils sont terminé.
- Répondre en un temps définit.


### [Dev] ToDo List Web

On veut créer une application ToDo List, avec des catégories et des statitiques.

- Création d'une page de login et de register
- Gestion des catégories par utilisateur
- Gestion des todos par utilsiateur
- Création d'une page de statistique (https://canvasjs.com/)