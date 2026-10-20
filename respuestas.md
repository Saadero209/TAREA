Preguntas 1

¿Para qué sirven user.name y user.email? ¿Dónde aparecerán más adelante?
Son tu firma digital en Git para identificar quien hizo cada cambio
aparecen en el historial de commits de GitHub

¿Por qué GitHub no permite usar la contraseña de la cuenta para subir código por HTTPS?
Por seguridad para evitar riesgos si alguien la descubre.

Preguntas 2
¿Por qué no se debe subir la carpeta .venv al repositorio?
Por que ocupa mucho espacio con librerias locales que se pueden reinstalar automaticamente en cualquier ordenador

¿Qué significaba el color rojo antes del commit? ¿Y qué color tendría un archivo modificado después?
Antes del commit indica los archivos modificados o nuevos y despues del commit suele ser de color verde

Preguntas 3
¿Qué es origin?
Es el nombre que usa gitpara referirse al servidor donde esta alojado tu proyecto en GitHub

Explica con tus palabras la diferencia entre commit y push.
El commit lo guarda tus cambios en tu ordenador y el push lo sube a GitHub

Preguntas 4
¿Por qué es mejor hacer dos commits pequeños que uno grande con todo?
Facilita encontrar errores puntuales

Escribe un ejemplo de mensaje de commit malo y explica por qué lo es.
Hacer un mensaje com "escribi algo" por que no explica que parte del codigo cambie

Preguntas 5
¿Qué ventaja tiene trabajar en una rama en lugar de directamente en main?
Permite experimentar y hacer cambios de forma segura

¿Qué es una fusión fast-forward y por qué se ha producido aquí?
Cuando el codigo de main no ha cambiado nada desde q cree mi rama

Preguntas 6
¿Por qué Git no pudo fusionar automáticamente esta vez y sí en la fase 5?
Por que se modificaron exactamente en la misma linea

¿Qué habría pasado si hubieras pulsado Accept Theirs?
Habria descartado mis cambios locales de ahora mismo

Preguntas 7
En un equipo, ¿por qué conviene hacer Update Project antes de empezar a trabajar cada día?
Para descargar los ultimos cambios de las personas.

Preguntas 8
¿Qué aporta una pull request frente a fusionar directamente en local como en la fase 5?
Permite revisar el código en equipo, discutir mejoras y hacer pruebas automaticas

¿Por qué el commit hecho después de crear la PR apareció en ella sin hacer nada más?
Esta conectada directamente a la rama remota 

Preguntas 9
¿Qué diferencia hay entre Pop y Apply al recuperar un stash?
Pop aplica los cambios guardados y los borra stash
Apply Los aplica pero los mantiene guardadospor si lo necesitas otra vez de nuevo

Preguntas 10
Completa: Rollback sirve para descartar cambios no guardados; Amend para modificar el último commit; Undo Commit para deshacer del commit; Revert para crear un nuevo commit que anule anteriormente.


¿Por qué pudiste recuperar borrador.txt si Git nunca lo había guardado?
Gracias a la función local History

Preguntas 11
¿Cuántos commits tiene main en total? ¿Cuántos son commits de merge?


¿Qué commit introdujo la validación del rango? Indica los 7 primeros caracteres de su hash.
