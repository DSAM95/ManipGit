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
        git push -u origin main


********************************** GIT CLONE ***************************
Si on souhaite récupérer un projet en local
    git init
    git clone url