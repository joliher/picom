# picom
Picom es un programa que ayuda mejorar estéticamente el tema de tener varias ventanas abiertas, además de tener otras tantas opciones.
Esta es mi configuración personalizada (y bastante básica) de picom en la que ajusto cosas como el bordeado de las ventanas,
la opacidad de ventanas inactivas, el espacio o margin que se deja entre diferentes ventanas, entre otras cosas.
<br><br>
Este programa puede llegar a dar problema si se parte con la base de un sistema operativo que ya viene configurado con un
composite manager, por lo que hay 2 alternativas.<br>
Si sabes lo que estás haciendo, puedes modificar el composite que estés utilizando en ese momento para cambiarlo por picom (ya que solo puede estar ejecutandose uno al mismo tiempo). <br>
La otra opción es partir de un window manager (por ejemplo, bspwm), que te venga sin prácticamente nada, para que asi sea mucho más dificil encontrar 
otros programas que se estén ejecutando en paralelo y que puedan interferir con los programas que tu deseas utilizar.
<br><br>
Para poder utilizar picom, el fichero picom.conf se puede ubicar tanto en ~/.config/ como en ~/.config/picom/.
Si se desea saber información más en detalle sobre como manipular este fichero, hay ejemplos del fichero de configuración
en /usr/share/doc/picom/examples/picom.sample.conf
