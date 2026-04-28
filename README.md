Sistema Experto — Guía de Trabajo

Este repositorio se utiliza para desarrollar un sistema experto de forma colaborativa utilizando Jupyter Notebooks y GitHub.

El objetivo es que todos los miembros del equipo puedan trabajar en paralelo sin interferencias, organizando el trabajo mediante ramas y notebooks separados.

⸻

Estructura del proyecto

Dentro del repositorio existe una carpeta llamada “notebooks”. En ella se encuentran los distintos archivos de trabajo del sistema experto.

Cada archivo tiene una función concreta y no debe ser modificado por personas que no estén asignadas a él.

⸻

Distribución del trabajo

Cada miembro del equipo trabaja en una parte distinta del sistema experto.

Una persona se encarga de definir las reglas del sistema.
Otra persona se encarga del motor de inferencia, es decir, la lógica que aplica las reglas.
Otra persona se encarga de la base de conocimiento, donde se definen los datos y hechos del sistema.
La última persona se encarga de las pruebas, validando que el sistema funciona correctamente con distintos ejemplos.

⸻

Uso de ramas

Cada persona debe trabajar únicamente en su propia rama.

No se debe trabajar directamente sobre la rama principal.

Antes de empezar a trabajar, es obligatorio actualizar la rama principal y luego integrar esos cambios en la rama personal. Esto evita conflictos y pérdida de información.

⸻

Flujo de trabajo

Antes de empezar a trabajar, cada persona debe asegurarse de tener la versión más actualizada del proyecto.

Después, debe cambiar a su propia rama y trabajar únicamente en ella.

Una vez realizados los cambios, se deben guardar y subir al repositorio con un mensaje claro que describa lo que se ha hecho.

Este proceso debe repetirse cada vez que se trabaje en el proyecto.

⸻

Normas importantes

No trabajar nunca directamente en la rama principal.
No modificar archivos que no correspondan a tu parte.
No trabajar sin haber actualizado previamente el proyecto.
Mantener los cambios organizados y claros.

Cada persona debe centrarse únicamente en su notebook asignado para evitar conflictos.

⸻

Contenido de cada notebook

El notebook de reglas contiene la definición de las reglas del sistema experto.

El notebook del motor de inferencia contiene la lógica que evalúa las reglas y produce resultados.

El notebook de base de conocimiento contiene los datos de entrada y los hechos iniciales del sistema.

El notebook de pruebas contiene ejemplos de uso y validación del sistema.

⸻

Integración final

Cuando todos los miembros hayan terminado su parte, se unirán todas las ramas en la rama principal.

Este proceso se realizará con cuidado para asegurar que todo el sistema funciona correctamente de forma conjunta.

⸻

Objetivo final

El objetivo es obtener un sistema experto completo, bien estructurado y documentado, donde el código y las explicaciones estén integrados dentro de los notebooks.

Si se siguen estas normas, el trabajo será más rápido, ordenado y sin conflictos.

Antes de trabajar (IMPORTANTE)

git checkout main
git pull
git checkout tu_rama
git merge main

Esto asegura que estás trabajando con la versión más actualizada del proyecto.

⸻

Después de hacer cambios

Cuando termines de editar tu notebook:
git add .
git commit -m "explicación breve del cambio"
git push

Esto guarda y sube tus cambios al repositorio.

⸻

Nota importante

Es obligatorio seguir estos pasos cada vez que trabajes en el proyecto.
No hacerlo puede provocar conflictos y pérdida de trabajo de otros compañeros.
Antes de editar cualquier notebook o hacer cambios, sigue siempre estos pasos para evitar conflictos:
