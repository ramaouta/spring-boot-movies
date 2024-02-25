Démo simple web service rest utilisant springboot et la base de données h2.<br />
Les objets crées, lister, supprimer sont des films.<br />
Chaque film est modélisé par un objet movie {id, nom, genre, releaseDate).<br />
h2 gère l'id (autoincrémentation).<br />
-Ajout d'un film (formulaire)<br />
  http://localhost:8888/ajouteMovie.html<br />
-Lister tous les films (représentation json)<br />
  http://localhost:8888/movies<br />
-Supprimer un film: il faut donner l'id du film à supprimer (formulaire)<br />
  http://localhost:8888/deleteMovie.html<br />
