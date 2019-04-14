
1.	Crear un repositorio en GitHub con el nombre “Practica02 – Mi Sitio Web (CSS)”


(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/repo.png)


2.	Crear una carpeta PRACTICA3 la cual tendrá las carpetas de la practica2 en la cual modificaremos esta carpeta tendra dos subcarpetas la una se llamara html: en la cual guardaremos nuestras páginas HTML y la otra se llamara imágenes: en ella guardaremos las imágenes con las que trabajaremos además agrgaremos una nueva carpeta llamada css el cual tendrá los archivos doscolumas, trescolumnas y reglas.

3.	Abrimos la carpeta creada en la aplicación Visual stude code y creamos los archivos en las cuales trabajaremos.





     DESARROLLO DE LOS ARCHIVOS CSS.
     1.reglas.css
    A.	Reglas.css cuenta con la siguiente estructura:


(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/1.png)

•	La regla imgtamaño   es un id que  nos ayuda a establecer en tamaño predeterminado para las imágenes que tenemos en los archivos html.
•	la regla posicionimg   es una clase que nos ayuda con una posición centrada de los elementos en las páginas html.
•	La regla tamañotexto  es una clase que  da un tamaño al texto.
•	La regla finpagina es un id que permite colocar el pie de página al final  y el margin-right da un margen a al pie de página.
•	La regla ubicacióntexto  es una clase que nos permite la ubicación de un texto hacia la derecha.
•	La regla colorinstagram es una clase la cual nos da un color de fondo para la sección aquí se establece un tipo de borde  y su grosor.
•	La regla colorfacebookes una clase la cual nos da un color de fondo para la sección aquí se establece un tipo de borde  y su grosor
•	La regla colorsnapchat es una clase la cual nos da un color de fondo para la sección aquí se establece un tipo de borde  y su grosor.
•	La regla colortwitter es una clase la cual nos da un color de fondo para la sección aquí se establece un tipo de borde  y su grosor.
•	La regla colorwhatsapp es una clase la cual nos da un color de fondo para la sección aquí se establece un tipo de borde  y su grosor.
•	La regla colormenu es una clase la cual nos da un color de fondo para la sección aquí se establece un tipo de borde  y su grosor.
•	La regla colorarticulo es una clase la cual nos da un color de fondo para la sección aquí se establece un tipo de borde  y su grosor.
•	La regla coloranexos es una clase la cual nos da un color de fondo para la sección aquí se establece un tipo de borde  y su grosor.
•	La regla textocentrado es una clase que  nos da un margen auto y tipo de letra.
•	La regla texto esta es una que nos permite subrayar un texto.
•	La regla body es una clase que nos permite crear las cajas que contendrán los ítems del menú.
•	La regla caja1 es un id que nos da un borde un estilo del borde  con un espacio entre cada una.
•	La regla caja2 es un id que nos da un borde un estilo del borde  con un espacio entre cada una.
•	La regla caja3 es un id que nos da un borde un estilo del borde  con un espacio entre cada una.
•	La regla caja4 es un id que nos da un borde un estilo del borde  con un espacio entre cada una.
•	La regla caja5 es un id que nos da un borde un estilo del borde  con un espacio entre cada una.

2.dosColumnas.css
A.	dosColumnas.css cuenta con la siguiente estructura:

•	la regla menuprincipales un id esta regla que nos permite colocar el texto en una ubicación.
•	la regla contenido es un id esta regla que nos permite justificar el texto  dar un margen y dar un espacio entre el borde y el contenido, también permite dar una ubicación.


3.tresColumnas.css
A.	tresColumnas.css cuenta con la siguiente estructura:
•	 la regla menu un id esta regla que nos permite colocar el texto en una ubicación.
•	la regla articulo es un id esta regla que nos permite justificar el texto  dar un margen y dar un espacio entre el borde y el contenido, también permite dar una ubicación.
•	la regla anexos un id esta regla que nos permite colocar el texto en una ubicación y darle un salto entre lineas.

EVIDENCIA DE LOS ARCHIVOS CSS.
•	REGLAS

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/reg.png)

