¿Pero qué sucede si, en vez de ver toda la tabla con la información detallada de las series y películas, solo queremos conocer la cantidad que hay?

Para eso, existe la función `COUNT` que, como te imaginarás, cuenta y devuelve el resultado total. Como toda función, recibe algún parámetro entre paréntesis.

Podés agregarle luego la expresión `AS` *nombre_con_que_quieras_mostrar_el_resultado*.

> Realizá la consulta necesaria para saber cuántas series y películas hay cargadas en la plataforma actualmente. Mostrá el resultado como _cantidad_de_contenido_.

<div
  class='mu-erd'
  data-entities='{
    "series_peliculas": {
      "titulo": {
        "type": "Text"
      },
      "descripcion": {
        "type": "Text"
      },
      "creador": {
        "type": "Text"
      },
      "personajes": {
        "type": "Text"
      },
      "temporadas": {
        "type": "Integer"
      },
      "estreno": {
        "type": "Integer"
      },
      "puntaje": {
        "type": "Real"
      }
    }
  }'>
</div>