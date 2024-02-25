Démo simple web service rest utilisant springboot et la base de données h2
Les objets crées, lister, supprimer sont des films.
Chaque film est modélisé par un objet movie {id, nom, genre, releaseDate)
h2 gère l'id (autoincrémentation)
Ajout d'un film (formulaire)
  http://localhost:8888/ajouteMovie.html
Lister tous les films (représentation json)
  http://localhost:8888/movies
Supprimer un film: il faut donner l'id du film à supprimer (formulaire)
  http://localhost:8888/deleteMovie.html
