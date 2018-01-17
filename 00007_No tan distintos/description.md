Hasta ahora vimos tablas donde ningún registro se repetía. ¿Pero qué sucedería si 
se hicieran dos versiones de una misma película en el mismo año, o una película y un documental con similares características? ¿Cómo podríamos diferenciarlos? 

<div class='mu-sql-table'
  data-name='series_peliculas'
  data-columns='["titulo", "descripcion", "creador", "personajes", "temporadas", "puntaje"]'
  data-rows='[
    ["Los simuladores (Argentina)", "Cuatro socios que se dedican al negocio de la simulación, resuelven los problemas y necesidades de sus clientes mediante lo que ellos denominan operativos de simulacro.", "Damián Szifron", "Mario Santos, Pablo Lamponne, Emilio Ravenna, Gabriel Medina", 2, 10],
    ["Los simuladores (México)", "Cuatro socios que se dedican al negocio de la simulación, resuelven los problemas y necesidades de sus clientes mediante lo que ellos denominan operativos de simulacro.", "Damián Szifron", "Mario Santos, Pablo López, Emilio Vargas, Gabriel Medina", 2, 9.7],
    ["Los simuladores (Chile)", "Cuatro socios que se dedican al negocio de la simulación, resuelven los problemas y necesidades de sus clientes mediante lo que ellos denominan operativos de simulacro.", "Damián Szifron", "Ernesto Santos, Gabriel Medina, Emilio Ravenna, Pablo Lorca", 2, 9.3],
    ["Los simuladores (España)", "Cuatro socios que se dedican al negocio de la simulación, resuelven los problemas y necesidades de sus clientes mediante lo que ellos denominan operativos de simulacro.", "Damián Szifron", "Santos, Medina, León, Jota", 2, 9.8]
  ]'>
</div>

Para diferenciarlos se utiliza un identificador único para cada registro, que suele ser numérico por simplicidad, y se lo llama Clave Primaria, Principal o Primary Key (PK). 

> Consultá todos los campos de la tabla _series_peliculas_ para ver cómo quedó con el nuevo identificador agregado. 
