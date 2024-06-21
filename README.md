# Objectif du TP

L'objectif de ce TP est de déployer une application web MERN complète utilisant docker compose. Configurez et déployez les services MongoDB pour la base de données, Express pour l'API backend, React pour le frontend, et Nginx pour servir l'application React et faire du reverse proxy vers l'API Express.

## Clonage du depot git

```git clone <URL-du-repository>```
```cd <nom-du-dossier>```

## Construction des conteneurs

```docker compose up --build ```

## Accès au frontend et au backend
- Frontend : localhost/
- Backend : localhost/api
  
(Information : mon backend ne fonctionne pas sur Opera GX, mais fonctionne sur Chrome)

## Résultat
Frontend : 
![image](https://github.com/mgaisnon/docker-stack-MERN/assets/148872982/a9864950-23d0-425a-bf15-d69a3d22bdb0)

Backend : 
![image](https://github.com/mgaisnon/docker-stack-MERN/assets/148872982/61ebdb4c-f409-495c-b9f3-d40961723862)

