# VOLA_SKINORDIQUE_CGI_DATA
Ce script python permet de recuperer les données du logiciel VOLA SKI NORDIQUEPRO v12 puis traiter les données de chronometrage afin d'envoyer les données traitées au logiciel d'incrustation TV singular.live

Le script se connecte a la premiere base de donnée de l'epreuve afin de recuperer les informations sur les coureur (dossard, categorie, nom, prenom...) 

Une connection a la seconde base de données de l'epreuve est effectuée pour recuperer tout les temps de chaques athletes. Ces donées sont triées afin de creer des dictionnaire contenant le resultat a chaques intermediares. Les données sont ensuites envoyées a L'API du logiciel singular.live pour realiser les incrustations.

On peur aussi rentrer dans le logiciel un numero de dossard specifique pour recuperer son nom, ses temps de passage, ses penamitées aux tirs et tout les autres informations concernant l'athlete.

Ce logiciel permet de recuperer toutes les impulsions sur les intermediares de chronometrage, les classements a la fin de chaques tir, le classement a l'arrivée et les listes de depart, nom d'epreuve, type de course...



le temps tournant de l'athletes n'est pas encore disponible. A voir dans une prochaine mise a jour 
