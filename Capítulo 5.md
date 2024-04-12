## CAPÍTULO 5: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT

### 5.1. Software Configuration Management

Se detallarán las herramientas necesarias para gestionar y controlar los cambios en el código e infraestructura del proyecto. 

5.1.1. Software Development Enviroment Configuration

En esta sección se definirá las herramientas y productos de software que se utilizará por cada uno de los integrantes para colaborar en la elaboración de esta plataforma. Se tomará en cuenta cada una de las fases del software , desde el nacimiento de la idea y documentación del proyecto hasta el despliegue de la plataforma.

| Herramienta | Propósito | Ruta de Descarga/Referencia |
|-------------|-----------|----------------------------|
| Git         | Control de versiones y colaboración en el código fuente del proyecto | [Git](https://git-scm.com/) |
| Jira Software | Gestión de tareas, seguimiento de problemas y planificación de tareas. Se podrá llevar a cabo una mejor gestión para cumplir con la metolodía SCRUM | [Jira Software](https://www.atlassian.com/software/jira) |
| Figma | Diseño de todas las interfaces de la aplicación y elaboración de un prototipo interactivo | [Figma](https://www.figma.com/) |
| Visual Studio Code | Codificación y desarrollo de software | [Visual Studio Code](https://code.visualstudio.com/) |
| Intellij IDEA | Codificación y desarrollo de software | [Intellij IDEA](https://www.jetbrains.com/idea/) |
| AWS (Amazon Web Services) | Despliegue y alojamiento de la aplicación | [AWS](https://aws.amazon.com/) |
| Markdown | Documentación técnica y de usuario | [Markdown Guide](https://www.markdownguide.org/getting-started/) |

5.1.2. Source Code Management

Nuestro proyecto seguirá los lineamientos del modelo GitFlow para controlar las versiones, donde utilizaremos GitHub como plataforma y sistema para el control de dichas versiones. Links del repositorio de GitHub:

- Link de la organización: https://github.com/NaggitBallona/Los-Reales-de-Open-Source
- Link de la landing page: 
- Link del informe: https://github.com/NaggitBallona/Los-Reales-de-Open-Source/blob/main/README.md
- Link del Front-end:
- Link del Back-end:

Estructura de las ramas:

- Main Branch: Rama principal de la aplicación. Se encuentran las versiones más actualizadas y estables de desarrollo, por medio de un proceso de admisión se agregan cambios de otras ramas derivadas.

- Develop Branch: Esta rama es donde se reunen de las demás ramas los avances del proyecto y desarollo. Se evalúan todos los cambios para ser registradas posteriormente en nuestra rama main.Estructura de las ramas:

- Main Branch: Rama principal de la aplicación. Se encuentran las versiones más actualizadas y estables de desarrollo, por medio de un proceso de admisión se agregan cambios de otras ramas derivadas.

- Develop Branch: Esta rama es donde se reunen de las demás ramas los avances del proyecto y desarollo. Se evalúan todos los cambios para ser registradas posteriormente en nuestra rama main.

5.1.3. Source Code Style Guide & Conventions

HTML: Varias de las mejores prácticas que hemos seguido para alcanzar un código limpio, ordenado, legible y escalable son mostradas a continuación:

- Se usan elementos HTML que tengan un significado claro y  preciso para el contenido que se está marcando. Por ejemplo, utiliza header, nav, main, article, section, aside, footer, entre otros, al estructurar la landing page, sin redundancia, por algún uso incorrecto o querer reinventar la rueda.
- HTML5 permite algunas etiquetas sin cierre (como "img" y "input"), sin embargo utilizamos la buena práctica de cerrar todas las etiquetas correctamente para evitar problemas de renderizado.
- Para mejorar la accesibilidad a nuestras clases, siempre incluimos el atributo alt en las etiquetas, "img" por ejemplo, para describir brevemente el contenido de la imagen.
- En HTML, es posible utilizar tanto mayúsculas como minúsculas en los nombres de elementos y atributos, pero nosotros utilizamos solo minúsculas para mantener el orden y facilitar la legibilidad del código.
- No omitir etiquetas principales e importantes como ```<html>```, ```<body>```,  ```<header>``` y más.
- Escribir en una línea los comentarios cortos.

CSS: Entre nuestras prácticas están:

- Los nombres de clases son claros, precisos y autodescriptivos.
- Separar los nombres de las clases y ID con guión, por ejemplo: ```#userWorker-id``` o ```button-shape{}```.
- Usar comentarios claros para explicar el código.
- Aplicar sangría al contenido de un bloque entero.
- Separar las declaraciones y selectores en nuevas líneas para tener una buena legibilidad y orden.

JavaScript: Principales buenas prácticas:

- Uso de prácticas de nomenclatura, en este caso camelCase para nombrar únicas variables y funciones. Por ejemplo, ```miVariable``` o ```miFuncion```.
- Uso de PascalCase para nombrar clases y constructores.Por ejemplo, ```MiClase```.
- Evitamos el uso de nombres de variables genéricos o ambiguos.
- Uso general de comentarios para explicar el propósito y funcionalidad de la porción del código.
- Uso de punto y coma al final de cada declaración.
- Uso de comillas simples ('') o comillas dobles ("") de forma consistente para las cadenas de texto.
- Uso de operadores ternarios, por ejemplo, ```(condición ? resultadoTrue : resultadoFalse)``` de manera cuidadosa según la legibilidad y dificultad del bloque de código.
- Evitación y eliminación del uso de funciones obsoletas o en desuso.
- Uso de ```try-catch``` para manejar y gestionar errores.
- Organización del código en bloques lógicos separados por líneas en blanco para mejorar la legibilidad.

Gherking : Lenguaje de dominio especializado utilizado en el Behavior Driven Development (BDD), diseñado para mejorar la comunicación entre equipos de negocios y técnicos al abordar problemas específicos. Emplea saltos de línea y palabras clave como "Given", "When", "Then" y "And" para mejorar la legibilidad y la organización de los escenarios en BDD, facilitando la estructuración clara y efectiva de diferentes tipos de casos. Estas prácticas nos ayudan a estructurar de manera clara y efectiva los diferentes tipos de escenarios en BDD.

### 5.2. Landing Page, Services & Applications Implementation

5.2.1.3. Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|------------|--------|-----------|----------------|---------------------|--------------------|
| | | | | | |

5.2.1.4. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|------------|--------|-----------|----------------|---------------------|--------------------|
| | | | | | |

5.2.1.5. Execution Evidence for Sprint Review
