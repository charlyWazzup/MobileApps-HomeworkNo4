##### ¿Qué es un patrón de Diseño?

Es el esqueleto de las soluciones a problemas comunes en el desarrollo de software. En otras palabras, brindan una solución ya probada y documentada a problemas de desarrollo de software que están sujetos a contextos similares. 


##### ¿En qué consiste el patrón Singleton?

El Singleton es quizás el más sencillo de los patrones que se presentan en el catálogo del GoF (disponible en el libro Patrones de Diseño [GoF95]. Es también uno de los patrones más conocidos y utilizados. Su propósito es asegurar que sólo exista una instancia de una clase. El patrón Singleton garantiza que una clase sólo tenga una instancia y proporciona un punto de acceso global a ésta instancia.


##### ¿En qué consiste el patrón Factory?

consiste en utilizar una clase constructora (al estilo del Abstract Factory) abstracta con unos cuantos métodos definidos y otro(s) abstracto(s): el dedicado a la construcción de objetos de un subtipo de un tipo determinado. Es una simplificación del Abstract Factory, en la que la clase abstracta tiene métodos concretos que usan algunos de los abstractos; según usemos una u otra hija de esta clase abstracta, tendremos uno u otro comportamiento.

##### ¿En qué consiste el patrón Builder?

 es usado para permitir la creación de una variedad de objetos complejos desde un objeto fuente (Producto), el objeto fuente se compone de una variedad de partes que contribuyen individualmente a la creación de cada objeto complejo a través de un conjunto de llamadas a interfaces comunes de la clase Abstract Builder.

El patrón builder es creacional. A menudo, el patrón builder construye el patrón Composite, un patrón estructural.

##### Herramienta ADB de Android

Las siglas ADB significan Android Debug Bridge y se corresponden con una herramienta de software que nos permite interactuar con nuestro smartphone Android desde un ordenador. Así, por ejemplo, a través de ADB podemos ejecutar comandos para copiar archivos desde el ordenador al teléfono o viceversa, flashear un revocery o el firmware completo e incluso reiniciar el dispositivo en modo recovery. 

Básicamente, en el ADB es la manera de cambiar profundamente el software de nuestro smartphone o por lo menos acceder a él. Por supuesto, todo esto se hace posible a través de un cable USB con el que conectamos el smartphone al ordenador. 

##### ¿Para qué sirve el operador _final_ en JAVA?

Indica que una variable, método o clase no se va a modificar, lo cuál puede ser útil para añadir más semántica, por cuestiones de rendimiento, y para detectar errores.

* Si una variable se marca como final, no se podrá asignar un nuevo valor a la variable.
* Si una clase se marca como final, no se podrá extender la clase.
* Si es un método el que se declara como final, no se podrá sobreescribir.

Algo muy a tener en cuenta a la hora de utilizar este modificador es que si es un objeto lo que hemos marcado como final, esto no nos impedirá modificar el objeto en sí, sino tan sólo usar el operador de asignación para cambiar la referencia.

##### ¿Qué lenguajes soportan la Sobrecarga de Operadores?

C++ y C. Java no lo soporta para evtar confusión entre programadores  que compartan programas. 

##### ¿Para qué sirve Gradle?

Gradle es una herramienta de automatización de la construcción de nuestro código que bebe de las aportaciones que han realizado herramientas como ant y maven pero intenta llevarlo todo un paso mas  allá. Para empezar se apoya en Groovy y en un DSL (Domain Specific Language) para trabajar con un lenguaje sencillo y claro a la hora de construir el build comparado con Maven. Por otro lado dispone de una gran flexibilidad que permite trabajar con ella utilizando otros lenguajes y no solo Java. Dispone por otro lado  de un sistema de gestión de dependencias sólido.

##### ¿En qué consiste la inyección de dependencias en desarrollo de software y  por qué es útil utilizarla?

La inyección de dependencias es un patrón de diseño de software usado en la Programación Orientada a Objetos, que trata de solucionar las necesidades de creación de los objetos de una manera práctica, útil, escalable y con una alta versatilidad del código.

En la mayoría de los frameworks actuales se aplica la Inyección de dependencias como parte de las herramientas y modelos que facilitan al programador. Como cualquier patrón de diseño de software trata de solucionar de una manera elegante un problema habitual en el desarrollo de software, por lo que también es idóneo utilizar este patrón en el desarrollo de proyectos a pequeña escala.

 Este patrón, como muchos otros, nos ayuda a separar nuestro código por responsabilidades, siendo que en esta ocasión sólo se dedica a organizar el código que tiene que ver con la creación de los objetos.

 Como ya sabemos, uno de los principios básicos de la programación, y de las buenas prácticas, es la separación del código por responsabilidades. Pues la inyección de dependencias parte de ahí.

 En el código de una aplicación con OOP (Programación Orientada a Objetos) tenemos una posible separación del código en dos partes, una en la que creamos los objetos y otra en la que los usamos. Existen patrones como las factorías que tratan esa parte, pero la inyección de dependencias va un poco más allá. Lo que dice es que los objetos nunca deben construir aquellos otros objetos que necesitan para funcionar. Esa parte de creación de los objetos se debe hacer en otro lugar diferente a la inicialización de un objeto.



##### Bibliografía

[¿Qué es un Patrón de Diseño?](https://msdn.microsoft.com/es-es/library/bb972240.aspx)


[El patrón Singleton](https://msdn.microsoft.com/es-es/library/bb972272.aspx#EEAA)

[Factory Method (patrón de diseño)](https://es.wikipedia.org/wiki/Factory_Method_(patrón_de_diseño))

[Builder (patrón de diseño)](https://es.wikipedia.org/wiki/Builder_(patrón_de_diseño))

[QUÉ ES ADB Y SUS COMANDOS MÁS IMPORTANTES](http://www.androidpit.es/que-es-adb-comandos-mas-importantes)

[Modificadores en Java](http://programacion.jias.es/2012/07/modificadores-en-java/)

[SOBRECARGA DE OPERADORES](https://prezi.com/gbj-ohp5s77d/sobrecarga-de-operadores/)

[¿Qué es Gradle?](http://www.arquitecturajava.com/que-es-gradle/)
