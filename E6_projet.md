Mattéo Pitaval 


Elsan est un groupe d'hospitalisation privé en France, Il y a 217 établissement Elsan, le groupe compte 28 000 collaborateurs


Contexte
Besoins
Objectifs
Fonctions
Synoptique


Contexte : 
les informations sont parfois manquantes ou incomplètes ;
retrouver un article ou son historique est long et compliqué ;
il n’y a pas de traçabilité des entrées et sorties (qui a pris quoi, quand) ;
les erreurs de saisie sont fréquentes, et aucune alerte ne prévient d’une rupture de stock ;
plusieurs personnes ne peuvent pas travailler en même temps sans risque de conflit de versions.

Besoins : 

Besoins utilisateurs :
Consulter rapidement le stock et rechercher un article.
Enregistrer les entrées et sorties simplement, sans tout saisir à la main.
Être prévenu quand un article passe sous un seuil minimum.
Retrouver l’historique des mouvements.

Besoins du responsable :
Contrôler les accès (qui peut modifier ou seulement consulter).
Avoir une vue d’ensemble fiable pour anticiper les commandes.
Exporter les données (par exemple en CSV) pour les inventaires.

Besoins techniques :
Une base de données SQL centralisée.
Une interface web accessible depuis le réseau interne.
Un module de lecture de codes-barres autonome, communiquant en Wi-Fi.
Une authentification sécurisée (mots de passe hachés, sessions).


Objectifs : 

Centraliser toutes les données de stock dans une base SQL unique et fiable.
Fiabiliser la saisie en scannant les articles au lieu de les taper.
Tracer chaque mouvement (utilisateur, date, quantité, type).
Anticiper les ruptures grâce à des alertes de stock bas.
Gagner du temps dans la recherche et la gestion quotidienne.
Sécuriser l’accès par un système de comptes et de rôles.

Fonctions :

-Authentification 
-Gestion des articles
-Gestion des mouvements
-Recherche et filtres
-Scan par ESP32-CAM
-Alerte stock bas
-Tableau de bord
-Export excel


Synoptique :



