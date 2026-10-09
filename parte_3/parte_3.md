1. Analiza
git status
git add README.md
git commit -m "Actualiza documentación"
git push
Explica qué ocurre en cada instrucción.

Respuesta: git status: Se verifica el estado de cada uno de los archivos y menciona cuales de ellos han sido modificados
git add README.md: Se prepara el archivo modificado para el proximo commit
git commit -m "Actualiza documentación": Guarda los cambios que realizaste en el historial local de Git.
git push: Envia los commits locales al repositorio de la nube

2. Identifica qué falta
Caso A
Modificar archivo
↓
git add .
↓
¿?
↓
git push
Indica qué operación falta y explica su función.

Respuesta: Faltaria utilizar git commit para guardar los cambios que realizaste 


Caso B
Repositorio GitHub
↓
¿?
↓
Repositorio local
Indica qué operación utilizarías y explica por qué.

Respuesta: git Clone por que de esta manera tengo una copia de manera local


Caso C
Repositorio remoto actualizado
↓
¿?
↓
Repositorio local actualizado
Indica qué operación utilizarías y explica por qué.

Respuesta: sync fork por que esta operacion sincroniza o actualiza la informacion del fork que tenemos del repositorio original