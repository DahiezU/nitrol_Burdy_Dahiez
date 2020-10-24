# Liste des scénarios d'application :
1. **Scénario : Louer un oeuvre :** 
    -   description : le membre peut aller enprunter une oeuvre non libre de droit dans un un des repertoires propsé, à un prix fixé, pour un temps fixé
    - liste des acteurs : le loueur et le client.
    - prérequis : une oeurvre privé, etre un membre, disponiblité de l'oeuvre.
    -  données: 
        - données rentré: paiment et contrepartie.
        - données sortie: Oeuvre.
    - Etapes :
        - se rendre sur le site. 
        - se connecter ou s'inscrire.
        - choisir une oeuvre dans la liste des oeuvres disponible non libre de droit.
        - cliquer sur louer l'oeuvre.

    - Exception :
        - Oeuvre plus disponible.
    - Descriptions : 

2. **Scénario : Enprunter oeuvre**
    - description : je peux avoir accés à une oeuvre publique temporairement  de n'importe quels répertoire public (musique, livre , vidéo)
    - acteurs : utilisateur et admin  
    - prérequis : Il faut etre membre et que l'oeuvre soit disponible 
    - données :
        - données rentrées : je séléctionne l'oeuvre et l'ajoute à mon répertoire d'emprunt
        - données sorties : l'oeuvre séléctionné 

    - Etapes :
        - se rendre sur le site. 
        - se connecter ou s'inscrire.
        - choisir une oeuvre dans la liste des oeuvres disponible libre de droit.
        - cliquer sur Emprunter l'oeuvre.
    - Exception :
        - oeuvre plus disponible.
    - Descriptions : 

3. **Scénario : Rechercher oeuvre :**  
    -   description : le membre peut renseigner des information sur une oeuvre affin de la trouver.
    - liste des acteurs : membre
    - prérequis : informations, sur l'oeuvre recherché moteur de recherche
    -  données: 
        - données rentré: les informations sur l'oeuvre
        - données sortie: fiche données de l'oeuvre.
    - Etapes :
        - Se rendre sur le site.
        - Aller dans la barre de recherche.
        - taper le nom de l'oeuvre recherché
        - regarder dans la liste proposé si l'oeuvre est dans la liste.
    - Exception :
        - Oeuvre non répertorié.
    - Descriptions : 

4. **Scénario : Proposer oeuvre**
    - description : le membre peux proposer des oeuvres (privé ou public) à ajouter aux répértoire appropriés.
    - acteurs : utilisateur et admin 
    - prérequis : Il faut etre membre et que l'oeuvre soit validé par l'Admin
    - données :
        - données rentrées : je scanne ou copie l'oeuvre , rentre les données utiles tels que Titre , auteur , date , etc...
        - données sorties : l'oeuvre est ajouter à la base de données

    - Etapes :
        - Se rendre sur le site 
        - Se connecter ou s'inscrire
        - aller dans la rubrique proposer un oeuvre
        - renseigner l'oeuvre que nous voulons partager avec tout les champs nécessaire (titre, date, description...)
        - Publier l'oeuvre 
    - Exception :
        - Oeuvre déjà sur le site.
    - Descriptions : 

5. **Scénario : S'inscrire:**  
    -   description : le visiteur peut renseigner ses informations personnels, afin d'avoir les accès pour pour louer une oeuvre. 
    - liste des acteurs : membre
    - prérequis : informations personnel.
    -  données: 
        - données rentré:les informations informations personnels
        - données sortie: accès aux oeuvre. nouveau profil.
    - Etapes :
        - se dendre sur le site
        - rentrer toute les données personnel, neccessaire.
        - Sauvegarder les données.
    - Exception :
         - vous etes déjà inscrit
    - Descriptions : 

6. **Scénario : Se connecter/ déconnecter**
    - description : le visiteur peut se connecter et se deconnecter facilement de l'appliction web
    - acteurs : membre
    - prérequis : etre visiteur pour se connecter et membre pour se deconnecter
    - données :
        - données rentrées : pseudo et mdp
        - données sorties : profil du membre

    - Etapes :
        - se connecter : 
            - cliquer sur login
            - entrer son identifiant et son mot de passe 
            - entrer
        - se deconnecter
            - cliquer sur logout
    - Exception :
        - si vous n'avez pas de compte, il faudra creer un profil
    - Descriptions : 

