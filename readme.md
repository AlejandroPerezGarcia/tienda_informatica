1. Consultas sobre una tabla

1.1) Lista el nombre de todos los productos que hay en la tabla producto.

1.2) Lista los nombres y los precios de todos los productos de la tabla producto.

1.3) Lista todas las columnas de la tabla producto.

1.4) Lista el nombre de los productos, el precio en euros y el precio en dólares estadounidenses (USD).

1.5) Lista el nombre de los productos, el precio en euros y el precio en dólares estadounidenses (USD). Utiliza los siguientes alias para las columnas: nombre de producto, euros, dólares.

1.6) Lista los nombres y los precios de todos los productos de la tabla producto, convirtiendo los nombres a mayúscula.

1.7) Lista los nombres y los precios de todos los productos de la tabla producto, convirtiendo los nombres a minúscula.

1.8) Lista el nombre de todos los fabricantes en una columna, y en otra columna obtenga en mayúsculas los dos primeros caracteres del nombre del fabricante.

1.9) Lista los nombres y los precios de todos los productos de la tabla producto, redondeando el valor del precio.

1.10) Lista los nombres y los precios de todos los productos de la tabla producto, truncando el valor del precio para mostrarlo sin ninguna cifra decimal.

1.11) Lista el identificador de los fabricantes que tienen productos en la tabla producto.

1.12) Lista el identificador de los fabricantes que tienen productos en la tabla producto, eliminando los identificadores que aparecen repetidos.

1.13) Lista los nombres de los fabricantes ordenados de forma ascendente.

1.14) Lista los nombres de los fabricantes ordenados de forma descendente.

1.15) Lista los nombres de los productos ordenados en primer lugar por el nombre de forma ascendente y en segundo lugar por el precio de forma descendente.

1.16) Devuelve una lista con las 5 primeras filas de la tabla fabricante.

1.17) Devuelve una lista con 2 filas a partir de la cuarta fila de la tabla fabricante. La cuarta fila también se debe incluir en la respuesta.

1.18) Lista el nombre y el precio del producto más barato. (Utilice solamente las cláusulas ORDER BY y LIMIT)

1.19) Lista el nombre y el precio del producto más caro. (Utilice solamente las cláusulas ORDER BY y LIMIT)

1.20) Lista el nombre de todos los productos del fabricante cuyo identificador de fabricante es igual a 2.

1.21) Lista el nombre de los productos que tienen un precio menor o igual a 120€.

1.22) Lista el nombre de los productos que tienen un precio mayor o igual a 400€.

1.23) Lista el nombre de los productos que no tienen un precio mayor o igual a 400€.

1.24) Lista todos los productos que tengan un precio entre 80€ y 300€. Sin utilizar el operador BETWEEN.

1.25) Lista todos los productos que tengan un precio entre 60€ y 200€. Utilizando el operador BETWEEN.

1.26) Lista todos los productos que tengan un precio mayor que 200€ y que el identificador de fabricante sea igual a 6.

1.27) Lista todos los productos donde el identificador de fabricante sea 1, 3 o 5. Sin utilizar el operador IN.

1.28) Lista todos los productos donde el identificador de fabricante sea 1, 3 o 5. Utilizando el operador IN.

1.29) Lista el nombre y el precio de los productos en céntimos (Habrá que multiplicar por 100 el valor del precio). Cree un alias para la columna que contiene el precio que se llame céntimos.

1.30) Lista los nombres de los fabricantes cuyo nombre empiece por la letra S.

1.31) Lista los nombres de los fabricantes cuyo nombre termine por la vocal e.

1.32) Lista los nombres de los fabricantes cuyo nombre contenga el carácter w.

1.33) Lista los nombres de los fabricantes cuyo nombre sea de 4 caracteres.

1.34) Devuelve una lista con el nombre de todos los productos que contienen la cadena Portátil en el nombre.

1.35) Devuelve una lista con el nombre de todos los productos que contienen la cadena Monitor en el nombre y tienen un precio inferior a 215 €.

1.36) Lista el nombre y el precio de todos los productos que tengan un precio mayor o igual a 180€. Ordene el resultado en primer lugar por el precio (en orden descendente) y en segundo lugar por el nombre (en orden ascendente).

---

2. Consultas multitabla (Composición interna)

2.1) Devuelve una lista con el nombre del producto, precio y nombre de fabricante de todos los productos de la base de datos.

