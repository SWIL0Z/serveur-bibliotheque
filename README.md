# Serveur d'une médiathèque
## Projet d'*Application Serveur Java*, réalisé entre décembre 2019 et janvier 2020

### CONTEXTE
Une médiathèque se digitalise et veut mettre en place un service de réservation, d'emprunt, et de retour de ses documents.

### RENDU
La partie serveur est la plus conséquente du projet. Elle utilise une interface contractuelle donnée dans le sujet du projet. J'ai développé la totalité des autres classes.

### BILAN
Ce premier projet exploitant la communication entre applications et la concurrence sur des ressources partagées m'ont permis d'utiliser toutes les notions vues dans ce domaine :
- Utilisation de server-sockets et de sockets pour la communication avec [le client](https://github.com/SWIL0Z/client-mediatheque)
- Mise en place de verrous sur les ressources partagées (les documents)
- Utilisation d'un protocole pour l'envoie de messages par les services (type_du_message$message) et décodé par [le client](https://github.com/SWIL0Z/client-mediatheque)
