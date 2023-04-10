¡Hola a todos! En este README os voy a contar cómo he clonado un porfolio profesional, a traves de unas imagenes en PDF, usando HTML5 y CSS3, siguiendo las indicaciones de un ejercicio de un curso introductorio de ID Bootcamp. Se trata de replicar una propuesta de diseño que nos han facilitado, con información genérica (no personal mía). El resultado lo podéis ver en este enlace: https://idb-ejerciciofinal.vercel.app/

<h2>Para realizar este proyecto he usado las siguientes tecnologías:</h2>

- HTML5: el lenguaje de marcado que define la estructura y el contenido de la página web. He usado etiquetas semánticas como `<header>`, `<nav>`, `<section>`, `<article>` y `<footer>` para darle más sentido y accesibilidad al documento.

- CSS3: el lenguaje de estilos que define la apariencia y el diseño de la página web. He usado propiedades como `flexbox` y `grid` para crear un diseño responsive que se adapte a diferentes tamaños de pantalla. También he usado algunas características nuevas de CSS3 como `variables` y `transforms`.

- Metodología BEM: una convención de nomenclatura para las clases de CSS que facilita la organización y el mantenimiento del código. BEM significa Block, Element, Modifier, y consiste en asignar nombres a las clases siguiendo este formato: `block__element--modifier`. Por ejemplo, en este fragmento de código se puede ver cómo he usado BEM para definir el bloque `header`, el elemento `logo` y el modificador `small`:

<!-- html <header class="header"> <div class="header__logo header__logo--small"> <img src="images/logo.png" alt="Logo"> </div> <nav class="header__nav"> <ul class="header__menu"> <li class="header__item"><a href="#about" class="header__link">Sobre mí</a></li> <li class="header__item"><a href="#skills" class="header__link">Habilidades</a></li> <li class="header__item"><a href="#projects" class="header__link">Proyectos</a></li> <li class="header__item"><a href="#contact" class="header__link">Contacto</a></li> </ul> </nav> </header> ``` -->

 La ventaja de usar BEM es que evita la colisión de nombres, mejora la reutilización de componentes y facilita la lectura y comprensión del código. Si queréis ver todo el código fuente del proyecto, podéis acceder al repositorio de GitHub que he creado para este ejercicio: 
 
 https://github.com/carlosdamota/idb_ejerciciofinal.git
 
 Allí podréis ver los diferentes commits que he realizado a lo largo del desarrollo, explicando los cambios y mejoras que he ido introduciendo. Para que os hagáis una idea del aspecto final del porfolio, os dejo unas capturas de pantalla tanto del diseño en móvil como en desktop:
  ![Captura móvil](images/chrome-capture-2023-3-10.png) 
  ![Captura desktop](images/chrome-capture-2023-3-10%20mobil.png)
  
  <h2>Agradeciminetos</h2>

  Espero que os haya gustado este post y que os sirva de inspiración para crear vuestros propios porfolios profesionales. Quiero agradecer a ID Bootcamp la posibilidad de poder realizar este precurso y a Openbootcamp por todo lo que es capaz de ofrecer. Ha sido una experiencia muy enriquecedora y divertida. ¡Hasta pronto! ```