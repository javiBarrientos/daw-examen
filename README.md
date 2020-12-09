# dwes-examen
## Javi Barrientos

Directorio remoto

http://javiphpsite.sytes.net/php-beginner-crud-level-1/

4- Modificar para mostrar dolar, listado, read_one
`index.php line 91 $ before {$price}`
`read_one line 68 $ before <?php`

5- Explica como se guarda la imagen de un producto, formato, comprobaciones, que se guarda, donde esta.

__El formato del campo es blob__


__Las comprobaciones son si es una imagen real, si es una imagen, el tipo de imagen esta aceptada(png, jpg, gif), comprobar que no exista otra con el mismo nombre, que no se pase del tamaño permitido, comprobar que la carpeta existe.__


__La imagen esta guardada en el servidor en una carpeta llamada uploads, lo que tenemos en la bbdd es el nombre de la imagen__


__La podemos recuperar accediendo a la carpeta uploads__


6- Actulizar imagen

__Dentro del fichero update linea 30 añadimos la imagen para el select de la query, linea 46 creamos la row, linea 66 update de la query, linea 77 metodo post de la imagen, linea 83 añadir el parametro de la imagen, en el formulario añadir tr de input__
