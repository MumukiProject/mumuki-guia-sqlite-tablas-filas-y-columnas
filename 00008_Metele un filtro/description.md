Vamos a crear la página de inicio de nuestra plataforma. 

Para no abrumar a los usuarios con un montón de detalles que inicialmente no les interesa, solo queremos mostrar el nombre de las series o películas, y la puntuación general. 
> Escribí la consulta que devuelva solo el título y la puntuación.  

<div
  class='mu-erd'
  data-entities='{
    "series_peliculas": {
      "id_contenido": {
        "type": "Integer",
        "pk": true
      },
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
      "puntuacion": {
        "type": "Real"
      }
    }
  }'>
</div>