# :wave: Los Fundamentos de GitHub 

## 🤓 Visión general del curso y resultados de aprendizaje 

El objetivo de esta tarea es darte una breve introducción a GitHub. También te proporcionaremos materiales para seguir aprendiendo y algunas ideas para comenzar en nuestra plataforma. 🚀

## :octocat: Git y GitHub

Git es un **Sistema de Control de Versiones Distribuido (DVCS)**, lo que significa que es una herramienta útil para rastrear fácilmente los cambios en tu código, colaborar y compartir. Con Git puedes seguir los cambios que haces en tu proyecto para tener siempre un registro de lo que has trabajado y poder revertir fácilmente a una versión anterior si es necesario. También facilita el trabajo con otros: ¡grupos de personas pueden trabajar juntos en el mismo proyecto y fusionar sus cambios en una fuente final!

GitHub es una manera de usar el mismo poder de Git en línea con una interfaz fácil de usar. Se utiliza en todo el mundo del software y más allá para colaborar y mantener el historial de proyectos.

GitHub alberga algunas de las tecnologías más avanzadas del mundo. Ya sea que estés visualizando datos o desarrollando un nuevo juego, hay toda una comunidad y conjunto de herramientas en GitHub que pueden llevarte al siguiente paso. Este curso comienza con los conceptos básicos de GitHub, pero profundizaremos en el resto más adelante.

## :octocat: Entendiendo el flujo de GitHub 

El flujo de GitHub es un flujo de trabajo ligero que te permite experimentar y colaborar en tus proyectos fácilmente, sin el riesgo de perder tu trabajo anterior.

### Repositorios

Un repositorio es donde ocurre el trabajo de tu proyecto; piensa en él como la carpeta de tu proyecto. Contiene todos los archivos de tu proyecto y el historial de revisiones. Puedes trabajar dentro de un repositorio solo o invitar a otros a colaborar contigo en esos archivos.

### Clonación 

