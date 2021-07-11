# Enunciado de la práctica Full Stack Web Bootcamp XI Edición

## Creación de un sitio web para plataforma online de contenido digital.

### Consideraciones generales

- No se permite el uso de librerías y frameworks externos como Bootstrap, Spectre.css o similares.
- Se deberá crear una o más hojas de estilo CSS para aplicar el diseño deseado a la web.
- La página web debe visualizarse correctamente en las versiones actuales de Google Chrome, Mozilla Firefox y Microsoft Edge.
- No se requiere el uso de interacción mediante JavaScript.

---

## Diario
- 05/07/21 Comence la práctica, cree una estructura con grid y flex.
- 06/07/21 Volví a comenzar, no me gustaba lo que estaba haciendo y lo borré todo. Desarrollé la estructura con grid e intenté organizarme con los css separando los estilos por página y si eran globales o específicos.
- 07/07/21 El miércoles me puse manos a la obra con el header y el Nav, separandolo en dos secciones contenidas en la parte superior del grid, el primero llevaría solo el logo, el segundo contendria dos ul, uno con un menu burger y otro a la vista solo con accesos directos a los géneros y un botón para loguearse (o en este caso serviría como requisito obligatorio de la práctica de tener un botón que cerrase sesión). En estos momentos todavía no había creado el burger menú. 
Cree el main donde puse una imagen en grande del anime del momento con una breve descripción (como en Netflix). Y empecé con la section, tenía claro que quería que la estructura estuviese hecha con grid. Al principio quedé satisfecha con el resultado, y pense ingenua de mi, que iba bien de tiempo, había conseguido a grandes rasgos elaborar la página (fuí una ingenua).
- 08/07/21 Una vez contenta con la section me puse con con la ficha en miniatura (:hover) que estaba encima de cada imagen. Fué relativamente sencillo hasta que comence con el icono de *seguir* o *favorito* (una estrella en mi caso). Fue un dolor de cabeza, por separado me salía pero cuando quería implementarlo dentro del div *invisible* la cosa fué más complicada. No conseguia que se posicionará correctamente y lo acabé poniendo dentro del h2 (en un intento desesperado y poco elegante). Cree la página del login y del 404 (reciclé la plantilla del login para la página 404)
- 09/07/21 Aquí empezo el holocausto..... estuve hablando con unos compañeros y enseñandole mi práctica me comentarón un problema que habían tenido ellos y que yo también tenía pero que no sabía. No se podía presionar la estrellita (*seguir*) si estaba en versión móvil ya que estaba contenida dentro del div *invisible*, y con la versión móvil ese div no era visible. Al comprobarlo me di cuenta que mi página era un horror en versión móvil (empecé a desesperar), todo estaba movido, nada se visualizaba correctamente. Me arme de paciencia y comencé a modificar los parametros del grid y los estilos en el mediaquery. La estrellita pasó a estar siempre visible y fuera del div *invisible* pero dentro del article con el parámetro z-index. En este momento estaba agotada y mi idea inicial de un header y un nav por separado en la parte superior del diseño resulto ser una decisión horrible. Arrgelé el main, la section y el footer, pero renuncié al header y al nav.
- 10/07/21 Empecé a sentir sudores frios pensando que era sábado, que me faltaba la ficha con el video, el header, el nav y el burger menu (el odioso burger menu). Como primera medida modifiqué el grid y puse al header como una sección entera en la parte superior, dentro contendría el nav, para hacerlo responsive y más estético eliminé el menú de géneros en la versión móvil, y me puse a crear el burger menú, no fué tarea fácil ya que no quería exactamente lo que había hecho el profe, no quería que ocupase toda la pantalla, quería que estuviese debajo del header, y que solo ocupase un alto específico. Y comence la página de la ficha, una tarea que pensé que sería igual de fácil que el login. Pues no.... Quise reutilizar partes de la página principal *home.html*,  pensé que solo habría que cambiar el contenido, pues me lleve una desesperante sorpresa. Después de varias horas, varias conversación con un compañero y 2 paracetamol más tarde conseguí hacer la ficha con el video.
- 11/07/21 Hoy me he puesto a darle los últimos retoques, mirando el inspector del Chrome, Firefox y Edge, reduciendo imágenes, leyendo la práctica otra vez para que no se me quedará nada en el tintero y escribiendo esto.


## Apuntes

- La temática la quise hacer de Anime porque me pareció mas chuli.
- He mezclado unidades de medida sin ton ni son, me habría gustado ser más ordenada pero comenzo a faltarme tiempo.
- Me encantan las variables, creo que son super útiles, sobre todo con los colores. 
- He intentado usar la especificidad, me ha resultado muy muy útil, ya que tiendo a poner los mismos nombres a las clases sin darme cuenta y tengo mala memoria, así he conseguido salvar más de un desastre.
- Amo y odio el burger menu a partes iguales, es útil y estético pero un coñazo.
- La página principal se llama home en vez de index porque la páctica especificaba que la primera página debía ser el login, así que puse el login como index.html y la página principal como home.html.
- Quería hacer un carrusel pero me quedé sin tiempo (me da pena la verdad).
- No me gusta el diseño de la página de la ficha, me habría gustado volver ha hacerla de cero.
- Creo que el grid es un display grandioso para hacer estructuras y combinado con el flex se pueden hacer cosas muy guais.
- He aprendido muchísimo esta semana, pero mucho mucho. Mi práctica dista mucho de ser perfecta o estar bien hecha pero estoy contenta con haber resuelto todos los problemas de una forma u otra.
- He tenido muchos problemas con contener las imágenes como yo quería, al final me resultaba muchísimo más sencillo ponerlas en el css en forma de background-image.
- He invertido muchísimas horas, ha sido muy divertido y lo he pasado muy bien y muy mal. 
- Quería poner todas las imágenes diferentes y animes de verdad con sus respectivas fichas. Pero renuncié por falta de tiempo. 

## Fallos 

- Creo que esta todo un poco desordenado, intenté al principio ser muy estricta pero a medida que pasaba el tiempo iba creando más y más páginas de css y no se si fué una gran idea.
- Dentro del css no está ordenado como me gustaría y debo trabajar en ello.
- Debí usar menos unidades de medida.
- No se si he usado correctamente las etiquetas semánticas. Creo que me he equivocado en varias.
- Debí ser más conciente desde el principio de la versión móvil y no dejarlo para más adelante.
- He abusado del inspector, realizando cambios insitu para ver como quedaban sin plantearme de verdad que estaba probando (sobretodo cuando llevaba muchas horas)
- Pensar que iba bien de tiempo...

## Cosas que considero que debo mejorar

- Esctructurar mejor tanto dentro como fuera.
- Usar menos unidades de medida e investigar más a fondo cuando usar que.
- Tener más claro las etiquetas semánticas.
- Investigar mejor el posicionamiento clásico.
- Practicar mucho más el grid y el flexbox.
- Intentar ser más limpia.
- Intentar usar menos anidamientos (div dentro de div dentro de div...)
- No poner clases a todo, mirar que voy a usar y como. Practicar más la especificidad.
- En definitiva debo prácticar más todo e invertir tiempo, mucho tiempo.

Espero que le guste el resultado. 






