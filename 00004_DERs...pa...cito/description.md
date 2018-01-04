Los sistemas informáticos utilizan distintos tipos de bases de datos que estructuran los datos de determinada manera. 

Una de ellas son las bases de datos relacionales que, manteniendo la misma idea de tablas que acabamos de ver, definen los campos necesarios que debe tener cada registro particular. 

Además, sería medio tonto poner como año de estreno: "mil novecientos noventa y tres":laughing:, así que es importante también diferenciar el tipo de dato acorde a cada caso. 

Se usa un DER (Diagrama Entidad Relación) como el siguiente para describir los campos y tipos de datos de cada tabla.

<div
  class='mu-erd'
  data-entities='{
    "series_peliculas": {
      "ent1_id": {
        "type": "Integer",
        "pk": true
      },
      "ent2_id": {
        "type": "Integer",
        "pk": true,
        "fk": {
          "to": { "entity": "Entity_2", "column": "ent2_id" },
          "type": "one_to_one"
        }
      },
      "ent1_description": {
        "type": "Varchar"
      }
    }
  }'>
</div>