# Twisk
L’utilisateur dispose d’une interface graphique pour créer et dessiner un monde. Un monde est composé de différentes étapes dans lesquelles vont circuler des « clients ».

Les étapes représentent des activités : piscine, toboggan, zoo qui vont pouvoir accueillir des clients. Certaines activités ont un nombre de places limité et sont donc précédées par un service de distribution de jetons, un guichet, modélisé par une file d’attente. Lorsque l’utilisateur a terminé la création de son monde, il peut demander à simuler l’évolution des clients dans les différentes étapes.

# Utilisation
  - Télécharger le fichier **twisk.jar**
  - Télécharger la bibliothèque javaFX ( https://gluonhq.com/products/javafx/ )
  - Ouvrir un terminal dans le dossier où se trouve twisk.jar
  - Utiliser la ligne de commande suivant : 
```bash  
java -jar --module-path [...]/lib --add-modules javafx.controls,javafx.fxml,javafx.graphics -Djdk.gtk.version=2. -Dprism.forceGPU=true twisk.jar
```
avec [...]/lib, l'emplacement du dossier lib de javaFX

# Fonctionnalités

  - Créer des Activités avec modification de la durée
  - Créer des Guichets avec modification du nombre de jetons
  - Déplacer les Activités / Guichets 1 par 1
  - Renommer les Activités / Guichets
  - Supprimer des Activités / Guichets
  - Charger un monde comportant des Activités / Guichets
  - Sauvegarder un modèle
  - Agrandir / Rétrécir les Activtés / Guichets avec la molette centrale de la souris
  - Modifier le nombre de clients
  - Autoriser les boucles dans le modèle
  - Choisir différente loi de probabilté ( Gausienne, Poisson, Uniforme )
  - Choisir les Activités où rentrent et sortent les clients

# Aperçu

  - Général
  ![Connexion](https://nsa40.casimages.com/img/2020/11/10//201110100839203485.png)
  ![Connexion](https://nsa40.casimages.com/img/2020/11/10//201110100910341527.gif)
  
  - Choisir les Activités où rentrent et sortent les clients 
  ![Connexion](https://nsa40.casimages.com/img/2020/11/10//201110100909376446.gif)
  
  - Ajouter et déplacer un Activité
  ![Connexion](https://nsa40.casimages.com/img/2020/11/10//201110101226708715.gif)
  
  - Ajouter et déplacer un Guichet
  ![Connexion](https://nsa40.casimages.com/img/2020/11/10//201110101258150562.gif)
  
  - Renommer une Activité / Guichet
  ![Connexion](https://nsa40.casimages.com/img/2020/11/10//201110101301553240.gif)
  
  - Modifier le nombre de jetons d'un Guichet
  ![Connexion](https://nsa40.casimages.com/img/2020/11/10//201110101226889466.gif)
