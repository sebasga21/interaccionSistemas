Hoja de trabajo "M06_02_FT_02 - Interacció entre sistemes"

	- El primer ejercicio es un ejercicio muy simple para comprobar la funcionalidad de innerHTML() y document.write().
· Para comprobar el innerHTML() se ha hecho un botón que al presionarlo aparece un número random por pantalla.
· Para comprobar el document.write() lo he hecho añadiendo un valor random al principio ya que si se usa este método
  después de que se cargue la página web se borra todo el contenido de la página solo para mostrar el valor del document.write().

	- El segundo ejercicio se trara de un juego también muy simple para mostrar la funcionalidad de window.alert(), window.prompt(),
	window.confirm(), console.log() y varios métodos más del objeto console.
· Para comprobar el window.prompt() se pide el nombre de usuario al principio del juego.
· Para comprobar el window.alert() se usa el botón 'Reload', si se refresca la página aparece un mensaje que se ha refrescado correctamente.
· Para comprobar el window.confirm(), cuando se choca el personaje del juego se pide al usuario si quiere seguir jugando o no.
· Para comprobar el console.log() se ha puesto un contador de 3 segundos antes de empezar el juego y por cada segundo se muestra un mensaje en el modo consola.
· Además de esto se ha usado console.time() y console.timeEnd() para calcular el tiempo total de juego desde que empieza hasta que termina, también
  se ha usado el console.clear() para limpiar el modo consola para que no se acumulen muchas lineas y por último se ha usado console.count() para
  contar la cantidad de veces que el usuario salta en el juego.

	- El tercer ejercicio consta de 2 formularios, uno para registrarse y el segundo para iniciar sesión
· Se ha linkado bootstrap en el código html y se ha usado bootstrap para el diseño de las casillas de entrada de datos.
· Si dejas campos vacios te muestra mensajes de error, si al registrarte la contraseña no coincide con la repetición de la contraseña salta un error, 
  si todo esta correcto se guarda el usuario en un array, pero si el usuario y contraseña ya están registrados salta un mensaje de error. 
  Y si no estas registrado no puedes iniciar sesión, te salta un mensaje de error pero si estas registrado te da la bienvenida.
· Si todo está correcto antes de añadir los datos en el array se pide una confirmación al usuario con un window.confirm().