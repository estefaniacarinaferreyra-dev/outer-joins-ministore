¿Por qué usaste LEFT JOIN para la Consulta 1 y no INNER JOIN? ¿Qué se perdería si usaras INNER JOIN?
Porque necesitaba traer TODOS los productos aunque no tengan venta asociada, el inner join solo trae los registros coincidentes.
Si hubiera usado inner join hubiera perdido todos aquellos productos que no tuvieron ventas.
¿Por qué usaste RIGHT JOIN para la Consulta 2? ¿Qué tabla está a la izquierda y cuál a la derecha en tu consulta?
Use right join porq necesitaba traer todas las ventas aunque no tuvieran producto asociado. A la izquiera tabla productos y a la derecha tabla ventas.
¿Qué representan los valores NULL en cada resultado? Explicá con un ejemplo concreto de los datos qué significa que venta_id sea NULL en la Consulta 1 y que producto_id de productos sea NULL en la Consulta 2.
En la consulta 1 que la venta_id sea null significa que para ese producto determinado no hubo ventas. En la consulta 2 el valor null del producto-id significa que hubo ventas sin producto asociado.
¿Cuándo usarías FULL OUTER JOIN en un caso real de negocio?
Cuendo necesito unir dos tablas pero no quiero perder ningún registro, ósea que me traiga registros no coincidentes tanto de la consulta 1 como de la consulta 2.
