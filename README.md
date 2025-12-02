# Universalis-Exposed

## I. Outils nécessaires:
Logiciel de prise de note "Obsidian"
1. télécharger https://obsidian.md/download

Système de synchronisation des sources "Git":
2. télécharger https://git-scm.com/install/windows (cliquer sur suivant/ok tout le long de l'installateur)

3. Se créer un compte sur https://github.com/
4. Communiquer l'email et le nom d'utilisateur à kokodelo974@gmail.com (ou autre canal) pour recevoir une invitation au projet
5. Une fois l'invitation reçue, accepter. En attendant on devrait pouvoir faire les étapes jusqu'à la **II.4**, 

## II. Récupérer le projet et sa synchronisation:

1. Créer un répertoire de qui accueillera le "Vault Obsidian" (*coffre fort*) dans Windows, dans "Mes Documents" et l'appeler "Obsidian Vaults" (**par exemple**)
2. Ouvrir le répertoire créé et effectuer un "clic droit" -> "open git bash here" (*sur Windows 11+, il faut faire "shift + clic droit" ou "clic droit" -> "Afficher d'autres options" pour avoir l'option disponible. Cette option est disponible car on l'a ajouté durant l'installation de Git*). On vient d'ouvrir un invité de commande de type "git bash".
![[open_git_bash.png]]
 
3. Dans la fenêtre qui s'est ouverte, copier coller les 2 commandes suivantes et les exécuter une à une en remplaçant les valeur entre **-VALEUR A REMPLACER-** (en supprimant les - -). Il est préférable d'utiliser le nom d'utilisateur et l'email utilisés lors de l'inscription sur Github
	1. git config --global user.name "**-UN NOM D'UTILISATEUR-**"
	2. git config --global user.email "**-UN@EMAIL-**"
4. Lancer la commande:
	1. git clone https://github.com/Kokodelo974/Universalis-Exposed.git
	Normalement on a désormais dans notre coffre fort Obsidian un nouveau répertoire "Universalis-Exposed" avec du contenu à l'intérieur: les sources du projet.

## III. Ouvrir le projet

1. Lancer Obsidian
2. Dans la fenêtre qui s'ouvre, sélectionner l'option "Open folder as vault" ou "Ouvrir un dossier comme coffre" et sélectionner le répertoire créé lors du clonage des sources: *Universalis-Exposed*.
   ![[open_as_vault.png]]
3. Une fenêtre s'ouvre, il faut confirmer que l'on fait confiance aux plugins communautaires du projet. Ils seront commun à tous pour que l'on puisse profiter du même point de vu.
![[activate_plugins.png]]

## IV. Faire sa première modification

On est presque près à modifier et synchroniser le projet.
1. Cliquer sur le bouton "Open Git Source control" sur la gauche 
   ![[open_git_source_control.png]]
2. Cela va ouvrir le panneau latéral droit sur l'onglet Git, il ne répertorie aucun changement sur les notes pour le moment
   ![[git_control.png]]
3. Ajouter son pseudo a la partie suivante et le fichier README (ce fichier) devrait apparaitre dans la liste des changement.
   
4. On peut alors modifier le message du "commit" qui est par défaut "vault backup: {{date}}" et "commit" ces changements avec le 2eme bouton représenté par une coche "V". On a ensuite un message nous informant qu'on a bien "commit" un fichier.
![[git_commit.png]]
5. Il faut ensuite "push" ces changements pour qu'ils soient effectifs avec la flèche vers le haut. Le même type de message que précédemment nous informe que l'on a bien "push" notre fichier 
![[Pasted image 20251202202402.png]]

VOILA.


## Ultra Users

1. Kokodelo974
