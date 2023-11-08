<h2>¿Que es git?</h2>

Git es un sistema de control de versiones distribuido ampliamente utilizado en el desarrollo de software. Fue creado por Linus Torvalds en 2005 y se ha convertido en una herramienta fundamental para gestionar el seguimiento de cambios en proyectos de programación, permitiendo a los equipos de desarrollo colaborar de manera eficiente y controlar el historial de revisiones de su código.

En esencia, Git se encarga de registrar y rastrear las modificaciones realizadas en los archivos de un proyecto a lo largo del tiempo, lo que facilita la gestión y colaboración en el desarrollo de software.

<h2>¿Que metodología vamos a usar?</h2>

Vamos a usar la metodología gitFlow con 4 ramas. La rama main, la rama release, la rama develop y gh-pages para publicar la documentación.





<h3>Pasos que se han seguido</h3>

El usuario 1 ha creado el respositorio con la estructura inicial y ha creado las cuatro ramas para la organización.

![alt text](https://i.imgur.com/2lCqyPs.png)
![alt text](https://i.imgur.com/xPTpL1C.png)


El usuario 2 ha creado ambos features y los ha añadido a la rama develop tras la supervisión (Pull recuest)

![alt text](https://i.imgur.com/NTvltCI.png)

El usuario 3 ha creado la feature para modificar el CSS y lo ha añadido a la rama develop tras la supervisión (Pull recuest)

![alt text](https://i.imgur.com/cxD0kWz.png)

El usuario 1 marca el lanzamiento como "v1.0" y crea una nueva rama llamada test para el testeo del mismo.

![alt text](https://i.imgur.com/cXnlhAu.png)
![alt text](https://i.imgur.com/XNmgSEX.png)

El usuario 1 ha creado los hooks post-checkout y pre-commit y los ha añadido a la carpeta en la rama main. Tras instalar el plugin, se añade al gitignore la carpeta "node_modules/"

![alt text](https://i.imgur.com/XNmgSEX.png)
