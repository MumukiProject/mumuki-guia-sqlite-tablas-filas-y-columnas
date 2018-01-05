Ahora que sabemos cómo agregar filtros, nos gustaría que se pueda buscar utilizando distintos criterios. 

Armamos un filtro donde se muestran distintos contenidos de “El planeta de los simios”, cuyo año de estreno sea del 2010 hasta la actualidad o tenga puntuación mayor a 8 y no sea el Cómic. 

```sql
SELECT titulo
FROM series_peliculas
WHERE titulo LIKE "%planeta de los simios%"
AND (estreno > 2010 OR puntuacion >= 8) 
AND NOT formato LIKE "cómic";
```
