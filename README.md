# Reflexiones individuales

## Estrategia de ramificacion
Usamos workflows con ramas llamadas: 
- main
- develop
- feature/express-config
- hotfix/fix-response
- feature/add-ci-yml-workflow
- feature/add-readme

## Convenciones de commits:
- feat: nueva funcionalidad
- fix: correcion de bug
- docs: cambios en la documentacion

### Bastian Millanir

**¿Que hice en este proyecto?**

Cree la rama feature/express-config en donde inicialicé y generé un microservicio 
levantado con Express.js el cual expone un endpoint con método GET devolviendo un
mensaje. Dejé este backend corriendo en el puerto 3000. 

También configuré el workflow de Github Actions el cual se activa cada vez que se 
hace un push a la rama develop o cuando se crea un pull request hacia la rama base main.

Además, me ayudé de Copilot (el reviewer de pull requests, NO el asistente de código) 
para la revisión de los Pull Requests, ya que contamos con 
el Student Developer Pack de Github gracias a DuocUC. Me fue de gran ayuda, sobre todo
para detectar incongruencias con el archivo de CI.yml con sus comentarios en el 
Pull Request. Es una herramienta que uso a diario en mi trabajo.

Y por último, mi tarea final fue complementar este README.md con lo que hice en esta
primera evaluación y mis reflexiones del trabajo colaborativo con Sofia.



**¿Que aprendi sobre CI/CD O Gitflow que no sabia antes?**

Aprendí a configurar un workflow de Github Actions para la instalación de dependencias
y ejecución de tests unitarios en un proyecto Node.js. Esto no lo había hecho antes, solo
había configurado un Github Actions para revisión de sintaxis de código y para ejecutar
Linting, pero nunca para instalar dependencias y ejecutar tests unitarios. Me apoyé harto
de las clases, tuve que ver las grabaciones para poder entender bien el flujo de trabajo y 
la configuración del workflow. En nuestro caso, dejamos opcional la ejecución de tests unitarios, 
ya que no teníamos tests unitarios en nuestro proyecto, pero si los tuviéramos
, el workflow los ejecutaría y nos avisaría si alguno falla.

En general se me hizo bien sencillo esta primera evaluación, ya que trabajo a diario con 
Node.js y Express.js, por lo que me fue fácil entender la configuración del workflow y la creación del microservicio.

### Sofia Huichulef

**¿Que hice en este proyecto?**
cree una rama hotfix para simular un brug critico,hice el commit,abri el PR y espere la aprobacion de mi compañero antes de mergear a main.

**¿Que aprendi ?**

**¿Que dificultad tuve y como la resolvi?**


## Estrategia de revision
-Todo PR requiere al menos 1 revision antes de mergear. En este caso, cada uno revisó el PR del otro.
-Se revisa: sintaxis, coherencia, congruencia con el workflow de CI/CD y que cumpla con la funcionalidad 
que se pide (con en nombre de la rama).

