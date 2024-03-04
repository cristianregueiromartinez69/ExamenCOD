PASOS QUE VAMOS DANDO EN EL EXAMEN DE COD

***Revisar el programa del que hicimos el fork***

El primer paso que vamos a hacer será revisar el programa, para verificar que se están cumpliendo todas las tareas propias del mismo.

**Revisar la Main**

En la rama main hemos comprobado que todo está correcto, así que no realizamos ninguna modificación

**Revisar la rama datos**

En la rama de datos, vemos que hay una conexión a la base de datos con 2 metodos
1. el primero de ellos se conecta con la base de datos y lanza una excepción, en caso de que no logre realizar la conexión
2. el segundo metodo, cierra la conexion con la base de datos
   Después de comprobar todo, vemos que se cumplen todas las funcionalidades de esa rama, por lo tanto no realizamos ninguna modificación

**Revisar la rama Interface**

En la rama interface revisamos que el codigo está bien, pero hay un problema en los commits. Hay uno qur no debe de estar ahí y está, por tanto tenemosd que solucionarlo.

**Retirar el commit que no queremos de la rama interface**

Listo, hemos retirado el ultimo commit que no queríamos incluir. Para eso hemos realizado el siguiente comando:
1. Nos ponemos en el commit anterior al cual queremos borrar
2. click derecho y le damos a reset current branch to here
3. le damos a la opcion del mixed, ya que el codigo nos interesa, pero el commit no
4. Por lo tanto la opcion del hard-mixed, me pareció la más optima. Borra el commit, pero no el codigo

**Fusionar todos los cambios realizados en la rama main**

Una vez hemos hecho todo lo anterior, tenemos que fusionar los cambios en la rama main con el merge squash
Objetivo que tenemos que conseguir:
**Realizar un solo commit en la main con el merge squash**
¿Como hacerlo?
Yo lo que hice fue crear una nueva rama fusiones, en la que se fusionan las dde bases de datos y las de interface. Luego se hace squash a la main con la rama que hemos creada.
Aunque creo que no me salio

**Pusheamos todo**
Ya hicimos push de la main, que creo que me salió todo mal, peor se hizo lo que se pudo
1. hacemos el push de la rama readme con el readme de la misma manera de la que hicimos con cualquier rama
