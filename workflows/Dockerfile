# Utilisez une image de base
FROM node:18

# Définissez le répertoire de travail dans le conteneur
WORKDIR /app

# Copiez les fichiers package.json et package-lock.json
COPY package*.json ./

# Installez les dépendances
RUN npm install

# Copiez le reste des fichiers du projet
COPY . .

# Exposez le port sur lequel votre application s'exécute
EXPOSE 3000

# Commande de démarrage de l'application
CMD ["npm", "start"]

