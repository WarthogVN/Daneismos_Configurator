# Daneismos_Configurator

Objet :
-------
Créer l'application de configuration pour Daneismos.
Cette application permet à un utilisateur néophyte de gérer la configuration de connexion à la base Daneismos.
La configuration est stockée dans le fichier daneismos.json

{
    "database" : "nom de la base",
    "host" : "ip du serveur mysql",
    "user" : "nom utilisateur",
    "password" : "mot de passe",
    "port" : "port du serveur"
}


Utilisation du crate Serde pour la sérialisation/désérialisation au format JSON
Utilisation du crate slint pour la partie UI

Pour l'utilisation du json voir poc_config (https://github.com/WarthogVN/poc_config)
Pour l'utilisation de slint voir poc_slint (https://github.com/WarthogVN/poc_slint)
voir https://github.com/slint-ui/slint/tree/master/examples


