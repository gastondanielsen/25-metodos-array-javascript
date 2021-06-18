# 25 Métodos de Arrays en javascript que todo desarrollador debe conocer.

<p align="center">
 <a href="https://github.com/gdcodev" target="_blank"><img alt="Github" src="https://img.shields.io/badge/GitHub-%2312100E.svg?&style=for-the-badge&logo=Github&logoColor=white" /></a> <a href="https://www.facebook.com/gdcode7" target="_blank"><img alt="Facebook" src="https://img.shields.io/badge/facebook-%231DA1F2.svg?&style=for-the-badge&logo=facebook&logoColor=white" /></a> <a href="https://www.linkedin.com/in/gastondanielsen/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a> <a href="https://dev.to/gdcodev" target="_blank"><img alt="Dev" src="https://img.shields.io/badge/Dev-%2312100E.svg?&style=for-the-badge&logo=dev.to&logoColor=white" /></a>
</p>

JavaScript nos proporciona una serie de funciones predefinidas para el manejo de arrays.

Antes de comenzar se deben estar preguntando ¿Qué son los Arrays?, bien, se los puede definir como un conjunto de datos ordenados por posiciones y todos asociados en una sola variable. Los datos pueden ser de cualquier tipo de dato como, por ejemplo, una cadena de texto, un numero o un objeto. Se podrá acceder a estos datos de manera independiente o agrupándolos.

A continuación, se detallaran los métodos mas conocidos.

---

1. **map()** : Permite recorrer el array y modificar los elementos presentes en él, retornando un nuevo array con la misma longitud que el original.
![map](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/f25rnjq2j6wuhugxzi2a.png)
2. **filter()** : Recorre el array y retorna un nuevo array con aquellos elementos que pasen una determinada condición.
![filter](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/h6447ms3disaktwi74os.png)
3. **forEach()** : Permite iterar el contenido de un array. Recibe un callback que toma como parámetro el elemento actual de la iteración y el indice del mismo.
![forEach](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kxv5bwmtsptuohcd2dqr.png)
4. **find()** : Recorre el array y retorna la primera coincidencia del elemento que se busca.
![find](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/yipdbg0l4wnbt2ybm3bl.png)
5. **sort()** : Ordena los elementos del array y retorna el arreglo ordenado. Los elementos se ordenarán en orden ascendente (de la A a la Z) por defecto.
![sort](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/m28vi4f62mvduofxun0q.png)
6. **some()** : Itera el array y retorna un booleano si como mínimo uno de los elementos presentes en el array pasa una condición determinada. Recibe un callback que se encargara de preguntar aquello que queremos dentro del array.
![some](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/fzys22t49oe2b00p1bvj.png)
7. **every()** : Es similar al some(), ya que itera el array y retorna un booleano. Pero esta vez, para que dicho booleano sea true todos los elementos del array deberán pasar la condición dada.
![every](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/dqj5q7a3h3tkvwq0bqvh.png)
8. **concat()** : Se utiliza para unir dos o más arrays. Este método no cambia los arrays existentes, sino que devuelve un nuevo array.
![concat](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wfsr0g0uxu6crvby9x6z.png)
9.  **includes()** : Determina si un array incluye un determinado elemento y retorna un booleano según corresponda.
![includes](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/o6wdww82n63ptkkmt3qu.png)
10.  **join()** : Une todos los elementos de un array en una cadena. Podemos pasarle como parámetro el carácter de separación que debe agregar entre los elementos. 
![join](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/7im37ahu1s67c7pk32g8.png)
11. **reduce()** : Aplica una función a un acumulador y a cada valor de una array (de izquierda a derecha) para reducirlo a un único valor.
![reduce](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/sx68tqk220y3jyqahrkm.png)
12. **indexOf()** : Retorna el primer índice en el que se puede encontrar un elemento dado en el array, ó retorna -1 si el elemento no esta presente.
![indexOf](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xjwma9dcyod21ife9r80.png)
13.  **findIndex()** : Retorna el índice del primer elemento de un array que cumpla con la función de prueba proporcionada. En caso contrario devuelve -1.
![findIndex](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/e3vkm3xkxdrvbswp4v4j.png)
14.  **fill()** : Cambia todos los elementos de un array por un valor estático, desde el índice de inicio hasta el índice final. Retorna el array modificado.
![fill](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lfiwo362se6dpspsb0tp.png)
15. **push()** :  Añade uno o más elementos al final de un array y devuelve la nueva longitud del array.
![push](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/gmatruzexxgcawhm1p7j.png)
16. **pop()** : Elimina el último elemento de un array y lo devuelve. Este método cambia la longitud del array.
![pop](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/8gkwxrcgqrzzlcckkchr.png)
17. **shift()** : Elimina el primer elemento del array y lo retorna. Este método modifica la longitud del array.
![shift](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zblrb9uldw4blb605krc.png)
18. **unshift()** : Agrega uno o más elementos al inicio del array, y devuelve la nueva longitud del array.
![unshift](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/q333rq1o787jr99217ps.png)
19. **slice()** : Devuelve una copia de una parte del array dentro de un nuevo array empezando por inicio hasta fin (fin no incluido). El array original no se modificará.
![slice](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/nxdd2w5v7ufqcamtmghy.png)
20.  **reverse()** : Invierte el orden de los elementos de un array. El primer elemento pasa a ser el último y el último pasa a ser el primero.
![reverse](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/cx3jwoqesf2ruyzgc2lg.png)
21. **splice()** : Cambia el contenido de un array eliminando elementos existentes y/o agregando nuevos elementos.
![splice](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zs4zscoz5o72xbysw84u.png)
22. **lastIndexOf()** : Busca un elemento en un array y devuelve su posición. Comienza buscando por el final del array. Retorna -1 si el elemento no se encontrara.
![lastIndexOf](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/tmappcxwkv92gs15ypaz.png)
23. **flat()** : Crea una nuevo array con todos los elementos de sub-array concatenados recursivamente hasta la profundidad especificada.
![flat](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ell6dbackl27setargzv.png)
24. **isArray()** : Determina si el valor pasado es un Array.
![isArray](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/upfe6eaormv9mt1hlsvm.png)
25.  **from()** : Crea una nueva instancia de Array a partir de un objeto iterable.
![from](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zxsazaddecc4156sccdj.png)

---

<h4 align="center"><strong>¡NO PARES DE APRENDER!</strong></h4>
