Ahora que sabemos cómo agregar filtros, nos gustaría que se pueda buscar utilizando diferentes criterios. 

Armamos un filtro donde se muestran distintos contenidos de “El planeta de los simios”, cuyo año de estreno sea de 1974 en adelante o tenga puntaje mayor a 8 y no sea el Cómic. 

```sql
SELECT id_contenido, titulo, formato, estreno, puntaje
FROM series_peliculas
WHERE titulo LIKE "%planeta de los simios%"
AND (estreno >= 1974 OR puntaje >= 8) 
AND NOT formato LIKE "cómic";
```

<div
  class='mu-sql-table'
  data-name='series_peliculas'
  data-columns='[{"name": "id_contenido", "pk": true}, "titulo", "formato", "creador", "estreno", "puntaje"]'
  data-rows='[
    [1, "El planeta de los simios", "Novela", "Pierre Boulle", 1963, 9.8], 
    [2, "El planeta de los simios", "Película", "Franklin Schaffner", 1968, 7.9],
    [3, "Escape del plantea de los simios", "Película", "Arthur P. Jacobs", 1971, 6.5],
    [4, "Conquista del planeta de los simios", "Película", "Arthur P. Jacobs", 1972, 6.7], 
    [5, "La batalla por el planeta de los simios", "Película", "Arthur P. Jacobs", 1973, 8.6],
    [6, "El planeta de los simios", "Serie", "Mort Abraham", 1974, 7],
    [7, "Regreso al planeta de los simios", "Serie", "DePatie-Freleng Enterprises", 1975, 7.4],
    [8, "El planeta de los simios", "Cómic", "El planeta de los simios franquicia", 1975, 8.2],
    [9, "El planeta de los simios", "Película", "Tim Burton", 2001, 8],
    [10, "El planeta de los simios: evolución", "Película", "Rupert Wyatt", 2011, 7.8],
    [11, "El planeta de los simios: confrontación", "Película", "Matt Reeves", 2014, 9], 
    [12, "La guerra del planeta de los simios", "Película", "Matt Reeves", 2017, 9.5]
  ]'>
</div>