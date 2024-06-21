# Utiliser une image de base pour Node.js
FROM node:18-alpine

# Définir le répertoire de travail dans le conteneur
WORKDIR /backend

# Copier les fichiers nécessaires
COPY . .

# Installer les dépendances
RUN npm install

# Commande pour démarrer l'application
CMD ["node", "index.js"]
