# mongodb-consultas-rafael
Ejercicios de MongoDB que incluyen inserciones, consultas, actualizaciones y operaciones de agregación para análisis de datos.
[README.md](https://github.com/user-attachments/files/23654289/README.md)
# Consultas en MongoDB -- Rafael Reales

Este repositorio contiene un archivo con las operaciones básicas,
filtros y consultas de agregación realizadas en MongoDB como parte de la
actividad académica.


### Inserción de datos

-   Creación de una colección llamada **productos**
-   Inserción de más de 100 documentos ficticios con:
    -   `nombre`
    -   `categoria`
    -   `precio`
    -   `stock`

### Consultas básicas

-   `insertOne()` y `insertMany()`
-   `find()` para visualizar documentos
-   `updateOne()` para modificar datos
-   `deleteOne()` para eliminar documentos

### Consultas con filtros y operadores

Se incluyen ejemplos utilizando operadores como: - `$gt` (mayor que) -
`$lt` (menor que) - `$and` / `$or` - `$regex` para búsquedas por texto

### Consultas de agregación (\$group)

Se realizan operaciones como: - Contar productos por categoría -
Calcular el **precio promedio** - Obtener el **stock total** - Máximo y
mínimo precio

------------------------------------------------------------------------

Cómo ejecutar el archivo

1.  Abrir **MongoDB Shell**, **MongoDB Compass** o **mongosh**.
2.  Conectarse a la base de datos deseada.
3.  Copiar y pegar el contenido del archivo `.js`.

Ejemplo en mongosh:

``` bash
mongosh
use tienda
load("consultas_mongodb.js")
```

------------------------------------------------------------------------

 Autor

**Rafael Reales**\
Actividad académica -- Consultas en MongoDB.

------------------------------------------------------------------------

Contacto

Si requiere más información, puede comunicarse conmigo a través de la
plataforma educativa.
