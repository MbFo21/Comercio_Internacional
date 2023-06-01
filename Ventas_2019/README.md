# Re etiquetado de archivo de ventas 2019

**Problema presentado** 
El archivo al ser leido en formato excel mezcla los tipos de datos. no podemos decir que datos son de tipo "fctor" o categoria 
para poder clasicicar los grupos de knn.

**Que hemos hecho**
Agregamos una columna al final que tiene las categorías :

- Botellas , pera todos los pedidos entre 1 y 12 unidades
- Cajas de cartón , para todos los que van de 13 a 24 unidades
- Pallet , para los pedidos que exceden las 25 unidades.

Se ha generado el archivo **Ventas_2019_Etiquetado.csv** que puede usarse para kNN 