7.  **Scénario 1: Modifier le profil:**
    -   description : le visiteur peut renseigner des informations personnel qui auraient soit changé, soit des information sur lesquels il se serait trompé lors de l'inscription, ou de la dernière modifiction.  
    - liste des acteurs : membre
    - prérequis : informations personnel à jour.
    -  données: 
        - données rentré: les informations informations personnels à jour
        - données sortie: profil modifié.
    - Etapes :
        - se connecter si ce n'est pas déjà fait 
        - aller sur votre profil
        - cliquer su "modifer vos données".
        - changer les champs à mettre à jour
        - sauvegarder
    - Exception :
        - si vous n'etes pas connecté avec vos identifiants
        - si vous n'avez pas de compte.
    - Descriptions : 

8. **Scénario :  Supprimer profil**
    - description : le membre peut supprimer son profil à tout moment, l'admin peut aussi supprimer le profil d'autre membre
    - acteurs : membre et admin
    - prérequis : etre connecté . 
    - données :
        - données rentrées :  suppression du profil
        - données sorties : profil supprimer , membre supprimer 

    - Etapes :
        - se connecter si ce n'est pas déjà fait 
        - aller sur votre profil.
        - aller dans les réglages 
        - cliquer sur "suppimer mon profil".
        - confirmer
    - Exception :
        - si vous n'etes pas connecté avec vos identifiants
        - si vous n'avez pas de compte.
    - Descriptions : 

9.  **Scénario 1: Completer l'oeuvre:**  
    -   description : L'administrateur peut renseigner les informations complémentaire d'une oeuvre  
    - liste des acteurs : Administrateur
    - prérequis : informations de l'oeuvre.
    -  données: 
         - données rentré: les informations de l'oeuvre
        - données sortie: nouvelle oeuvre en base de donnée.
    - Etapes :
        - se connecter si ce n'est pas déjà fait. 
        - se rendre sur l'oeuvre.
        - cliquer sur "completer l'oeuvre.
        - completer les champs à completer.
        - Sauvegarder.
    - Exception :
        - si l'oeuvre n'est pas la votre.
        - si vous n'etes pas connecté.
        - si vous n'etes pas administrateur
    - Descriptions : 


10. **Scénario :  Modifier données oeuvre**
    - description : l'admin peut modifier les données de l'oeuvre ( titre , date , descirption , etc..) quand il le souhaite
    - acteurs : admin
    - prérequis :  est connecté en tant qu'admin
    - données :
        - données rentrées :  données à  modifier de la fiche technique de l'oeuvre 
        - données sorties :  fiche technique modifié 

    - Etapes :
        - Se connecter si ce n'est pas déjà fait.
        - se rendre sur l'oeuvre à modifier
        - cliquer sur "modifier l'oeuvre"
        - changer les champs à modifier.
        - Sauvegarder
    - Exception :
        - Vous n'etes pas administateur.
        - vous n'etes pas connecté
        - vous n'avez pas de donnée à mettre à jour sur l'oeuvre

    - Descriptions : 



11. **Scénario : Supprimer oeuvre**
    - description : l'admin peut supprimer une oeuvre si il le veut, la suppression de l'oeuvre entrainera la destrcuction de tout les champs qu'elle comporte(titre, date, description, ect..)
    - acteurs : admin
    - prérequis :  est connecté en tant qu'admin
    - données :
        - données rentrées :  l'oeuvre à supprimer. 
        - données sorties :  message : la suppression à bien été faite  

    - Etapes :
        - se connecter si ce n'est pas déjà fait
        - se rendre sur l'oeuvre en question 
        - Cliquer sur supprimer l'oeuvre
    - Exception :
        - Vous n'etes pas administrateur
        - vous n'etes pas connecté.

    - Descriptions : 


12. **Scénario : Decider statut de l'oeuvre**
    - description : l'Admin peut ajouter un statut à une oeuvre. si elle est acive ou non, visible ou non.
    - prérequis :  est connecté en tant qu'admin
    - données :
        - données rentrées :  l'oeuvre à statuer. 
        - données sorties :  Oeuvre avec un statut  

    - Etapes :
        - Se connecté si ce n'est pas déjà fait 
        - se rendre sur l'oeuvre en question
        - Cliquer su statuer l'oeuvre
        - Seclectionner le statut opproprié 
        - Sauvegardé
    - Exception :
        - Vous n'etes pas administrateur
        - Vous n'etes pas connecté
    - Descriptions : 

