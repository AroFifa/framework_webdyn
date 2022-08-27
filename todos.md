##  Avant-projet
*   Mise en place de l'environnement
    -   créer 2 projets dans eclipse dans un même espace de travail:
        -   Framework
        -   Test
    -   utiliser le projet +Framework dans +Test
        -   rechercher des tuto
        -   utiliser un fichier jar

##  Code source
*   créer une classe Main +Test @main
*   créer un package modèle @@model pour les modèles de test
    -   créer une classe **User**
        -   ajouter des annotations
*   créer un package pour les annotations @note +Framework 
*   créer des classes pour les annotations +Framework 
    -   **Table** pour les tables dans la base de donnée
    -   **Attr** pour les colonnes des tables
    -   **Utilitaire** pour la réfléction: utilisant toutes les autres classes de l'annotation
*   créer une classe pour générer les scripts **ScriptDao** +Framework 
    -   save
    -   del
    -   alter
    -   get
*   créer une classe pour l'accès au donnée **GenericDao** +Framework 
    -   save
    -   del
    -   alter
    -   get
*   créer une classe exception **ExceptionDao** +Framework 
    -   exception si l'objet n'est pas une table dans la SGBD
        -   prendre le nom de la table
        -   prendre les colonnes dans la base de donnée
        -   générer un script
    
