
# Pokemon Go. Pokedex-Kanto

  
## Contexto


El inicio de este trabajo se desarrolla en el contexto del Bootcamp de [Laboratoria](https://www.laboratoria.la/). Desafío Data Lovers.

**Cuándo:** La duración para el desarrollo del proyecto fue de 3 semanas, con fecha de entrega en enero 2019.

**Problema/meta general:** Construir una página web para visualizar un conjunto (set) de datos que se adecúe a lo que descubramos que el usuario necesita. Un pokedex.


![](https://lh4.googleusercontent.com/P39bT9H3odkUtECZ1hC-52LyrzXiQTsgOxbnaOgyz-KbcBw5qn_wJRI7aU4G4iX26g8Y_VFw-ribwu9RdClov2-RFgrC0zvlpLu656FYV8zacfnAyvA3e4ZDJaMYG2WgecRveaC-)

El Pokédex en el mundo ficticio de Pokémon, es una enciclopedia portátil de alta tecnología que los Entrenadores Pokémon llevan consigo para registrar las fichas de todas las diversas especies Pokémon con las que se encuentran durante su viaje como entrenadores (Fuente: [Wikipedia).](https://es.wikipedia.org/wiki/Pok%C3%A9dex)

  
**Equipo:** Este proyecto se basa en el trabajo en equipos conformados por duplas, en nuestro caso, sin conocer el juego Pokemon Go, sin embargo nos decidimos por este proyecto, porque nos pareció poder comprender mejor quién iba a ser el usuario de nuestro futuro producto, lo cual nos pareció lo más relevante en ese momento.

**Herramientas utilizadas:** HTML, CSS, Vanilla Javascript, Boostrap, Figma, Slack, Git, Github, Zeplin.

![enter image description here](https://lh3.googleusercontent.com/mXAIIRpmtb8pAGWJ9dG0m6SVOiu8-VCh1K0bwRAECBLO3lNTN2hsmtFZ1V4dTVFauyD4kCxyTzWq "Herramientas")

**Resultados y entregas:**
-   Un reporte con las conclusiones clave respecto al trabajo con los usuarios y los patrones de interacción.
    
-   Una página web que permita visualizar la data, filtrarla, ordenarla y hacer algún cálculo agregado.
    

**Status:** En proceso.

  

## Etapa 1 - Definición del usuario.


Comenzamos con una búsqueda online para conocer lo que hay disponible para los usuarios respecto a aplicaciones que den información sobre Pokemon Go. Encontramos dos sitios principales [Pokedex.com](https://www.pokemon.com/es/pokedex/) y [Pokedex.org](https://pokedex.org/).

  ![enter image description here](https://lh3.googleusercontent.com/WfBr0Ss9BcPpMyXcgIclBt5ipvTghCQH5Sf4paMWONX_DoJDMXARIN2Kh9MrAOI1Cz0uQR9FU8Bh "PokeWeb")


Ambos proporcionan una idea de nuestro objetivo en cuanto al modo de presentar la información, de realizar búsquedas y filtros de los distitos pokemon.

A partir de esta búsqueda inicial, pasamos acercamos a varias compañeras que son jugadoras de Pokemon Go, para conocer de qué manera nuestra aplicación les podría servir. Conversamos con 3 compañeras, y realizamos preguntas como:

2.- **¿Qué información es relevante conocer para ti?** (peso, altura, debilidad, eggs, etc. respecto a lo disponible en la base de datos proporcionada para el desafío).

3.- **¿Para qué necesitarías esta información?** (cuándo, cómo, por qué)

  

Nos dimos cuenta que en solo esta pequeña muestra de entrevistadas habían algunas diferencias, ya que por ejemplo para algunas era relevante saber …. Mientras que para otras no. Esto lo atribuimos a la experiencia previa en relación con el juego, es decir aquellas con más experiencia y conocimiento del juego, parecen requerir menos información de los pokemon, que sería provista por nuestra aplicación, lo que ayudó a definir mejor a nuestro usuario:

  
***Definición del usuario***

> Un jugador novato de Pokemon Go, y que quiera conocer/ informarse de los pokemones de la región de Kanto para mejorar como entrenador y convertirse en MAESTRO POKEMON,

  
********
## Historias de Usuario

### Definitions of done
Aqui desarrollamos las historias de usuario de nuestro producto.

1.  Enunciado: "Yo como usuario de la aplicación"

Quiero filtrar el listado de Pokemones por elemento, para que sea más fácil y rápido encontrar el pokemon que busco

Criterios de Aceptación:

 - [ ] Quiero que el filtrado se muestre en una lista desplegable 
 - [ ] Quiero que en la búsqueda aparezca el nombre y la foto del pokemon
 - [ ] Quiero que el listado tenga colores relacionados al tipo de elemento del pokemon
 - [ ]  Quiero que la página sea visible en el móvil y en mi computador.

    

  

2. Enunciado: "Yo como usuario de la aplicación"

Quiero ordenar el listado de pokemones: Alfabéticamente (A-Z, y/o Z-A) y por número de ID (Mayor a menor , y/o menor a mayor). Para que sea más fácil y rápido encontrar el pokemon que busco.

Criterios de Aceptación:

 - [ ] Quiero elegir la opción de orden en una lista desplegable
 - [ ] Quiero ordenar de la A a la Z
 - [ ]  Quiero ordenar de la Z a la A  
 - [ ] Quiero ordenar el id número de forma ascendente
 - [ ] Quiero ordenar el id número de forma descendente

    

  

3. Enunciado: "Yo como usuario de la aplicación"
Quiero ver la información detallada del pokemon para estar más informado de sus características.

Criterios de Aceptación:

 - [ ] Quiero que se abra una ventana emergente con información detallada del pokemon
 - [ ] Quiero poder cerrar la ventana al hacer clic fuera de ella
 - [ ] Quiero poder cerrar la ventana al hacer clic en una X

    
4.Enunciado: "Yo como usuario de la aplicación"
Quiero saber la cantidad de Pokemones que existe de cada elemento para saber qué cantidad existe de cada uno.

Criterios de Aceptación:

 - [ ] Quiero poder ver información estadística adicional del Pokemon que seleccione.

  

#### User Flowchart

Luego de tener más claro quién sería nuestro usuario, comenzamos el proceso de pensar en el flujo del usuario al usar la aplicación. Así creamos un prototipo del flujo básico del usuario, el flujo de filtrado, de ordenado (alfabeto o numérico), búsqueda, y estadísticas.

  

Añadir aqui las fotos del flujo de usuario

  
  

## Stage 2 - Prototipado baja definición

El paso siguiente corresponde al prototipado de baja definición, aquí comenzamos ideando e iterando sobre cómo debería verse la aplicación, y qué elementos debería contener para llegar a nuestra meta.

  

### Workflow y Wireframes

  

Añadir aqui las fotos de los prototipos de baja fidelidad

  

En esta etapa del trabajo tuvimos un espacio dentro del Bootcamp para compartir el trabajo entre las parejas de alumnas, así tuvimos la oportunidad de recibir feedback del prototipo inicial, así como de ver los trabajos de otras alumnas, de tal manera de mejorar la calidad de los trabajos e incorporar ideas.

-   Centrarnos en lo más relevante de este desafío (filtrar, ordenar y manipular la data) y no perder tiempo en tareas menos relevantes.
    
-     
    

De este modo, este insumo nos sirvió para modificar nuestro prototipo inicial y convertirlo en el prototipo de alta fidelidad,

  

En esta etapa también decidimos incorporar la herramienta de Boostrap, como plantilla para la página, esto fue un desafío personal, para aprender una nueva herramienta, así como una mejor presentación de la información. Para esto nos decidimos por el template [La Casa](http://pixelhint.com/demo/la_casa/), ya que era la que más cercana estaba al prototipado de baja definición que nos habíamos propuesto en esta etapa. De este modo modificamos la plantilla (HTML y CSS). Sin embargo, avanzando en el proyecto nos dimos cuenta que en realidad este template entorpecía nuestro trabajo más que aligerarlo, ya que habían muchos elementos que no utilizamos, y otros que nos demoraba tiempo en comprender, por lo que a la segunda semana decidimos eliminarlo, y trabajar nuestra propia plantilla.

## Planificación

Paralelo a este proceso trabajamos de manera digital en trello, project de github. Y analógicamente en el tablero proporcionado en Laboratoria.


aqui fotos de los tableros
  
  
  
  
  

## Stage 3 - Prototipado alta definición

Esta es la segunda Iteración, la primera no fue guardada previo al cambio, pero era bastante similar, únicamente modificamos los colores, desde tonos oscuros (de azul marino para el fondo, a blanco y azulino).

Aquí comenzamos a definir más claramente lo que queríamos lograr, esta vez cambiando los colores por unos más claros.

  

Versión computador escritorio.

![aplicación, versión escritorio](https://lh3.googleusercontent.com/NClgGDo6Mqmhaua3efY1pRADbPQ5qZJJ02ASL6TsOMwW5Xi4uMQYNu9Axk9CAZsauhdd2it_Q0t9b1y_c_GEr6nKWy5WDubTkxjv2xaQvSQYNFHOy54x5HMjEKFMN8WQ7ElfpeVa)

Versión celular

![](https://lh3.googleusercontent.com/ZZEcpKtOdRGPOJOBWVD5pVmR6SXf5Vq1KzOsB9ZwTdmsKBuvIic61irG2PPfD6oduVreZg8EIxv5rW5Nt31LRZULUjroDCUEgz2SOtMCAmiv7lYLZX1Df1ANLN4op36PXSG0zPQX)

  ![enter image description here](https://lh3.googleusercontent.com/tyUR1n_qPKQocYbX8JlqsxDQFC2kNciOdHfd-lryo5KnkXW95Q6lowOoGxw9wbSp0il15cNrD5Fv "Pokedex, versión celular")

## Stage 4 - Entrevistas con usuarios y Testeos


1.  Testeo con usuarios
    
1.  problemas
    
2.  necesidades
    
3.  número de testeos
     
Mediante la red de contactos de ambas integrantes del equipo, encontramos a personas que son usuarios y no usuarios de Pokemon Go, que nos ayudaron a testear la aplicación.

Estas entrevistas se basaron en una breve entrevista inicial (experiencia previa con la aplicación), luego un testeo basado en el prototipo de Figma (con una tarea específica), donde se les invitó a los entrevistados que utilizaran el demo de la aplicación, y finalmente, se les hicieron algunas preguntas acerca de su satisfacción, usabilidad y utilidad (cómo fue la experiencia, que le cambiarian, sacarían, mejorarian).

A partir de lo anterior se encontró que:

 - List item
 - ddwd
 - ddad
 - 

### Storyboard  —  Usando la App

Creamos un storyboard para describir la experiencia de un usuario de la aplicación Pokedex. Mediante esta estrategia se puede explorar el producto en un contexto amplio, como si fuera parte de una narrativa mayor. Es una forma económica y efectiva de capturar, relacionar y explorar la aplicación en el mundo real.

  

### Paleta de Colores
Elegimos estos colores porque

![](https://lh3.googleusercontent.com/PGqwjJkvauOfyHzOTiczm65nDvGzVF4O9fHHytEKXrDcQyawJlbUlXK86dryfI4LumXierdq2qcuOsDWcRjrT0IOgIn-DaM6jHiuXPTHPmKTgKgfsSIhLsUWPvwIK8MPp1wAnSIl)

### Tipografía
La tipografía elegida fue... debido a que

### Iconos & Ilustraciones


### Nombre & Logo

  
  
  

## Etapa 5 - El Diseño final


La meta del la aplicación web es crear un proceso rápido de resolución de búsqueda de un pokemon.  La versión final esta disponible para verla.

  


  
La experiencia del usuario esta basada en algunos pasos, donde cada pantalla aparece suficiente información para poder realizar un selección, búsqueda, ordenamiento de la información de los pokemon disponibles.
A partir de los testeos de usuarios, las decisiones respecto a los diseños se basaron en las necesidades detectadas en estos usuarios.  
  

## Conclusiones

Overall this was a very interesting challenge to be involved with, and it was only possible thanks to the collaboration of 3 client stakeholders (including the tailor herself), 4 online clients, 2 guest users, and the final design/development team.



### Aspectos a mejorar:

 

 - List item
 - 

  

*********

  
  

[https://uxdesign.cc/ui-ux-case-study-a-step-by-step-guide-to-the-process-of-designing-a-pet-diet-app-d635b911b648](https://uxdesign.cc/ui-ux-case-study-a-step-by-step-guide-to-the-process-of-designing-a-pet-diet-app-d635b911b648)

  

Highlight your user centered design process: Convey how your design decisions were based on user research, whether that was gathered through user interviews, reviews,