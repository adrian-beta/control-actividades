1. Flujo colaborativo
Supón que quieres colaborar con el repositorio de otro desarrollador. Ordena y explica los siguientes elementos:
6Push, 1Fork, 7Pull Request, 2Clone, 9Merge, 5Commit, 8Review, 3Branch y 4Modificar archivos. Agrega cualquier
operación que consideres necesaria.

Respuesta: Primero utilizamos Fork para tener una copia del proyecto en nuestra cuenta de github, despues utilizaremos Clone para crear un repositorio local, cuando tengamos el repositorio local usaremos Branch para saber en que rama estamos usando para evitar modificar el main usaremos git switch para crear una rama nueva donde nosotros trabajermos, lo siguiente sera instalar el entorno virtual en nuestra computadora ya que el repositorio no lo tiene usaremos python -m venv .venv  para instalarlo y .\.venv\Scripts\activate para activarlo una ves este esto activado instalaremos los requirements con pip install -r requirements.txt ahora si podemos empezar a modificar los archivos, una ves terminado nuestra aportacion relizaremos git status para saber que archivos modificamos y agregarlos al commit con git add . asi agregaremos todos los que fueron modificados despues de eso crearemos el commit para tener los cambios guardados, lo siguiente es realizar un push para que todo lo que hicimos en nuestro repositorio local se guarde en nuestra copia de la nube pero en la rama que creamos, despues crearemos un pull request para enviarselo al dueño del repositorio, una vez que el haya revisado(review) el pull request y este todo bien relizara el merge a su repositorio original, ya por ultimo usaremos sync fork para tener nuestra copia actualizada junto al original

2. Fork y Clone
Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”. Indica si es correcta
y explica la diferencia entre Fork y Clone.

Respuesta: Esta mal, Clone crea una copia del proyecto en tu computadora local quien crea una copia del proyecto dentro de tu cuenta de github es Fork

3. Pull Request
Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: ¿los cambios ya forman parte
del repositorio original? ¿Qué debe ocurrir para incorporarlos?

Respuesta: No forman parte aun, se necesita realizar un pull request para que el dueño del repositorio original confirme los cambios que hiciste despues de revisarlos y asi formen parte del repositorio original

4. Request Changes
El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear
otro Pull Request y qué ocurre cuando realizas nuevamente push.

Respuesta: Primero revisar que cambios debo realizar en mis archivos para tener los requisitos que la otra persona me esta pidiendo, si puedo hacer otro Pull Request si la persona que me pidio los cambios cerro el anterior, al hacer un push sube los cambios a mi copia del repositorio original y ahi enviar el nuevo pull request

5. Merge y repositorio local
Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no
contiene los cambios. Explica por qué sucede y qué operación debe realizarse.

Respuesta: Esto sucede por que solo se actualizo el repositorio de la nube para que el repositorio local se actualize con los nuevos cambios debe utilizar git pull para descargar todos los cambios de la nube a su repositorio local


6. Sync Fork
Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué herramienta
utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull.

Respuesta: Dentro del mismo Fork que creaste puedes usar Sync Fork para sincronizar tu Fork con el original  y de esta manera tenerlo actualizado, por ultimo en el Clone que hiciste del repositorio tienes que estar en la rama Main para usar el git pull y actualizar tu repositorio local