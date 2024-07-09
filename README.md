# symfony serve -d

ouvrir le projet sur le localhost:8000

# connexion BD Postgres
Dans xamp, php.ini => décommenter les lignes :
extension=pdo_pgsql
extension=pgsql

créer fichier .env.local pour les données de connexion (DATABASEURL)

test pour vérifier la connexion à la BD :
symfony console doctrine:database:create --if-not-exists