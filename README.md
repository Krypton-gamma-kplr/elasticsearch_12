# elasticsearch_12

Exemple de recherche de mots dans une base de données de livre.
Pour lancer le programme :

docker-compose up -d --build

docker exec gs-api "node" "server/load_data.js"

puis aller sur le lien port 8080