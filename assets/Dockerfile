# Utilisation de l'image de base demandée (version slim pour l'évolution)
FROM nginx:alpine3.23-slim

# Copier tous les fichiers de ton projet vers le dossier de Nginx
# C'est ici que ton site HTML/CSS est injecté dans le serveur
COPY . /usr/share/nginx/html/

# Exposer le port 80 (port standard HTTP)
EXPOSE 80

# Lancer Nginx en mode premier plan
CMD ["nginx", "-g", "daemon off;"]