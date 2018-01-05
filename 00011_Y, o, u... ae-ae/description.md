Ahora que sabemos cómo agregar filtros, nos gustaría que se pueda buscar utilizando distintos criterios. 

Armamos un filtro donde se muestran distintos contenidos de “El planeta de los simios”, cuyo año de estreno sea del 2010 hasta la actualidad o tenga puntuación mayor a 8 y no sea el Cómic. 

```sql
SELECT titulo
FROM series_peliculas
WHERE titulo LIKE "%planeta de los simios%"
AND (estreno > 2010 OR puntuacion >= 8) 
AND NOT formato LIKE "cómic";
```

<div
  class='mu-sql-table'
  data-name='series_peliculas'
  data-columns='["titulo", "formato", "creador", "estreno", "puntuacion"]'
  data-rows='[
    ["El planeta de los simios", "Novela", "Pierre Boulle", 1963, 8.1], 
    ["El planeta de los simios", "Película", 
    ["Escape del plantea de los simios", 1971
    "Conquista del planeta de los simios", 1972 
    "La batalla por el planeta de los simios", 1973 
    "La guerra del planeta de los simios", 2017 ], 
    ["IT", "Stephen King", "El payaso Pennywise, Beverly Marsh, Richie Tozier, Bill Denbrough, Eddie Kaspbrak, Stanley Uris, Ben Hanscom, Mike Hanlon, Georgie Denbrough", NULL, 8.9]
  ]'>
</div>

