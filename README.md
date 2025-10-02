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

<img width="324" height="170" alt="imagen" src="https://github.com/user-attachments/assets/7453d6a7-e2fc-43bb-b1d1-1fcd60e449fb" />

<img width="750" height="490" alt="imagen" src="https://github.com/user-attachments/assets/c83ea14c-343f-4ade-bd63-e3ba8c05ce6a" />


4. user2 clonará su fork del repo.

<img width="557" height="42" alt="imagen" src="https://github.com/user-attachments/assets/63e808e4-0abd-4670-b685-c6b682af71f3" />

Con git clone el user2 clona su fork en la maquina local



5. user1 creará una issue con el título "Add custom text for startup contents".

<img width="362" height="69" alt="imagen" src="https://github.com/user-attachments/assets/0c3ae4c6-7127-41af-afeb-1a1a8a3c6591" />


6. user2 creará una nueva rama custom-text y modificará el fichero index.html personalizándolo para una supuesta startup.

<img width="309" height="73" alt="imagen" src="https://github.com/user-attachments/assets/9803fbaa-bb05-4bcf-90f5-5d31329d6204" />


7. user2 enviará un PR a user1.

<img width="436" height="79" alt="imagen" src="https://github.com/user-attachments/assets/3c29acd2-b141-4bca-ac23-f1b0c6332d72" />


8. user1 probará el PR de user2 en su máquina (copia local) creando previamente un remoto denominado upstream, y realizará ciertos cambios en su copia local que luego deberá subir al propio PR.

user1 clona el fork de user2

<img width="754" height="40" alt="imagen" src="https://github.com/user-attachments/assets/8b1626af-63ed-43cf-8116-1d505bb6f5e5" />


crea upstream, y cambia a la rama del pull request

<img width="787" height="31" alt="imagen" src="https://github.com/user-attachments/assets/27948229-77e8-481e-be68-36299d2f5016" />

Modifica el codigo, hace el commit y lo pushea al repositorio remoto

<img width="468" height="35" alt="imagen" src="https://github.com/user-attachments/assets/2dd5f319-4702-42d9-b102-569b60c8dfc9" />


9. user1 y user2 tendrán una pequeña conversación en la página del PR, donde cada usuario incluirá, al menos, un cambio más.

<img width="537" height="761" alt="imagen" src="https://github.com/user-attachments/assets/75be2ed4-7486-40ad-8474-f91783f22311" />


10. user1 finalmente aprobará el PR, cerrará la issue creada (usando una referencia a la misma) y actualizará la rama principal en su copia local.

<img width="703" height="348" alt="imagen" src="https://github.com/user-attachments/assets/14f9b0fe-a96b-433c-ad4c-e30123040e2a" />

user1 cambia la rama a main, y actualiza el repositorio local con los cambios hechos en el remoto con el pull

<img width="544" height="42" alt="imagen" src="https://github.com/user-attachments/assets/640bbdc2-23b8-4199-a48c-89b1571eb01d" />


11. user2 deberá incorporar los cambios de la rama principal de upstream en su propia rama principal.

user1 añade el remoto y upstream su repositorio

<img width="717" height="42" alt="imagen" src="https://github.com/user-attachments/assets/8c02918e-a948-41a7-adc4-bae21dddebf1" />

Integra los cambios

<img width="670" height="27" alt="imagen" src="https://github.com/user-attachments/assets/e39d1e99-590f-46ce-82cd-ead86f7bc1fc" />


12. user1 creará una issue con el título "Improve UX with cool colors".

<img width="297" height="280" alt="imagen" src="https://github.com/user-attachments/assets/c7a791ad-0666-41c8-9e43-2bd9455a047c" />


13. user1 cambiará la línea 10 de cover.css a: color: purple;

<img width="299" height="310" alt="imagen" src="https://github.com/user-attachments/assets/125b0bfb-f631-4359-861a-65f08fbf3730" />


14. user1 hará simplemente un commit local en main

<img width="360" height="30" alt="imagen" src="https://github.com/user-attachments/assets/d0c80137-c38f-4744-8cff-d28ec340baa5" />

<img width="563" height="45" alt="imagen" src="https://github.com/user-attachments/assets/e7ab3add-5b6f-4f70-8e33-52802ca370bc" />


15. user2 creará una nueva rama cool-colors y cambiará la línea 10 de cover.css a: color: darkgreen;

