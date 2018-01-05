Queremos mejorar la organización del contenido, utilizando algunos filtros. 

Por ejemplo, nos interesa mostrar una sección de “Recomendados” donde esté todo el contenido con puntuación mayor o igual a 9. 

```sql
SELECT titulo AS Recomendados
FROM series_peliculas 
WHERE puntuacion >= 9;
```

> Presioná continuar para ver el resultado.

<div
  class='mu-sql-table'
  data-name='series_peliculas'
  data-columns='["titulo, "descripcion", "creador", "personajes", "temporadas", "puntuacion"]'
  data-rows='[
    ["Stranger Things", "The Duffer Brothers", "Eleven, Mike, Will, Dustin, Lucas, Hopper, Joyce, Nancy, Jonathan, Steve", 2, 2016, 10], 
    ["Breaking Bad", "Vince Gilligan", "Walter White, Jesse Pinkman, Gus Fring, Saul Goodman, Mike Ehrmantraut, Hank Schrader, Tuco Salamanca, Skyler White", 5, 2008, 9.7], 
    ["IT", "Stephen King", "El payaso Pennywise, Beverly Marsh, Richie Tozier, Bill Denbrough, Eddie Kaspbrak, Stanley Uris, Ben Hanscom, Mike Hanlon, Georgie Denbrough", NULL, 2017, 8.9]
  ]'>
</div>
