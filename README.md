 TP 2 - Requêter une API publique


  1. Requête GET sur les commentaires

 URL : `https://jsonplaceholder.typicode.com/comments`
 Méthode : `GET`
 Description : Cette requête récupère tous les commentaires ou ceux associés au post ayant l'ID 1.



 2. Requête POST sur les todos

URL : `https://jsonplaceholder.typicode.com/todos`
Méthode : `POST`
Paramètres :
   `userId=1`
   `title=Faire du code`
   `completed=false`
Description : Crée un nouveau "todo" pour l'utilisateur avec l'ID 1.



  3. Requête PATCH sur les posts

URL : `https://jsonplaceholder.typicode.com/posts/1`
Méthode : `PATCH`
Paramètres :
   `title="Nouveau titre"`
   `body="Nouveau contenu du post"`
Description : Met à jour le post avec l'ID 1, en modifiant son titre et son contenu.



 4. Requête GET pour afficher les commentaires du post avec l'ID 1

URL : `https://jsonplaceholder.typicode.com/comments?postId=1`
Méthode : `GET`
Description : Récupère tous les commentaires associés au post ayant l'ID 1.



 5. Requête GET pour afficher les photos affiliées à l'album numéro 2

URL: `https://jsonplaceholder.typicode.com/photos?albumId=2`
Méthode : `GET`
Description : Récupère toutes les photos affiliées à l'album avec l'ID 2.
