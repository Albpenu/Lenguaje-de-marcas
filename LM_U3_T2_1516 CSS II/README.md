# LM_U3_T2_1516:CSS II

Ejercicio 1:

A partir del código HTML , añadir los estilos necesario para obtener el resultado mostrado más abajo. El archivo html y el archivo css deben meterse en una carpeta que se llame Ej1.


<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<title>Ejercicio de selectores</title>
</head>
 
<body>
 
<div id="primero">
<p>Lorem ipsum dolor sit amet, <a href="#">consectetuer adipiscing elit</a>. Praesent blandit nibh at felis. Sed nec diam in dolor vestibulum aliquet. Duis ullamcorper, nisi non facilisis molestie, <em>lorem sem aliquam nulla</em>, id lacinia velit mi vestibulum enim.</p>
 
</div>
 
<div class="normal">
<p>Phasellus eu velit sed lorem sodales egestas. Ut feugiat. <span><a href="#">Donec porttitor</a>, magna eu varius luctus,</span> metus massa tristique massa, in imperdiet est velit vel magna. Phasellus erat. Duis risus. <a href="#">Maecenas dictum</a>, nibh vitae pellentesque auctor, tellus velit consectetuer tellus, tempor pretium felis tellus at metus.</p>
 
<p>Cum sociis natoque <em class="especial">penatibus et magnis</em> dis parturient montes, nascetur ridiculus mus. Proin aliquam convallis ante. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nunc aliquet. Sed eu metus. Duis justo.</p>
 
<p>Donec facilisis blandit velit. Vestibulum nisi. Proin volutpat, <em class="especial">enim id iaculis congue</em>, orci justo ultrices tortor, <a href="#">quis lacinia eros libero in eros</a>. Sed malesuada dui vel quam. Integer at eros.</p>
</div>
 
</body>
</html>




El resultado final debe ser lo más parecido posible a la siguiente imagen:
![Alt text](https://github.com/Albpenu/Lenguaje-de-marcas/raw/master/LM_U3_T2_1516%20CSS%20II/practica1.gif?raw=true)
 

Ejercicio 2:

A partir del código HTML , añadir los estilos necesario para obtener el resultado mostrado más abajo. El archivo html y el archivo css deben meterse en una carpeta que se llame Ej2:

 

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Ejercicio de selectores</title>
</head>
 
<body>
<h1 id="titulo">Lorem ipsum dolor sit amet</h1>
 
<p>Nulla pretium. Sed tempus nunc vitae neque. <strong>Suspendisse gravida</strong>, metus a scelerisque sollicitudin, lacus velit 
ultricies nisl, nonummy tempus neque diam quis felis. <span class="destacado">Etiam sagittis tortor</span> sed arcu sagittis tristique.</p>
 
<h2 id="subtitulo">Aliquam tincidunt, sem eget volutpat porta</h2>
 
<p>Vivamus velit dui, placerat vel, feugiat in, ornare et, urna.  <a href="#">Aenean turpis metus, <em>aliquam non</em>, tristique in</a>, pretium varius, sapien. Proin vitae nisi.  Suspendisse <span class="especial">porttitor purus ac elit</span>. Suspendisse eleifend odio at dui. In in elit sed metus pretium elementum.</p>
 
<table summary="Descripción de la tabla y su contenido">
<caption>Título de la tabla</caption>
<thead>
  <tr>
    <th scope="col"></th>
    <th scope="col" class="especial">Título columna 1</th>
    <th scope="col" class="especial">Título columna 2</th>
  </tr>
</thead>
 
<tfoot>
  <tr>
    <th scope="col"></th>
    <th scope="col">Título columna 1</th>
    <th scope="col">Título columna 2</th>
  </tr>
</tfoot>
 
<tbody>
  <tr>
    <th scope="row" class="especial">Título fila 1</th>
    <td>Donec purus ipsum</td>
    <td>Curabitur <em>blandit</em></td>
  </tr>
  <tr>
    <th scope="row">Título fila 2</th>
    <td>Donec <strong>purus ipsum</strong></td>
    <td>Curabitur blandit</td>
  </tr>
</tbody>
</table>
 
<div id="adicional">
<p>Donec purus ipsum, posuere id, venenatis at, <span>placerat ac, lorem</span>. Curabitur blandit, eros sed gravida aliquet, risus justo 
porta lorem, ut mollis lectus tortor in orci. Pellentesque nec augue.</p>
 
<p>Fusce nec felis eu diam pretium adipiscing. <span id="especial">Nunc elit elit, vehicula vulputate</span>, venenatis in, 
posuere id, lorem. Etiam sagittis, tellus in ultrices accumsan, diam nisi feugiat ante, eu congue magna mi non nisl.</p>
 
<p>Vivamus ultrices aliquet augue. <a href="#">Donec arcu pede, pretium vitae</a>, rutrum aliquet, tincidunt blandit, pede. 
Aliquam in nisi. Suspendisse volutpat. Nulla facilisi. Ut ullamcorper nisi quis mi.</p>
</div>
 
</body>
</html>
 

El resultado final debe ser lo más parecido posible a la siguiente imagen:
![Alt text](https://github.com/Albpenu/Lenguaje-de-marcas/raw/master/LM_U3_T2_1516%20CSS%20II/practica2.gif?raw=true)


Ejercicio 3:

A partir del código HTML y CSS proporcionados, determinar las reglas CSS necesarias para añadir los siguientes márgenes y rellenos. Originalmente el documento es como se ve en la primera imagen:
![Alt text](https://github.com/Albpenu/Lenguaje-de-marcas/blob/master/LM_U3_T2_1516%20CSS%20II/practica3.gif?raw=true)


Deben aplicarse las siguientes reglas CSS:

1. El elemento #cabecera debe tener un relleno de 1em en todos los lados.
2. El elemento #menu debe tener un relleno de 0.5em en todos los lados y un margen inferior de 0.5em.
3. El resto de elementos (#noticias, #publicidad, #principal, #secundario) deben tener 0.5em de relleno en todos sus lados, salvo el elemento #pie, que sólo debe tener relleno en la zona superior e inferior.
4. Los elementos .articulo deben mostrar una separación entre ellos de 1em.
5. Las imágenes de los artículos muestran un margen de 0.5em en todos sus lados.
6. El elemento #publicidad está separado 1em de su elemento superior.
7. El elemento #pie debe tener un margen superior de 1em.

El resultado final deberá ser algo así:
![Alt text](https://github.com/Albpenu/Lenguaje-de-marcas/blob/master/LM_U3_T2_1516%20CSS%20II/practica3-solucion.gif?raw=true)



Entregar el archivo html y css en una carpeta que se llame Ej3.