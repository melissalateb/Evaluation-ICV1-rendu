# Evaluation-ICV1-rendu

# Exercice 1: Etapes
1 - Ajout des Dockerfiles pour chacun des seveurs planner & worker
2 - Ajout du fichier docker-compose afin de lancer planner et worker via docker
3 - Lancer les commandes --> 
        # Dans le répertoire principal où se trouvent les dossiers planner et worker
        docker-compose build
        docker-compose up
4 - Modification du nombre de tache a lancer dans le main 20 --> 4
# Exercice 2: Etapes
1 - Modification de la ligne 12 pour ajouter une adress du worker : let workers = ['http://localhost:8080']
2 - Execution du script './connect.sh 8080 8070' pour pouvoir ajouter des workers 
# Exercice 4: Etapes
1 - Ajout du parametre type pour chaque worker pour pouvoir affilier chaque opération avec un worker
2 - Ajout de plusieurs conditions et plusieurs vérificatios pour filtrer le type de tache pour chaque worker