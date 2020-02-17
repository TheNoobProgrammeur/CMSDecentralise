# Scenario 9

- **Titre** : Suppression d'un document (word, libreOffice)
- **Objectif**: Donner la possibilité à l'utilisateur de supprimer un de ses articles
- **Précondition(s)**:
	- Avoir installé l'application en local
	- Avoir un compte utilisateur permettant la suppression
	- Avoir effectuer le scenario `Connection` (Scenario 8)

## Etapes

- 1 : L'internaute accède à ses articles grâce à un bouton ''Mes Documents'' présent sur l'écran d'accueil

- 2 : L'utilisateur séléctionne un document

- 3 : Si l'utilisateur a les droits de modification alors :

  - 4 : L'application determine le logiciel pour ouvrire le document.
  
- 5 : Sinon l'application affiche une prévisualisation du document.


cas d'erreurs:

- Type du document inconue.

- On ne sais pas prévisualiser le document.

- On n'arrive pas a modifier ce document 
