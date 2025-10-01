# GIT-WORK

<center>

# UT1-A1 Documentación y sistema de control de versiones


</center>

***Nombre: Moisés (user1) Y Leonardo (user2)***
***Curso:*** 2º de Ciclo Superior de Desarrollo de Aplicaciones Web.

### ÍNDICE

+ [Introducción](#id1)
+ [Objetivos](#id2)
+ [Material empleado](#id3)
+ [Desarrollo](#id4)
+ [Conclusiones](#id5)


#### ***Introducción***. <a name="id1"></a>

En esta práctica, aprenderemos y afianzaremos distintos mecanismos de Git mediante la simulación de un trabajo entre dos personas. El objetivo principal es familiarizarnos con el uso del sistema de control de versiones como herramienta central para la gestión del código, dejando de lado otros medios de intercambio de archivos y centrándonos exclusivamente en las funcionalidades que Git y GitHub.

La actividad nos permitirá recorrer un flujo de trabajo completo: creación de un repositorio inicial y su configuración, pasando por el uso de ramas, forks, issues entreo otros hasta la apertura y gestión de pull requests con la resolución de conflictos. Además, se busca experimentar de manera práctica cómo se organiza la comunicación entre colaboradores dentro de un mismo proyecto, algo fundamental.

#### ***Objetivos***. <a name="id2"></a>

En esta actividad se deberá hacer uso del sistema de control de versiones, de esta forma, se acondicionarán diferentes conocmientos y se simularán diferentes situaciones que podrían ocurrir en el mundo laboral, como:

- Creación de repositorio
- Utiización de fork
- Pull Requests
- Trabajar con una comunicación altamente reducida
- Etiquetar a través de versiones el respositorio de GitHub

Entre otros.

#### ***Material empleado***. <a name="id3"></a>

Hardware

- Ordenadores del alumnado

Software

- Git
- Navegador Web
- Editor de texto/código
- Configuraciones realizadas
- Red

#### ***Desarrollo***. <a name="id4"></a>

1. user1 creará un repositorio público llamado git-work en su cuenta de GitHub, añadiendo un README.md y una licencia MIT.

En este caso, Moisés ha creado el repositorio en GitHub con los requisitos solicitados como se aprecia en la imagen.

<img width="914" height="412" alt="image" src="https://github.com/user-attachments/assets/0c83731f-7f76-4990-9e25-0b57e489fc5d" />


2. user1 clonará el repo y añadirá los ficheros: index.html, bootstrap.min.css y cover.css. Luego subirá los cambios al upstream.

En la imagen que se muestra a continuación solo se muestra la creación del cover.css, no obstante, es simplemente hacerlo con los tres archivos a crear.

<img width="335" height="33" alt="imagen" src="https://github.com/user-attachments/assets/4110edcf-d646-4e1d-b676-540e4fb760ce" />

git clone https://github.com/user1/git-work.git 
cd git-work 

touch index.html bootstrap.min.css cover.css (En nuestro caso, el user1 directamente creó cada archivo y después añadió el contenido en cada uno de ellos)
git add index.html bootstrap.min.css cover.css
git commit -m "Add initial project files"
git push origin main

<img width="252" height="70" alt="imagen" src="https://github.com/user-attachments/assets/32d977c1-c706-40b8-9da7-47c41899a764" />

3. user2 creará un fork de git-work desde su cuenta de GitHub.



4. user2 clonará su fork del repo.


5. user1 creará una issue con el título "Add custom text for startup contents".

<img width="362" height="69" alt="imagen" src="https://github.com/user-attachments/assets/0c3ae4c6-7127-41af-afeb-1a1a8a3c6591" />

6. user2 creará una nueva rama custom-text y modificará el fichero index.html personalizándolo para una supuesta startup.

<img width="309" height="73" alt="imagen" src="https://github.com/user-attachments/assets/9803fbaa-bb05-4bcf-90f5-5d31329d6204" />

7. user2 enviará un PR a user1.

<img width="436" height="79" alt="imagen" src="https://github.com/user-attachments/assets/3c29acd2-b141-4bca-ac23-f1b0c6332d72" />



En esta parte explicamos detalladamente los pasos que seguimos para realizar la práctica incluyendo capturas de pantalla y explicando que vemos en ellas. 

> ***IMPORTANTE:*** si estamos capturando una terminal no hace falta capturar todo el escritorio y es importante que se vea el nombre de usuario.

Si encontramos dificultades a la hora de realizar algún paso debemos explicar esas dificultades, que pasos hemos seguido para resolverla y los resultados obtenidos.

#### ***Conclusiones***. <a name="id5"></a>

Al comenzar la práctica se disponian de conceptos y fluidez de git decentes, pero a medida que avanzaban los puntos a realizar, se necesitaron algunas búsquedas, puestas en común e incluso algunas charlas para solventar dudas y/o desconocimientos del tema.

Nos ha brindado nuestra primera experiencia en esta asignatura, y es sobre el sistema de control de versiones, el cual es tan importante en nuestro sector.

Realizar esta práctica al inicio del semestre ha sido especialmente útil, ya que nos permite asentar conocimientos que emplearemos de manera recurrente en la mayoría de trabajos y asignaturas. Además, nos ayuda a interiorizar buenas prácticas desde el principio, lo que sin duda marcará una diferencia en la calidad de nuestro trabajo futuro.
