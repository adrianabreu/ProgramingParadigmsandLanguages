#Tema 3. Programación Orientada a Objetos

Se han tomado estas definciones de diversas fuentes bibliográficas tales como:

[Java Documentation](https://docs.oracle.com/javase/tutorial/java/concepts/)
[Ruby Doc](http://ruby-doc.org/)
[Tutorials Point](http://www.tutorialspoint.com/ruby/ruby_classes.htm)

**Clase**: Plantilla que permite definir el conjunto de características, funcionalidades y atributos de los que va a disponer un objeto.

**Objeto**: Paquete de software que permite represetar objetos del mundo real. Define un estado (conjunto de variables) y un comportamiento (conjunto de métodos). 

**Variable local**: Variables que solo pueden accederse desde la función o bloque de instrucciones donde se declaran. (_variablelocal o variablelocal)

**Variable de instancia**: Es una variable que puede ser accedida desde cualquier parte de una instancia. (@variable)

**Variable de clase**: Es una variable común a todos los objetos de una misma clase. (@@variable)
 
**Variable global**: Variables que pueden ser accedidas desde cualquier lugar del programa. ($variable)

**Getter y Setter**: Métodos que permiten obtener (getter) o modificar (setter) los atributos correspondientes que se han aislado mediante encapsulación.

**Polimorfismo:** Capacidad de presentar la misma interfaz para diferentes subtipos de datos. Creando una abstracción génerica.

**[Tipo]**: Aplicamos dos definiciones aquí.

1. Formal: Interfaz de un valor -el conjunto de peticiones a las que puede responder-.

2. Informal: Conjunto de cosas que puedes hacer con un valor particular. 

**Diferencia entre Tipo y Clase**: Una clase define lo que puedes hacer con objetos de esa clase, por tanto una clase define un tipo. Sin embargo una clase hace mucho más que eso, puesto que define tambien como se implementan esos métodos. 

Por tanto, un objeto puede tener solo una clase, pero puede tener múltiples tipos, ya que cada superclase provee un subconjunto de funcionales que están disponibles en la clase del objeto.

**Herencia**: Relación que existe entre dos clases donde una actúa como "padre" y cede sus atributos y métodos a una clase "hija". Es posible ver una "herencia múltiple" pero en Ruby solo está disponible la herencia simple.

**Invalidación de un método**: Técnica que modifica el comportamiento de la clase heredada reescribiendo el método que ha recibido de su padre.

**[Encapsulación]**: Aislamiento de los datos miembros de un objeto, de tal forma que solo se pueda cambiar mediante las operaciones definidas para ese objeto.

**Módulos**: Forma de agrupar métodos, clases y constantes. En Ruby los módulos no son instanciables, pero proveen de dos ventajas, de un espacio de nombres y de la implementación de los mix-in.

**Mix-in**: Clase que no está heredada para ser autónoma sino para proveer cierta funcionalidad que debe ser heredada por una subclase.

**Espacio de nombres**: Contenedor abstractao que permite mantener una relación entre distintos elementos. 

**Clases Abstractas**: Clases que poseen métodos declarados pero no definidos.

**Clases Concretas**: Clases que tienen definidos todos sus métodos declarados.

**[Métodos Singleton]**: Métodos definidos para una instancia particular que debe tener un comportamiento especial al margen de los elementos que ha recibido de la clase.

**[Eigenclass]**: Clases anónimas que mantienen los métodos singleton de los objetos. 

**String Interpolation**: Proceso de evaluar una string literal que contiene uno o más párametros sustituibles, generando un resultado en el cual los párametros son reemplazados por sus valores correspondientes.


##Herramientas de Ruby

**[RVM]**: Gestor de versiones para Ruby, permite cambiar fácilmente la versión instalada.

Debugger: Herramienta que permite ver el estado del programa en diversos puntos marcados a lo largo del código, de tal forma que puedan detectarse errores.

IRB: Intérprete interactivo de Ruby, 

**[Pry]**: Alternativa a IRB que incrementa una elevada cantidad de mejoras tales como: Resaltado de sintaxis, identación de código y otra serie de características que permiten depurar mejor el código.

**[Bundler]**: Gestor de dependencias de Ruby.

**Rake**: Gestor de tareas de Ruby, permite automatizar procesos, tales como publicar en un ftp, ssh... 

**Rdoc**: Herramienta para la gestor de documentación del código.

**Guard**: Herramienta de integración continua. Permite "vigilar" una serie de ficheros en el proyectos y ejecutar una acción ante posibles cambios.

##Unit testing y TDD

**Unit testing**: Método de testeo de software en el cual alguna o varias partes de un programa se asocian con un datos o procedimientos específicos para comprobar que el resultado obtenido es el esperado.

**Assertion**: Pruebas elementales que confirman si el código que hemos desarrollado genera el resultado esperado.

**TDD**: Filosofía de desarrollo dirigido por pruebas que pretende verificar que el comportamiento de un objeto (respecto a sus métodos y atributos) sea el esperado.

**BDD**: Abstracción del TDD llevado a enfocarse al comportamiento de los programas, generando un dominio de lenguaje específico que permite hacer pruebas de desarrollo con una sintaxis mucho más natural.

**Rspec**: Herramienta que implementa BDD en Ruby. (¡No olvides que la sintaxis should quedará obsoleta!)



[Tipo]: http://stackoverflow.com/questions/468145/what-is-the-difference-between-type-and-class
[Encapsulación]: https://es.wikipedia.org/wiki/Encapsulamiento_%28inform%C3%A1tica%29
[Métodos Singleton]: http://www.rubyist.net/~slagell/ruby/singletonmethods.html
[Eigenclass]: http://madebydna.com/all/code/2011/06/24/eigenclasses-demystified.html
[RVM]: https://rvm.io/
[PRY]: http://pryrepl.org/
[Bundler]: http://bundler.io/
[Rake]: http://rake.rubyforge.org/
[Rdoc]: http://rdoc.sourceforge.net/