•	DOSCOLUMNAS


(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/d.png)

•	TRESCOLUMNAS


(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/colum3.png)


VALIDACION DE LOS ARCHIVOS CSS.
•	REGLAS

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/regla.png)


•	DOSCOLUMNAS


(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/fa.png)


•	TRES COLUMNAS

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/tres.png)


IMPLEMENTACION EN  LAS PAGINAS HTML.

1.	Facebook.html
A.	Facebook.html cuenta con la estructura:

<link href="../css/dosColumnas.css" rel="stylesheet" type="text/css"/>
    <link href="../css/reglas.css" rel="stylesheet" type="text/css"/>

Primero se debe importar los archivos de la carpeta css.

header >   dentro de esta etiqueta se implementa la clase posicionimg :

Para centrar la imagen y el titulo.
<nav class="colorfacebook" id="menuprincipal" >
            
            <div >
                    <ul  class="tamañotexto, posicionimg" >
                            <h1> MENU </h1> 

En la etiqueta nav se  implementa la clasecolorfacebook para dar el color  y el id menúprincipal para la ubicación del texto. En la etiqueta  ul se implementa la clase tamañotexto y posicionimg para darle mayor tamaño al texto y posicionarlo al centro.

Se implementa la etiqueta div la cual tendrá la clase colorfacebook y un id contenido para darle color a la sección y ubicar el texto en una parte del archivo.

En la etiqueta header de la seccion  se implementa la clase posicionimg  para darle una posición a la imagen de la pagina.

footer>  dentro de esta etiqueta se cuenta con :

una clase colorfacebook y un id de fin de pagina que ayuda a darle color a la sección y para que se quede al final.

B.	 Evidencia de la correcta estructuración de las páginas HTML. 

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/1.png)


C.	La evidencia de la validación de cada página HTML. 

	
(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/2.png)


   2. instagram.html
A.	instagram.html cuenta con la estructura:

<link href="../css/dosColumnas.css" rel="stylesheet" type="text/css"/>
    <link href="../css/reglas.css" rel="stylesheet" type="text/css"/>

Primero se debe importar los archivos de la carpeta css.


header >   dentro de esta etiqueta se implementa la clase posicionimg :Para centrar la imagen y el titulo.

En la etiqueta nav se  implementa la colorfinstagram para dar el color  y el id menúprincipal para la ubicación del texto. En la etiqueta  ul se implementa la clase tamañotexto y posicionimg para darle mayor tamaño al texto y posicionarlo al centro.

Se implementa la etiqueta div la cual tendrá la clase colorfinstagram y un id contenido para darle color a la sección y ubicar el texto en una parte del archivo.

En la etiqueta header de la seccion  se implementa la clase posicionimg  para darle una posición a la imagen de la pagina.

footer>  dentro de esta etiqueta se cuenta con :

una clase colorfinstagram y un id de fin de pagina que ayuda a darle color a la sección y para que se quede al final.

B.	Evidencia de la correcta estructuración de las páginas HTML.


(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/3.png)

A.	La evidencia de la validación de cada página HTML. 

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/4.png)


   3. snapchat.html
A.	snapchat.html cuenta con la estructura:


<link href="../css/dosColumnas.css" rel="stylesheet" type="text/css"/>
    <link href="../css/reglas.css" rel="stylesheet" type="text/css"/>

Primero se debe importar los archivos de la carpeta css.


header >   dentro de esta etiqueta se implementa la clase posicionimg :Para centrar la imagen y el titulo.

En la etiqueta nav se  implementa la colorsnapchat para dar el color  y el id menúprincipal para la ubicación del texto. En la etiqueta  ul se implementa la clase tamañotexto y posicionimg para darle mayor tamaño al texto y posicionarlo al centro.

Se implementa la etiqueta div la cual tendrá la clase colorsnapchat y un id contenido para darle color a la sección y ubicar el texto en una parte del archivo.

En la etiqueta header de la seccion  se implementa la clase posicionimg  para darle una posición a la imagen de la pagina.

footer>  dentro de esta etiqueta se cuenta con :

