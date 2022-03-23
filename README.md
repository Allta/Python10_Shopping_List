# Examen Introduction Python - Ynov Python B1

## Consignes

:see_no_evil: _**Il s'agit d'un travail autonomne. Toute communication sera sanctionnée.**_ :speak_no_evil:

‼️ **Plagiat interdit** ‼️

‼️ **Le Non-respect des consignes sera pénalisé** ‼️

## Présentation du besoin technique 

### Résumé 

Vous allez devoir réaliser un programme en ligne de commande qui permet de gérer une liste de course.
Il va falloir pouvoir rajouter/enlever/afficher des éléments dans votre liste de course. 
Cette liste de course devra être persistente. C'est à dire qu'elle devra être sauvegardée sur le disque pour pouvoir la modifier et la récupérer même lorsque le programme ne fonctionnera plus. 

Une fois la liste de course valider par l'utilisateur il faudra l'envoyer sur internet pour pouvoir y accéder depuis n'importe quel appareil. 

------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------

### Fonction de la liste de course
Dans ce projet, il va falloir créer un programme en ligne de commande qui permet de manipuler une liste de courses.
**Déroulé du script :** 

Le programme doit permettre de réaliser 5 actions :

- Ajouter un élément à la liste de courses
- Retirer un élément de la liste de courses
- Afficher les éléments de la liste de courses
- Vider la liste de courses
- Valider la liste de course et l'envoyer sur internet
- Quitter le programme

Il faut donc demander à l'utilisateur de choisir parmi une de ces action en entrant un nombre de 1 à 5.

*La gestion d'erreur devra être présente dans le script.*
Il faut donc gérer le cas de figure où l'utilisateur ne rentre pas un nombre compris entre 1 et 5 ou s'il rentre par exemple des lettres ou un autre symbole invalide. Dans ce cas, il faut afficher de nouveau le menu avec les options disponibles, jusqu'à ce que l'utilisateur choisisse une option valide.

_**Ajouter un élément :**_

L'ajout d'un élément devra prendre en compte : `nom de l'article` ainsi que sa `quantité` (En gramme ou en nombre d'unité).

### Sauvegarde de la liste de course 

La liste de course doit être sauvegardée dans un fichier **json** sous le nom `shopping.json`. 

Le programme devra vérifier si un fichier `shopping.json` existe déjà ou non. 

Si le fichier existe déjà il faudra récupérer la liste de course existante et la modifier. 

Si le fichier n'existe pas alors il faut partir sur une liste vide. 

Lorsque l'utilisateur quittera le programme, il faudra sauvegarder le fichier sur le disque en écrasant l'ancien. 

------------------------------------------------------------------------------------------------------------------------------------------------
**INFORMATION TECHNIQUE**

------------------------------------------------------------------------------------------------------------------------------------------------

    En Python, le JSON s'apparente à un dictionnaire.
    Il est composé d'un collection de couple clef/valeur
    
    Pour formater des données Python en JSON et inversement, la librairie json existe.
    Cependant il est possible d'écrire un dictionnaire Python dans un fichier JSON.
    Pour convertir un objet Python en chaine JSON, il faut utiliser l’une des méthodes dump() ou dumps() du module json.
    La méthode dump() permet d’enregistrer les données JSON dans un fichier tandis que dumps() (=“dump string”) renvoie simplement les données sous forme de chaine JSON et  permet de continuer à travailler avec elles.
 
Exemple d'un fichier .json  : 

![image](https://user-images.githubusercontent.com/51991304/159792369-770b6bef-ffe2-41d1-b2a4-2d0c14dc0a0a.png)


## Livrable
### Documentation Technique  

**Un fichier _md_ ->  [NOM]\_[PRENOM].md** 

Il y a un template de rendu dans le repository. Vous pouvez le reprendre et le modifier. 
Le template contient la syntaxe **Markdown** qui permet de réaliser des rendu esthétique et professionnel très rapidement. 
        
:bangbang::bangbang: Pensez à renommer le fichier avec votre **Nom** et **Prénom**

:sparkles: Une fois le TP et le rendu terminé commitez et pushez le dans le repo. :sparkles:
  
_**Il n'y a pas de minimum ou de maximum de pages démandées. La notation se fera sur la qualité du rendu.**_ 

 Cette documentation technique doit : 
 - Rappeler le besoin 
 - Expliquer le fonctionnement du programme 
 - Inclure une documentation d'utilisation ( Comme le `--help` d'une commande linux)
 
 Les screenshots sont les bienvenus dans ce rendu. 
 
 ### Technique

Le programme python et ses fichiers de configuration ou tout fichiers liés au programme devront être présents sur ce repository. 
### Délais 

Tous les livrables (Documentation technique + programme) devront être présent sur le repository à la fin de la séance. 
Le repository sera **fermé** et il sera **impossible** de commiter une fois les 4h terminées. 