Cuando se crea un repositorio con GitHub, se almacena de forma remota en la ☁️. Puedes clonar un repositorio para crear una copia local en tu computadora y luego usar Git para sincronizar ambos. Esto facilita la corrección de problemas, agregar o eliminar archivos y hacer commits más grandes. También puedes usar la herramienta de edición de tu elección en lugar de la interfaz de usuario de GitHub. ¡Clonar un repositorio también descarga todos los datos del repositorio que GitHub tiene en ese momento, incluidas todas las versiones de cada archivo y carpeta del proyecto! Esto puede ser útil si experimentas con tu proyecto y luego te das cuenta de que te gustaba más una versión anterior.
Para obtener más información sobre la clonación, lee ["Clonar un Repositorio"](https://docs.github.com/es/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Confirmar y enviar (Commit y Push)
**Confirmar** y **enviar** es cómo puedes agregar los cambios que hiciste en tu máquina local al repositorio remoto en GitHub. De esa manera, tu instructor y/o compañeros de equipo pueden ver tu último trabajo cuando estés listo para compartirlo. Puedes hacer un commit cuando hayas realizado cambios en tu proyecto que quieras "guardar como punto de control". También puedes agregar un **mensaje de confirmación** útil para recordarte a ti mismo o a tus compañeros de equipo qué trabajo hiciste (por ejemplo, "Agregué un README con información sobre nuestro proyecto").

Una vez que tengas uno o varios commits que estés listo para agregar a tu repositorio, puedes usar el comando push para agregar esos cambios a tu repositorio remoto. Confirmar y enviar puede parecer nuevo al principio, pero prometemos que te acostumbrarás 🙂

## 💻 Términos de GitHub que debes conocer 

### Repositorios 
Ya mencionamos los repositorios, son donde ocurre el trabajo de tu proyecto, ¡pero hablemos un poco más sobre sus detalles! A medida que trabajes más en GitHub, tendrás muchos repositorios, lo que puede resultar confuso al principio. Afortunadamente, tu ["Panel de GitHub"](https://docs.github.com/es/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) te ayuda a navegar fácilmente a tus repositorios y ver información útil sobre ellos. ¡Asegúrate de haber iniciado sesión para verlo!

Los repositorios también contienen **README**s. Puedes agregar un archivo README a tu repositorio para decirle a otras personas por qué tu proyecto es útil, qué pueden hacer con tu proyecto y cómo pueden usarlo. Estamos usando este README para comunicarte cómo aprender Git y GitHub. 😄 
Para obtener más información sobre los repositorios, lee ["Crear, Clonar y Archivar Repositorios"](https://docs.github.com/es/github/creating-cloning-and-archiving-repositories/about-repositories) y ["Acerca de los README"](https://docs.github.com/es/github/creating-cloning-and-archiving-repositories/about-readmes).

### Ramas (Branches)
Puedes usar ramas en GitHub para aislar el trabajo que no quieres fusionar en tu proyecto final todavía. Las ramas te permiten desarrollar características, corregir errores o experimentar de manera segura con nuevas ideas en un área contenida de tu repositorio. Normalmente, podrías crear una nueva rama desde la rama predeterminada de tu repositorio: main. Esto crea una nueva copia de trabajo de tu repositorio para que experimentes. Una vez que tus nuevos cambios hayan sido revisados por un compañero de equipo, o estés satisfecho con ellos, puedes fusionar tus cambios en la rama predeterminada de tu repositorio.
Para obtener más información sobre las ramas, lee ["Acerca de las Ramas"](https://docs.github.com/es/github/collaborating-with-issues-and-pull-requests/about-branches).

### Bifurcaciones (Forks)
Una bifurcación es otra forma de copiar un repositorio, pero generalmente se usa cuando quieres contribuir al proyecto de otra persona. Bifurcar un repositorio te permite experimentar libremente con cambios sin afectar el proyecto original y es muy popular cuando contribuyes a proyectos de software de código abierto.
Para obtener más información sobre las bifurcaciones, lee ["Bifurcar un repositorio"](https://docs.github.com/es/github/getting-started-with-github/fork-a-repo)

### Solicitudes de extracción (Pull Requests)
Cuando trabajas con ramas, puedes usar una solicitud de extracción para informar a otros sobre los cambios que deseas realizar y pedir su opinión. Una vez que se abre una solicitud de extracción, puedes discutir y revisar los posibles cambios con los colaboradores y agregar más cambios si es necesario. ¡Puedes agregar personas específicas como revisores de tu solicitud de extracción, lo que muestra que quieres su opinión sobre tus cambios! Una vez que una solicitud de extracción está lista para usar, puede fusionarse en tu rama principal.
Para obtener más información sobre las solicitudes de extracción, lee ["Acerca de las Solicitudes de Extracción"](https://docs.github.com/es/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Problemas (Issues)
Los problemas son una forma de rastrear mejoras, tareas o errores para tu trabajo en GitHub. Los problemas son una excelente manera de realizar un seguimiento de todas las tareas en las que deseas trabajar para tu proyecto e informar a otros sobre lo que planeas hacer. También puedes usar problemas para informar a un proyecto de código abierto favorito sobre un error que encontraste o una característica que crees que sería genial agregar.

Para proyectos más grandes, puedes realizar un seguimiento de muchos problemas en un tablero de proyecto. Los Proyectos de GitHub te ayudan a organizar y priorizar tu trabajo, y puedes leer más sobre ellos [en este documento "Acerca de los tableros de proyectos"](https://docs.github.com/es/github/managing-your-work-on-github/about-project-boards). ¡Probablemente no necesitarás un tablero de proyecto para tus tareas, pero una vez que pases a proyectos aún más grandes, son una excelente manera de organizar el trabajo de tu equipo!
También puedes vincular solicitudes de extracción y problemas para mostrar que se está trabajando en una solución y cerrar automáticamente el problema cuando alguien fusiona la solicitud de extracción.
Para obtener más información sobre los problemas y vincularlos a tus solicitudes de extracción, lee ["Acerca de los Problemas"](https://docs.github.com/es/github/managing-your-work-on-github/about-issues).

### Tu perfil de usuario

Tu página de perfil cuenta a las personas la historia de tu trabajo a través de los repositorios que te interesan, las contribuciones que has hecho y las conversaciones que has tenido. También puedes darle al mundo una visión única de quién eres con tu README de perfil. ¡Puedes usar tu perfil para que los futuros empleadores sepan todo sobre ti!
Para obtener más información sobre tu perfil de usuario y cómo agregar y actualizar tu README de perfil, lee ["Administrar tu README de Perfil"](https://docs.github.com/es/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).

### Uso de markdown en GitHub 

Es posible que ya lo hayas notado, pero puedes agregar algunos estilos divertidos a tus problemas, solicitudes de extracción y archivos. ["Markdown"](https://guides.github.com/features/mastering-markdown/) es una forma fácil de dar estilo a tus problemas, solicitudes de extracción y archivos con una sintaxis simple. Esto puede ser útil para organizar tu información y facilitar la lectura para otros. ¡También puedes incluir gifs e imágenes para ayudar a transmitir tu punto!
Para obtener más información sobre el uso de la versión de markdown de GitHub, lee ["Sintaxis básica de escritura y formato"](https://docs.github.com/es/github/writing-on-github/basic-writing-and-formatting-syntax).

### Interactuando con la comunidad de GitHub

La comunidad de GitHub es vasta. Hay muchos tipos de personas que usan GitHub en su día a día: estudiantes como tú, desarrolladores profesionales, aficionados que trabajan en proyectos de código abierto y exploradores que recién se sumergen en el mundo del desarrollo de software por su cuenta. Hay muchas formas en las que puedes interactuar con la comunidad más amplia de GitHub, pero aquí hay tres lugares por donde puedes comenzar.

#### Marcar repositorios con estrella 

Si encuentras un repositorio interesante o quieres realizar un seguimiento, ¡márcalo con una estrella! Cuando marcas un repositorio con estrella, también se utiliza como una señal para mostrar mejores recomendaciones en github.com/explore. Si deseas volver a los repositorios que has marcado con estrella, puedes hacerlo a través de tu perfil de usuario.
Para obtener más información sobre cómo marcar repositorios con estrella, lee ["Guardar Repositorios con Estrellas"](https://docs.github.com/es/github/getting-started-with-github/saving-repositories-with-stars).

#### Seguir usuarios 

Puedes seguir a personas en GitHub para recibir notificaciones sobre su actividad y descubrir proyectos en sus comunidades. Cuando sigues a un usuario, su actividad pública de GitHub aparecerá en tu panel de control para que puedas ver todas las cosas interesantes en las que están trabajando.
Para obtener más información sobre cómo seguir usuarios, lee ["Seguir a Personas"](https://docs.github.com/es/github/getting-started-with-github/following-people).

#### Explorar GitHub Explore 

GitHub Explore es un gran lugar para hacer precisamente eso... explorar :smile: Puedes encontrar nuevos proyectos, eventos y desarrolladores con los que interactuar.

Puedes consultar el sitio web de GitHub Explore [en github.com/explore](https://github.com/explore). Cuanto más interactúes con GitHub, más personalizada será tu vista de Explore.

## 📝 Próximos pasos opcionales 

* Abre un pull request para avisar que terminaste esta tarea.
* Crea un nuevo archivo markdown en este repositorio. ¡Hazles saber lo que aprendiste y sobre qué aún estás confundido! ¡Experimenta con diferentes estilos!
* Crea tu README de perfil. ¡Deja que el mundo sepa un poco más sobre ti! ¿Qué te interesa aprender? ¿En qué estás trabajando? ¿Cuál es tu pasatiempo favorito? Obtén más información sobre cómo crear tu README de perfil en el documento, ["Administrar tu README de Perfil"](https://docs.github.com/es/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Ve a tu panel de usuario y crea un nuevo repositorio. Experimenta con las funciones dentro de ese repositorio para familiarizarte con ellas.
* [Haznos saber qué te gustó o qué no te gustó del contenido de este curso](https://support.github.com/contact/education). ¿Qué te gustaría ver más? ¿Qué sería interesante o útil para tu viaje de aprendizaje?

## 📚 Recursos 
* [Un video breve que explica qué es GitHub](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Recursos de aprendizaje de Git y GitHub](https://docs.github.com/es/github/getting-started-with-github/git-and-github-learning-resources) 
* [Entendiendo el flujo de GitHub](https://guides.github.com/introduction/flow/)
* [Cómo usar las ramas de GitHub](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Materiales interactivos de capacitación de Git](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [Laboratorio de Aprendizaje de GitHub](https://lab.github.com/)
* [Foro de la comunidad educativa](https://education.github.community/)
* [Foro de la comunidad de GitHub](https://github.community/)