2.2)Devuelve una lista con el nombre del producto, precio y nombre de fabricante de todos los productos de la base de datos. Ordene el resultado por el nombre del fabricante, por orden alfabético.

2.3)Devuelve una lista con el identificador del producto, nombre del producto, identificador del fabricante y nombre del fabricante, de todos los productos de la base de datos.

2.4)Devuelve el nombre del producto, su precio y el nombre de su fabricante, del producto más barato.

2.5)Devuelve el nombre del producto, su precio y el nombre de su fabricante, del producto más caro.

2.6)Devuelve una lista de todos los productos del fabricante Lenovo.

2.7)Devuelve una lista de todos los productos del fabricante Crucial que tengan un precio mayor que 200€.

2.8)Devuelve un listado con todos los productos de los fabricantes Asus, Hewlett-Packardy Seagate. Sin utilizar el operador IN.

2.9)Devuelve un listado con todos los productos de los fabricantes Asus, Hewlett-Packardy Seagate. Utilizando el operador IN.

2.10)Devuelve un listado con el nombre y el precio de todos los productos de los fabricantes cuyo nombre termine por la vocal e.

2.11)Devuelve un listado con el nombre y el precio de todos los productos cuyo nombre de fabricante contenga el carácter w en su nombre.

2.12)Devuelve un listado con el nombre de producto, precio y nombre de fabricante, de todos los productos que tengan un precio mayor o igual a 180€. Ordene el resultado en primer lugar por el precio (en orden descendente) y en segundo lugar por el nombre (en orden ascendente)

2.13)Devuelve un listado con el identificador y el nombre de fabricante, solamente de aquellos fabricantes que tienen productos asociados en la base de datos.

---

3. Consultas multitabla (Composición externa)
   Resuelva todas las consultas utilizando las cláusulas LEFT JOIN y RIGHT JOIN.

3.1) Devuelve un listado de todos los fabricantes que existen en la base de datos, junto con los productos que tiene cada uno de ellos. El listado deberá mostrar también aquellos fabricantes que no tienen productos asociados.

3.2) Devuelve un listado donde sólo aparezcan aquellos fabricantes que no tienen ningún producto asociado.

3.3) ¿Pueden existir productos que no estén relacionados con un fabricante? Justifique su respuesta.

---

4. Consultas resumen

4.1) Calcula el número total de productos que hay en la tabla productos.

4.2) Calcula el número total de fabricantes que hay en la tabla fabricante.

4.3) Calcula el número de valores distintos de identificador de fabricante aparecen en la tabla productos.

4.4) Calcula la media del precio de todos los productos.

4.5) Calcula el precio más barato de todos los productos.

4.6) Calcula el precio más caro de todos los productos.

4.7) Lista el nombre y el precio del producto más barato.

4.8) Lista el nombre y el precio del producto más caro.

4.9) Calcula la suma de los precios de todos los productos.

4.10) Calcula el número de productos que tiene el fabricante Asus.

4.11) Calcula la media del precio de todos los productos del fabricante Asus.

4.12) Calcula el precio más barato de todos los productos del fabricante Asus.

4.13) Calcula el precio más caro de todos los productos del fabricante Asus.

4.14) Calcula la suma de todos los productos del fabricante Asus.

4.15) Muestra el precio máximo, precio mínimo, precio medio y el número total de productos que tiene el fabricante Crucial.

4.16) Muestra el número total de productos que tiene cada uno de los fabricantes. El listado también debe incluir los fabricantes que no tienen ningún producto. El resultado mostrará dos columnas, una con el nombre del fabricante y otra con el número de productos que tiene. Ordene el resultado descendentemente por el número de productos.

4.17) Muestra el precio máximo, precio mínimo y precio medio de los productos de cada uno de los fabricantes. El resultado mostrará el nombre del fabricante junto con los datos que se solicitan.

4.18) Muestra el precio máximo, precio mínimo, precio medio y el número total de productos de los fabricantes que tienen un precio medio superior a 200€. No es necesario mostrar el nombre del fabricante, con el identificador del fabricante es suficiente.

4.19) Muestra el nombre de cada fabricante, junto con el precio máximo, precio mínimo, precio medio y el número total de productos de los fabricantes que tienen un precio medio superior a 200€. Es necesario mostrar el nombre del fabricante.

