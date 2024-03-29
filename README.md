# requêteSQL

## Entrez votre requête SQL :

Les utilisateurs peuvent saisir leur requête SQL dans la zone de texte fournie.

## Exécuter la requête :

Lorsque les utilisateurs cliquent sur le bouton "Exécuter la requête", la page envoie la requête SQL saisie à un serveur PHP pour le traitement.

## Traitement PHP :

Le serveur PHP récupère la requête SQL saisie par l'utilisateur. Il effectue une connexion à une base de données MySQL en utilisant les informations de connexion spécifiées (adresse du serveur, nom d'utilisateur, mot de passe et nom de la base de données). La requête SQL est exécutée sur la base de données. Si la requête est validée et renvoie des résultats, elle est enregistrée dans un fichier "historique.txt" avec la date et l'heure de son exécution. Les résultats de la requête sont affichés dans un tableau HTML sur la page Web, avec les noms des colonnes et les données associées.

## Historique des requêtes :

Les utilisateurs peuvent afficher l'historique des requêtes précédentes en cliquant sur le bouton "Historique". Lorsque ce bouton est cliqué, la page charge le contenu du fichier "historique.txt" via AJAX et l'affiche dans une fenêtre contextuelle. Chaque requête précédente est affichée sous forme de liste dans cette fenêtre contextuelle.

## Voir l'historique :

Les utilisateurs peuvent vider l'historique des requêtes précédentes en cliquant sur le bouton "Vider l'historique". Cela efface le contenu du fichier "historique.txt", supprimant ainsi toutes les requêtes enregistrées précédemment.

En résumé, cette page Web offre aux utilisateurs un moyen pratique d'envoyer des requêtes SQL à une base de données, de visualiser les résultats de ces requêtes, de consulter l'historique des requêtes précédentes et de vider cet historique au besoin.
