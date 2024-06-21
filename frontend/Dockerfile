# Utiliser une image de base pour Node.js
FROM node:18-alpine

# Définir le répertoire de travail dans le conteneur
WORKDIR /app

# Copier les fichiers nécessaires
COPY . .

# Installer les dépendances
RUN npm install

# Commande pour démarrer l'application
CMD ["npm", "start"]