user2 crea la rama

<img width="357" height="26" alt="imagen" src="https://github.com/user-attachments/assets/86ebd63d-0698-4c2a-acca-08f6a231ba56" />

cambia cover.css a darkgreen

<img width="258" height="282" alt="imagen" src="https://github.com/user-attachments/assets/de1506b4-0f76-40ed-9c74-0f279fdcb231" />


16. user2 enviará un PR a user1.

user2 hace el commit 

<img width="675" height="33" alt="imagen" src="https://github.com/user-attachments/assets/c396fd7a-8a9c-43b3-a1cb-25ff4de884bf" />

y lo pushea al remoto y crea la pull request

<img width="388" height="26" alt="imagen" src="https://github.com/user-attachments/assets/dacbbf95-d288-4897-9f01-9a5f164a38f5" />

<img width="738" height="97" alt="imagen" src="https://github.com/user-attachments/assets/6ec15310-98b5-441b-8dee-93201a076728" />


17. user1 probará el PR de user2 (en su copia local). A continuación tratará de mergear el contenido de la rama cool-colors en su rama principal y tendrá que gestionar el conflicto: Dejar el contenido que viene de user2.

<img width="772" height="23" alt="imagen" src="https://github.com/user-attachments/assets/dc8ebe57-3b19-471d-941a-a53f974e4111" />

<img width="561" height="32" alt="imagen" src="https://github.com/user-attachments/assets/b8a5e79e-0bb7-42f3-bca8-8d1dfd395b70" />

aparece un conflicto por el color modificado en cover.css, lo modifica para ser igual al del user2


18. Después del commit para arreglar el conflicto, user1 modificará la línea 11 de cover.css a: text-shadow: 2px 2px 8px lightgreen;

<img width="683" height="25" alt="imagen" src="https://github.com/user-attachments/assets/abc6c290-69d1-401d-9577-9c5b422ed262" />

19. user1 hará un commit especificando en el mensaje de commit el cambio hecho (sombra) y que se cierra la issue creada (usar referencia a la issue). A continuación subirá los cambios a origin/main.

commit

<img width="802" height="51" alt="imagen" src="https://github.com/user-attachments/assets/c70eba7c-f4fe-47a3-8394-cc22438c0234" />

subir cambios a origin/main

<img width="411" height="48" alt="imagen" src="https://github.com/user-attachments/assets/be5b3cef-82ce-4dd1-be6c-f1a9af8287af" />


20. user1 etiquetará esta versión (en su copia local) como 0.1.0 y después de subir los cambios creará una "release" en GitHub apuntando a esta etiqueta.

etiqueta version como 0.1.0

<img width="587" height="34" alt="imagen" src="https://github.com/user-attachments/assets/222e20f5-25cc-4c0d-98ad-955d72c61be9" />

sube cambios

<img width="424" height="50" alt="imagen" src="https://github.com/user-attachments/assets/09631170-2443-4b08-9d1c-7d72a1df75ec" />

publica release 

<img width="969" height="345" alt="imagen" src="https://github.com/user-attachments/assets/e0159f6e-d113-4437-9c29-b2529c6de276" />


En esta parte explicamos detalladamente los pasos que seguimos para realizar la práctica incluyendo capturas de pantalla y explicando que vemos en ellas. 

> ***IMPORTANTE:*** si estamos capturando una terminal no hace falta capturar todo el escritorio y es importante que se vea el nombre de usuario.

Si encontramos dificultades a la hora de realizar algún paso debemos explicar esas dificultades, que pasos hemos seguido para resolverla y los resultados obtenidos.

#### ***Conclusiones***. <a name="id5"></a>

Al comenzar la práctica se disponian de conceptos y fluidez de git decentes, pero a medida que avanzaban los puntos a realizar, se necesitaron algunas búsquedas, puestas en común e incluso algunas charlas para solventar dudas y/o desconocimientos del tema.

Nos ha brindado nuestra primera experiencia en esta asignatura, y es sobre el sistema de control de versiones, el cual es tan importante en nuestro sector.

Realizar esta práctica al inicio del semestre ha sido especialmente útil, ya que nos permite asentar conocimientos que emplearemos de manera recurrente en la mayoría de trabajos y asignaturas. Además, nos ayuda a interiorizar buenas prácticas desde el principio, lo que sin duda marcará una diferencia en la calidad de nuestro trabajo futuro.
