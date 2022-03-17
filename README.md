
Ejercicio 1
===========
Responde en este fichero a las siguientes preguntas: 

1. ¿Cómo se configura el email de manera global en GIT?
Respuesta: 

2. ¿Qué es un Pull Request?
Respuesta: hacer un pull request es la acción de validar algo que hayamos forkeado de un repositorio que no nos pertenece , lo modifiquemos y intentemos validar dichos cambios con el repositorio original.

3. ¿Para qué sirve HEAD en GIT?
Respuesta: el HEAD nos indica el estado en el que se encuentra comiteado el repositorio

4. ¿En cuántos estados diferentes puede estar un fichero en GIT?
Respuesta: en 3 estados diferentes 

5. ¿Qué número identifica de manera única a cada commit?
Respuesta: el hash que nos aparece al comprobar usando un git status

6. ¿Cómo retrocederías en los commits para tener el directorio de trabajo como lo tenías hace 3 commits?
Respuesta: git reset --hard HEAD~3

7. ¿Cómo explicarías un conflicto en GIT?
Respuesta: se crearía un conflicto por ejemplo cuando quisieramos mergear dos ramas donde hubiera lineas de texto que se sobrescribirían en el caso de mergear varias ramas, de forma que cuando intentas realizarlo el propio git te dice que existe un conflicto

8. ¿Con qué comando dejaríamos de tener el directorio bajo control de versiones?
Respuesta: git rm

9. ¿Cómo añadirías la URL de un repositorio remoto?
Respuesta: git remote add origin "url"

10. ¿Cómo explicarías qué ha ocurrido cuando tras la ejecución de un comando de GIT nos responde: "You are in 'detached HEAD' state"?
Respuesta:
