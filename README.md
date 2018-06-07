# Annuaire


### BDD (PHP/MySQL)
* téléchargez ce repository (dossier)
* importez le fichier annuaire.sql fourni dans phpMyAdmin
  * ouvrez le avant, pour voir ce qu'il fait :D
  * dans phpMyAdmin, créez une nouvelle base données (utf8_general_ci)
  * allez dans l'onglet "importer": choisissez le fichier et executez l'importation
* créez un fichier php:
    * connectez votre fichier à la base de données (PDO)
    * affichez des données de la base de données
      * affichez tous les contacts de l'annuaire et affichez leur nombre
      * affichez ceux qui habitent à Auch
      * affichez ceux qui ont une adresse mail "gmail"
    * intégrez la possibilité de modifier le contact qui a l'id 18 pour y ajouter cette adresse mail ("ogatien@simplon.co")
    * supprimez un contact de l'annuaire

### Interface (HTML/CSS)
* intégrez Bootstrap ou Materialize à votre projet
* créez une interface graphique pour votre Annuaire avec au minimum une navbar et un footer
* affichez toutes les données citées plus haut sous forme de tableaux HTML
* créez une deuxième page PHP contenant un formulaire HTML permettant d'ajouter un nouveau contact


### Bonus
* pouvoir supprimer un contact
* pouvoir modifier un contact
