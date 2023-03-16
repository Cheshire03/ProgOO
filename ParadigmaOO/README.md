# Tarea 1

1. [Paradigma](https://github.com/Cheshire03/ProgOO/edit/main/ParadigmaOO/README.md#paradigma)

  1.1. [Definción de Paradigma](https://github.com/Cheshire03/ProgOO/edit/main/ParadigmaOO/README.md#definici%C3%B3n-de-paradigma-en-el-contexto-de-lenguajes-de-programaci%C3%B3n)

  1.2. [Programación orientada a objetos](https://github.com/Cheshire03/ProgOO/edit/main/ParadigmaOO/README.md#definici%C3%B3n-de-programaci%C3%B3n-orientada-a-objetos-cu%C3%A1l-fue-el-primer-lenguaje-orientado-a-objetos-quienes-y-en-d%C3%B3nde-lo-propusieron)
  
  1.3. [Abstracción](https://github.com/Cheshire03/ProgOO/edit/main/ParadigmaOO/README.md#define-con-tus-palabras-el-concepto-de-abstracci%C3%B3n-por-qu%C3%A9-se-considera-fundamental-en-programaci%C3%B3n)
  
  1.4. [Encapsulamiento](https://github.com/Cheshire03/ProgOO/edit/main/ParadigmaOO/README.md#explica-el-concepto-de-encapsulamiento-busca-dos-im%C3%A1genes-que-te-ayuden-a-describir-el-concepto-una-que-tenga-alg%C3%BAn-sistema-sin-encapsulamiento-y-otra-donde-s%C3%AD-lo-tenga-menciona-porque-es-importante-y-qu%C3%A9-problemas-puede-evitar)
  
  1.5. [Herencia](https://github.com/Cheshire03/ProgOO/edit/main/ParadigmaOO/README.md#describe-con-tus-palabras-el-concepto-de-herencia-e-ilustra-el-concepto-con-im%C3%A1genes)
  
  2. [UML]


# Paradigma
### Definición de Paradigma en el contexto de lenguajes de programación.

Un paradigma de programación es una manera o estilo de programación de software. Existen diferentes formas de diseñar un lenguaje de programación y varios modos de trabajar para obtener los resultados que necesitan los programadores.  Se trata de un conjunto de métodos sistemáticos aplicables en todos los niveles del diseño de programas para resolver problemas computacionales.

Los lenguajes de programación adoptan uno o varios paradigmas en función del tipo de órdenes que permiten implementar como, por ejemplo, Python o JavaScript, que son multiparadigmas.

### Definición de Programación Orientada a Objetos, ¿Cuál fue el primer lenguaje orientado a objetos, quienes y en dónde lo propusieron? 

La Programación Orientada a Objetos (POO) es un paradigma de programación, es decir, un modelo o un estilo de programación que nos da unas guías sobre cómo trabajar con él. Se basa en el concepto de clases y objetos. Este tipo de programación se utiliza para estructurar un programa de software en piezas simples y reutilizables de planos de código (clases) para crear instancias individuales de objetos. 

Con el paradigma de Programación Orientado a Objetos lo que buscamos es dejar de centrarnos en la lógica pura de los programas, para empezar a pensar en objetos, lo que constituye la base de este paradigma. Esto nos ayuda muchísimo en sistemas grandes, ya que en vez de pensar en funciones, pensamos en las relaciones o interacciones de los diferentes componentes del sistema.

Smalltalk es el primer lenguaje de programación gráfico orientado a objetos, de tipado dinámico (una misma variable puede tomar valores de distinto tipo en distintos momentos) y reflexivo (capacidad que tiene un programa para observar y opcionalmente modificar su estructura de alto nivel); y es por eso que puede ser considerado un mundo virtual donde viven objetos que se comunican entre sí, mediante el envío de mensajes. Tuvo gran influencia en la creación de otros lenguajes como Java o Ruby.

Sus orígenes se encuentran en investigaciones realizadas por Alan Kay, Dan Ingalls y Ted Kaehler, entre otros, en Palo Alto, en el Xerox PARC, y su objetivo principal era el de crear un sistema que permitiese expandir la creatividad de sus usuarios, proporcionando un entorno para la experimentación, creación e investigación.

![alt text](https://github.com/Cheshire03/ProgOO/blob/main/img/alan-kay-dan-ingalls-david-c-smith.jpg "Fundadores")

### Define con tus palabras el concepto de abstracción, ¿Por qué se considera fundamental en programación? 

El concepto de abstracción viene relacionado con la *encapsulación*, en que mientras la encapsulación mantiene privados los atributos que el usuaio no ocupa ver o entender. Por lo que la abstracción es el siguiente paso lógico; el usuario interactúa con métodos simples, los cuales hacen procesos complicados en el fondo, para modificar los atributos de los objetos y su relación con otros objetos.

Considero es fundamental para la programación, ya que el usuario para el que están dirigidos los programas, no va a ser un experto en programación, ni lo ocupa ser. Por lo que la abstracción sirve para facilitar al usuario final el uso de las herramientas que creamos, sin necesidad de saber su funcionamiento.

### Explica el concepto de encapsulamiento, busca dos imágenes que te ayuden a describir el concepto, una que tenga algún sistema sin encapsulamiento y otra donde sí lo tenga. Menciona porque es importante y qué problemas puede evitar.

La encapsulación contiene toda la información importante de un objeto dentro del mismo y solo expone la información seleccionada al mundo exterior. 
Esta propiedad permite asegurar que la información de un objeto esté oculta para el mundo exterior, agrupando en una Clase las características o atributos que cuentan con un acceso privado, y los comportamientos o métodos que presentan un acceso público.

![alt text](https://github.com/Cheshire03/ProgOO/blob/main/img/abstracion.jpg "abstracción")

Como ejemplo, en la imagen de arriba, la persona de la izquierda solo puede ver al gato como una bola de pelos que acariciar; mientras que la persona de la derecha, que es veterinaria, conocer toda la estructura interna del gato. La persona de la izquierda representa al usuario y la de la derecha al programador.

La encapsulación de cada objeto es responsable de su propia información y de su propio estado. La única forma en la que este se puede modificar es mediante los propios métodos del objeto. Por lo tanto, los atributos internos de un objeto deberían ser inaccesibles desde fuera, pudiéndose modificar sólo llamando a las funciones correspondientes. Con esto conseguimos mantener el estado a salvo de usos indebidos o que puedan resultar inesperados. 

### Describe con tus palabras el concepto de herencia e ilustra el concepto con imágenes.

Básicamente, el concepto de herencia se refiere a cuando creas una clase superior, la cual va a tener subclases las cuales heredarán los atributos de la clase superior, pero pueden tener sus propios métodos y atributos individuales de todos modos. Por ejemplo, un carro y una moto funcionan de manera diferente, pero ambos son vehículos; y comparten ciertas características como: el motor, llantas, luces, etc.

![alt text](https://github.com/Cheshire03/ProgOO/blob/main/img/94489697-9910-4c8e-ade7-ee3fa996362f.jpg "herencia")

# UML

El Lenguaje Unificado de Modelado (UML) desempeña un rol importante no solo en el desarrollo de software, sino también en los sistemas que no tienen software en muchas industrias, ya que es una forma de mostrar visualmente el comportamiento y la estructura de un sistema o proceso. el UML ayuda a mostrar errores potenciales en las estructuras de aplicaciones, el comportamiento del sistema y otros procesos empresariales.  

El UML se implementó por primera vez en la década de los 90 gracias a tres ingenieros de software: Grady Booch, Ivar Jacobson y James Rumbaugh. Ellos querían desarrollar una forma menos caótica de representar el cada vez más complejo desarrollo de software, a la vez que separaban la metodología del proceso. 

Pronto se hizo evidente que varias organizaciones, incluidas Microsoft, Oracle e IBM, consideraron que UML era esencial para su propio desarrollo de negocios. Ellos, junto con muchas otras personas y compañías, establecieron los recursos necesarios para desarrollar un lenguaje de modelado hecho y derecho. Hoy, el UML sigue siendo la indicación estándar para los desarrolladores, así como para gestores de proyectos, propietarios de negocios, empresarios tecnológicos y profesionales de distintos sectores. 

**¿Cuáles son las ventajas del UML?**

- Simplifica las complejidades 
- Mantiene abiertas las líneas de comunicación 
- Automatiza la producción de software y los procesos  
- Ayuda a resolver los problemas arquitectónicos constantes 
- Aumenta la calidad del trabajo 
- Reduce los costos y el tiempo de comercialización

**Tipos de diagramas UML**

Existen dos tipos principales de diagramas UML: diagramas de estructura y diagramas de comportamiento (y dentro de esas categorías se encuentran varios otros). Estas variaciones existen para representar los numerosos tipos de escenarios y diagramas que usan los diferentes tipos de personas. 

**Herramientas para UML**

GitMind: Online Mind Map Tool

Gliffy: Software de gráficos basado en web

MagicDraw: Software propietario con licencia (Single, Floating, Mobile)

Lucidchart: Software de gráficos basado en web

Microsoft Visio: Software propietario de gráficos vectoriales y gráficos
IBM Rational Rhapsody	Entorno de desarrollo gráfico para el desarrollo y validación de software basado en modelos

[Carpeta con imágenes](https://github.com/Cheshire03/ProgOO/tree/main/img)

## Referencias

https://proyectoidis.org/smalltalk/

https://www.ionos.mx/digitalguide/paginas-web/desarrollo-web/las-mejores-herramientas-uml/

https://profile.es/blog/que-es-la-programacion-orientada-a-objetos/

https://www.microsoft.com/es-ww/microsoft-365/business-insights-ideas/resources/guide-to-uml-diagramming-and-database-modeling#:~:text=El%20Lenguaje%20Unificado%20de%20Modelado,de%20un%20sistema%20o%20proceso.

https://www.lucidchart.com/pages/es/que-es-el-lenguaje-unificado-de-modelado-uml
