Démo d'un simple web service rest utilisant springboot et la base de données h2.<br />
Les objets créés, listés et supprimés sont des films.<br />
Chaque film est modélisé par un objet movie {id, nom, genre, releaseDate).<br />
h2 gère l'id (autoincrémentation).<br />
-Page d'accueuil qui affcihe un message<br />
 http://localhost:8888/<br />
-Ajout d'un film (par un formulaire)<br />
  http://localhost:8888/ajouteMovie.html<br />
-Lister tous les films (représentation json)<br />
  http://localhost:8888/movies<br />
-Supprimer un film: il faut donner l'id du film à supprimer (par un formulaire)<br />
  http://localhost:8888/deleteMovie.html<br />