una clase colorsnapchat y un id de fin de pagina que ayuda a darle color a la sección y para que se quede al final.

B.	Evidencia de la correcta estructuración de las páginas HTML.

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/5.png)

C.	La evidencia de la validación de cada página HTML. 


(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/6.png)


4. twitter.html
A.	twitter.html cuenta con la estructura:

Primero se debe importar los archivos de la carpeta css.


header >   dentro de esta etiqueta se implementa la clase posicionimg :Para centrar la imagen y el titulo.

En la etiqueta nav se  implementa la colortwitter para dar el color  y el id menúprincipal para la ubicación del texto. En la etiqueta  ul se implementa la clase tamañotexto y posicionimg para darle mayor tamaño al texto y posicionarlo al centro.

Se implementa la etiqueta div la cual tendrá la clase colortwitter y un id contenido para darle color a la sección y ubicar el texto en una parte del archivo.

En la etiqueta header de la seccion  se implementa la clase posicionimg  para darle una posición a la imagen de la pagina.

footer>  dentro de esta etiqueta se cuenta con :

una clase colortwitter y un id de fin de pagina que ayuda a darle color a la sección y para que se quede al final.

B.	Evidencia de la correcta estructuración de las páginas HTML.

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/7.png)

C.	La evidencia de la validación de cada página HTML.

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/8.png)


5.whatsapp.html
A.	whatsapp.html cuenta con la estructura:

Primero se debe importar los archivos de la carpeta css.


header >   dentro de esta etiqueta se implementa la clase posicionimg :Para centrar la imagen y el titulo.

En la etiqueta nav se  implementa la colorwhatsapp para dar el color  y el id menúprincipal para la ubicación del texto. En la etiqueta  ul se implementa la clase tamañotexto y posicionimg para darle mayor tamaño al texto y posicionarlo al centro.

Se implementa la etiqueta div la cual tendrá la clase colorwhatsapp y un id contenido para darle color a la sección y ubicar el texto en una parte del archivo.

En la etiqueta header de la seccion  se implementa la clase posicionimg  para darle una posición a la imagen de la pagina.

footer>  dentro de esta etiqueta se cuenta con :

una clase colorwhatsapp y un id de fin de pagina que ayuda a darle color a la sección y para que se quede al final.


B.	Evidencia de la correcta estructuración de las páginas HTML.

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/9.png)

C.	La evidencia de la validación de cada página HTML.

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/10.png)


5.index.html
A.	index.html cuenta con la estructura:
Primero se debe importar los archivos de la carpeta css.


header >   dentro de esta etiqueta se implementa la clase posicionimg :Para centrar la imagen y el titulo.

En la etiqueta nav se  implementa la colormenu para dar el color  y el id menúprincipal para la ubicación del texto. En la etiqueta  ul se implementa la clase tamañotexto para darle mayor tamaño al  texto.
Se implementa la etiqueta div la cual tendrá la clase colorarticulo y un id articulo para darle color a la sección y ubicar el texto en una parte del archivo.dentro de las etiquetas h2  se encuentra la clase texto y posición imagen para centrar el titulo en la etiqueta ul se tiene  la clase tamañotexto para agrandar el texto.

En la etiqueta header de la seccion  se implementa la clase posicionimg  para darle una posición a la imagen de la pagina.
Antes  de la etiqueta anside  se cierra la etiqueta div. Dentro de la etiqueta anside estará la clase coloranexos  que dara color a la seccion

footer>  dentro de esta etiqueta se cuenta con :

una clase colorfin y un id de fin de pagina que ayuda a darle color a la sección y para que se quede al final.


B.	Evidencia de la correcta estructuración de las páginas HTML.

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/11.png)


A.	La evidencia de la validación de cada página HTML.

(https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-/blob/master/evidencia/12.png)


6.INFORMACIÓN DE GITHUB (USUARIO Y URL DEL REPOSITORIO DE LA PRÁCTICA) 
	
Usuario: KellyReyes
URL: https://github.com/KellyReyes/Practica02-Mi-Sitio-Web-CSS-.git
