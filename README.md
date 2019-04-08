## Rallye Lecture PHP

Ce projet réalisé en PHP à l'aide du framework CodeIgniter permet aux enseignant d'une base de données d'administrer un site relatif à un rallyeLecture et aux élèves d'y participer.

Le projet se divise en 3  parties :

* Connexion Administrateur / Utilisateur.
* Gestion des Livres
* Quizz sur les livres.

### Menu admin

![](https://image.noelshack.com/fichiers/2019/15/1/1554749033-capture3.png)

C'est l'administateur du site qui controlle tout.
En effet celui-ci à accès à toutes les pages et possèdent un controle total.

Nous nous sommes donc dans un premier temps intéressés à la pagination des pages du menu "LIVRE".
On remarque sur l'image ci-dessous une numérotation des pages réalisées en php.

![](https://image.noelshack.com/fichiers/2019/15/1/1554749036-capture4.png)

Ensuite, nous avons cherché à ajouter la fonctionnalité de pouvoir créer de nouveaux livres et de les insérer dans la base de données.

![](https://image.noelshack.com/fichiers/2019/15/1/1554749034-capture5.png)



### Menu enseignant

L'enseignant, préalablement créée peut donc se connecter au site et avoir accès à divers menus : 

![](https://image.noelshack.com/fichiers/2019/15/1/1554749032-capture2.png)


 ### Les éléves
 
 Les éléves dont nous avons ajouter leurs identifants dans la base de données grâce à l'application C# peuvent eux aussi se connecter au site et avoir accès aux quizzs proposés par leurs professeurs.
 
 
 ### Diagramme du site

![](https://raw.githubusercontent.com/AureohDev/RallyeLectureWebApp/master/Github/Schema/schemaDbRallyeLecture.PNG)

![](https://raw.githubusercontent.com/AureohDev/RallyeLectureWebApp/master/Github/Schema/schemaDbAauth.PNG)


