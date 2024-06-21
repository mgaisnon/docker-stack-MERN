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