4.20) Calcula el número de productos que tienen un precio mayor o igual a 180€.

4.21) Calcula el número de productos que tiene cada fabricante con un precio mayor o igual a 180€.

4.23) Lista el precio medio los productos de cada fabricante, mostrando solamente el identificador del fabricante.

4.24) Lista el precio medio los productos de cada fabricante, mostrando solamente el nombre del fabricante.

4.25) Lista los nombres de los fabricantes cuyos productos tienen un precio medio mayor o igual a 150€.

4.26) Devuelve un listado con los nombres de los fabricantes que tienen 2 o más productos.

4.27) Devuelve un listado con los nombres de los fabricantes y el número de productos que tiene cada uno con un precio superior o igual a 220 €. No es necesario mostrar el nombre de los fabricantes que no tienen productos que cumplan la condición.

Ejemplo del resultado esperado:

## nombre | total

Lenovo | 2
Asus | 1
Crucial | 1

4.28) Devuelve un listado con los nombres de los fabricantes y el número de productos que tiene cada uno con un precio superior o igual a 220 €. El listado debe mostrar el nombre de todos los fabricantes, es decir, si hay algún fabricante que no tiene productos con un precio superior o igual a 220€ deberá aparecer en el listado con un valor igual a 0 en el número de productos.
Ejemplo del resultado esperado:

## nombre | total

Lenovo | 2
Crucial | 1
Asus | 1
Huawei | 0
Samsung | 0
Gigabyte | 0
Hewlett-Packard | 0
Xiaomi | 0
Seagate | 0

4.29) Devuelve un listado con los nombres de los fabricantes donde la suma del precio de todos sus productos es superior a 1000 €.

4.30) Devuelve un listado con el nombre del producto más caro que tiene cada fabricante. El resultado debe tener tres columnas: nombre del producto, precio y nombre del fabricante. El resultado tiene que estar ordenado alfabéticamente de menor a mayor por el nombre del fabricante.

---

5. Subconsultas (En la cláusula WHERE)
   Con operadores básicos de comparación

5.1) Devuelve todos los productos del fabricante Lenovo. (Sin utilizar INNER JOIN).

5.2) Devuelve todos los datos de los productos que tienen el mismo precio que el producto más caro del fabricante Lenovo. (Sin utilizar INNER JOIN).

5.3) Lista el nombre del producto más caro del fabricante Lenovo.

5.4) Lista el nombre del producto más barato del fabricante Hewlett-Packard.

5.5) Devuelve todos los productos de la base de datos que tienen un precio mayor o igual al producto más caro del fabricante Lenovo.

5.6) Lista todos los productos del fabricante Asus que tienen un precio superior al precio medio de todos sus productos.

---

6. Subconsultas con ALL y ANY

6.1) Devuelve el producto más caro que existe en la tabla producto sin hacer uso de MAX, ORDER BY ni LIMIT.

6.2) Devuelve el producto más barato que existe en la tabla producto sin hacer uso de MIN, ORDER BY ni LIMIT.

6.3) Devuelve los nombres de los fabricantes que tienen productos asociados. (Utilizando ALL o ANY).

6.4) Devuelve los nombres de los fabricantes que no tienen productos asociados. (Utilizando ALL o ANY).

---

7. Subconsultas con IN y NOT IN

7.1) Devuelve los nombres de los fabricantes que tienen productos asociados. (Utilizando IN o NOT IN).

7.2) Devuelve los nombres de los fabricantes que no tienen productos asociados. (Utilizando IN o NOT IN).

---

8 Subconsultas con EXISTS y NOT EXISTS

8.1) Devuelve los nombres de los fabricantes que tienen productos asociados. (Utilizando EXISTS o NOT EXISTS).

8.2) Devuelve los nombres de los fabricantes que no tienen productos asociados. (Utilizando EXISTS o NOT EXISTS).

---

9. Subconsultas correlacionadas

9.1) Lista el nombre de cada fabricante con el nombre y el precio de su producto más caro.

9.2) Devuelve un listado de todos los productos que tienen un precio mayor o igual a la media de todos los productos de su mismo fabricante.

9.3) Lista el nombre del producto más caro del fabricante Lenovo.

---

10. Subconsultas (En la cláusula HAVING)

10.1) Devuelve un listado con todos los nombres de los fabricantes que tienen el mismo número de productos que el fabricante Lenovo.
