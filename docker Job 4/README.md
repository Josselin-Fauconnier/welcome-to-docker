# Docker Job 4 : Dockerfile Apache & PHP

Exercice job 4



## Étapes Réalisées

### 1. Construction de l'image (Build)
Commande utilisée : `docker build -t job4-app .`

![Construction de l'image](./créer%20image%20.png)

### 2. Lancement du Conteneur (Run)
Commande utilisée : `docker run -d -p 8080:80 job4-app`

![Lancement du conteneur](./conteneur%20lancer.png)

### 3. Résultat
Accès à la page via `http://localhost:8080`.

![Page PHP Info](./php%20info.png)

### 4. Gestion et Arrêt
Arrêt du conteneur.

![Arrêt du conteneur](./stop%20.png)
