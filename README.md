# dwes-examen
## Javi Barrientos

4- Modificar para mostrar dolar, listado, read_one
`index.php line 91 $ before {$price}`
`read_one line 68 $ before <?php`

5- Explica como se guarda la imagen de un producto, formato, comprobaciones, que se guarda, donde esta.
__El formato del campo es blob__

__Las comprobaciones son si es una imagen real, si es una imagen, el tipo de imagen esta aceptada(png, jpg, gif), comprobar que no exista otra con el mismo nombre, que no se pase del tamaño permitido, comprobar que la carpeta existe.__

__La imagen esta guardada en el servidor en una carpeta llamada uploads, lo que tenemos en la bbdd es el nombre de la imagen__

__La podemos recuperar accediendo a la carpeta uploads__

6- Actulizar imagen
