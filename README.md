# ManipGit
    Commandes de connexion à Git : 
        git config --global user.name "UserName"
        git config --global user.email "Email"

    Commandes first initialisation projet GIT       
        git init
        git add README.md
        git commit -m "first commit"
        git branch -M main
        git remote add origin https://url projet....
        git push -u origin main

************************** GIT PUSH ***************************************
Une fois que le projet est initialisé : On veut pousser une modif 
        git add README.md / ou nom du fichier
        git commit -m "Firt commit"
        git push -u origin NomBranch


********************************** GIT CLONE ***************************
Si on souhaite récupérer un projet en local
    git init
    git clone url


********************************** Les branches ***************************
   Creer une branche sur le terminal
        git branch NomBranche
    Se positioner sur une branche existante 
        git checkout NomBranche

**************************** Merger les branches ************************
 Pour fusionner des branches localement, utilisez git checkout afin de basculer vers la branche dans laquelle vous souhaitez fusionner. Cette branche est généralement la branche principale, ou main. Ensuite, utilisez git merge et spécifiez le nom de l'autre branche à intégrer à cette branche : 
    git merge nomBranche

**************************** Merger les branches ************************
	git branch -d NomBranch.
	
**************************** delete branch ************************
	git branch -d NomBranch.