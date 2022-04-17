# MW010_Maquetación web [2021/22]

## Dockerfile

In the project, you need to put your index.html in the directory /public-html and later, into the directory 
mpwar-maquetacion-web.

Then, run the commands to build and run the Docker image:

```
$ docker build -t mpwar-maquetacion-web-practica-1 .
$ docker run -dit --name maquetacion-web-app -p 3000:80 mpwar-maquetacion-web-practica-2 

```

## Ejercicio Nº1

Crear una página web tal y como aparece en el archivo P1.png utilizando todo lo aprendido sobre HTML, e investigando algunos detalles.

Contenido

* Los enlaces del principio deben llevar a cada uno de los apartados.
* Las líneas separadoras son elementos <hr>.
* Para las imágenes podéis usar un servicio de placeholders como Picsum. * El texto puede ser Lorem Ipsum.
* Podéis inventaros la action de los formularios, pero usad post como método.
* Podéis usar este video en el espacio patrocinado. Debe reproducirse automáticamente en bucle y en silencio, sin que el usuario pueda controlarlo. El tamaño en la página es de 240x135.
* Los campos del formulario de "demo" deberían tener el valor por defecto que se aprecia en la captura.
* El enlace con el correo electrónico debe componer un mensaje a esa dirección con el asunto "¡Hola!"

Consideraciones:

* Se tendrá muy en cuenta la semántica del código entregado.
* Es crítico validar el código antes de la entrega. Los warnings bajan nota, y los errores implican suspenso directo.
* Aunque se debe intentar imitar el resultado, el estilo puede variar ligeramente respecto a la captura, según navegador y estructura interna.

Entrega

* Aunque solo creéis un archivo .html, entregad un comprimido que siga el formato login.zip o login.rar.
