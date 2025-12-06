descripcion del proyecto:
galeria visual sobre los personajes de el anime y manga Dragonball por el mangaka japones Akira Toriyama

Instrucciones para ver el proyecto en local:

1. clonar el repositorio url(https://github.com/Jhon-Gelvez/galeria-visual-Jhon-Gelvez.git)
   git clone https://github.com/Jhon-Gelvez/galeria-visual-Jhon-Gelvez.git
2. navegar a la carpeta galeria-visual-Jhon-Gelvez
3. abrirlo en VSC
   code .
4. usar la extension live server para vel el sitio en el navegador

Enlace a la página pública en GitHub Pages:
https://jhon-gelvez.github.io/galeria-visual-Jhon-Gelvez/

Decisiones de diseño
Por qué elegiste la paleta de colores.
-Fondo Principal #121212
Gris Oscuro Profundo. Evita el negro puro (#000000) ya que puede causar que los colores claros "floten" demasiado. Este tono ofrece un mejor contraste y es más suave para los ojos.

-Texto Principal #E0E0E0
Gris Muy Claro/Blanco Desactivado. No uses blanco puro (#FFFFFF). Este gris claro mejora la legibilidad y reduce el efecto de halo o vibración alrededor del texto claro sobre un fondo oscuro.


Cómo diseñaste los gradientes y su propósito.
background: radial-gradient(circle, #666 0%,#333 30%, #121212 70%);
da un efecto de iliminacion posterior para resaltar el elemento de la pagina

background: linear-gradient(90deg, #121212 0%, #888 50%,#121212 100%);
resalta el contenido central y se difumina en los bordes reslatando del fondo como una tira luminosa

background:
  radial-gradient(ellipse at 20% 20%, #35234b 0%, transparent 70%),
  radial-gradient(ellipse at 60% 20%, #2975bf 0%, transparent 70%),
  radial-gradient(ellipse at 100% 20%, #3d54b1 0%, transparent 70%),
  radial-gradient(ellipse at 100% 100%, #9f3c54 0%, transparent 70%),
  radial-gradient(ellipse at 20% 100%, #362d6f 0%, transparent 70%);
background-blend-mode:screen;
colores cosmicos para representar el poder del personaje resaltado

Cómo optimizaste las imágenes (si procede).
las imagenes estan en formato .webp que esta diseñado para la web y su peso es bajo menos de 500KB lo que permite una carga rapida del sitio web
