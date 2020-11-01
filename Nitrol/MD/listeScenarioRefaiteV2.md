# Liste des scénarios d'application :
1. **Scénario : Louer un oeuvre :** 
    -   description : le membre peut aller enprunter une oeuvre non libre de droit dans un un des repertoires propsé, à un prix fixé, pour un temps fixé
    - liste des acteurs : le loueur et le client.
    - prérequis : une oeurvre privé, etre un membre, disponiblité de l'oeuvre.
    -  données: 
        - données rentré: paiment et contrepartie.
        - données sortie: Oeuvre.
    - Etapes :
        - le client se rend sur le site. 
        - il  se connecte ou s'inscrit si il n'a pas  de compte.
        - choisit une oeuvre dans la liste des oeuvres disponibles privées.
        - clique sur louer l'oeuvre.
        - l'oeuvre apparait dans son repertoire personnel

    - Exception :
        - Oeuvre pas disponible.
    - Descriptions : 

2. **Scénario : Enprunter oeuvre**
    - description : je peux avoir accés à une oeuvre publique temporairement  de n'importe quels répertoire public (musique, livre , vidéo)
    - acteurs : utilisateur et admin  
    - prérequis : Il faut etre membre et que l'oeuvre soit disponible 
    - données :
        - données rentrées : je séléctionne l'oeuvre et l'ajoute à mon répertoire d'emprunt
        - données sorties : l'oeuvre séléctionné 

    - Etapes :
        - le client se  rend sur le site. 
        - il  se connecte ou s'inscrit si il n'a pas  de compte.
        - il choisit une oeuvre dans la liste des oeuvres disponible libre de droit.
        - clique sur Emprunter l'oeuvre.
        - l'oeuvre apparait dans son repertoire personnel
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
        - le client se  rend sur le site.
        - va dans la barre de recherche.
        - tape le nom de l'oeuvre recherché
        - regarde dans la liste proposé si l'oeuvre est dans la liste.
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
        - le client se  rend sur le site. 
        - il  se connecte ou s'inscrit si il n'a pas  de compte.
        - va dans la rubrique proposer un oeuvre
        - renseigne l'oeuvre qu'il veut partager avec tout les champs nécessaires (titre, date, description...)
        - attends la confiramation de l'admin
        - publie l'oeuvre 
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
        - le client se rend sur le site
        - rentre ses données dans le formulaire d'inscription.
        - valide les données.
    - Exception :
         - le client est déjà inscrit
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
            - le client clique sur login
            - entre son identifiant et son mot de passe 
            - valide
        - se deconnecter
            - clique sur logout
    - Exception :
        - si le client n'a pas de compte, il faudra créer un profil
    - Descriptions : 

7.  **Scénario : Modifier le profil:**
    -   description : le visiteur peut renseigner des informations personnel qui auraient soit changé, soit des information sur lesquels il se serait trompé lors de l'inscription, ou de la dernière modifiction.  
    - liste des acteurs : membre
    - prérequis : informations personnel à jour.
    -  données: 
        - données rentré: les informations informations personnels à jour
        - données sortie: profil modifié.
    - Etapes :
        - le client se connecte si ce n'est pas déjà fait 
        - va sur votre profil
        - clique su "modifer vos données".
        - change les champs à mettre à jour
        - valide les mises à jours
    - Exception :
       
        - si le client n'a pas de compte.
    - Descriptions : 

8. **Scénario :  Supprimer profil**
    - description : le membre peut supprimer son profil à tout moment, l'admin peut aussi supprimer le profil d'autre membre
    - acteurs : membre et admin
    - prérequis : etre connecté . 
    - données :
        - données rentrées :  suppression du profil
        - données sorties : profil supprimer , membre supprimer 

    - Etapes :
        - le client se connecte 
        - va sur son profil.
        - va dans les réglages 
        - clique  sur "suppimer mon profil".
        - valide la supression
    - Exception :
        - si le client n'a pas de compte.
    - Descriptions : 

9.  **Scénario : Completer l'oeuvre:**  
    -   description : L'administrateur peut renseigner les informations complémentaire d'une oeuvre  
    - liste des acteurs : Administrateur
    - prérequis : informations de l'oeuvre.
    -  données: 
         - données rentré: les informations de l'oeuvre
        - données sortie: nouvelle oeuvre en base de donnée.
    - Etapes :
        - l'admin se connecte 
        - se rend sur l'oeuvre.
        - clique sur "completer l'oeuvre ou modifier ".
        - complete les champs manquants.
        - valide les modifications.
    - Exception :
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
        - l'admin se connecte.
        - se rende sur l'oeuvre à modifier
        - clique sur "modifier ou supprimer l'oeuvre"
        - modifie les champs de l'oeuvre.
        - valide les modifications.
    - Exception :
        - il n'est pas administateur.

    - Descriptions : 



11. **Scénario : Supprimer oeuvre**
    - description : l'admin peut supprimer une oeuvre si il le veut, la suppression de l'oeuvre entrainera la destrcuction de tout les champs qu'elle comporte(titre, date, description, ect..)
    - acteurs : admin
    - prérequis :  est connecté en tant qu'admin
    - données :
        - données rentrées :  l'oeuvre à supprimer. 
        - données sorties :  message : la suppression à bien été faite  

    - Etapes :
        - l'admin se connecte
        - se rende sur l'oeuvre en question 
        - clique sur supprimer l'oeuvre
    - Exception :
        -  il n'est pas administrateur

    - Descriptions : 


12. **Scénario : Decider statut de l'oeuvre**
    - description : l'Admin peut ajouter un statut à une oeuvre. si elle est acive ou non, visible ou non.
    - prérequis :  est connecté en tant qu'admin
    - données :
        - données rentrées :  l'oeuvre à statuer. 
        - données sorties :  Oeuvre avec un statut  

    - Etapes :
        - l'admin se connecte
        - se rende sur l'oeuvre en question
        - clique su statuer l'oeuvre
        - seclectionne le statut approprié 
        - valide
    - Exception :
        - il n'est pas administrateur
    - Descriptions : 
