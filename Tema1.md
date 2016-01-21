#Tema 1. Modelos de Programación.

Un paradigma de programación es un "estilo", que sirve como base en la construcción de la estructura y los elementos de los programas.

Actualmente existen cuatro [paradigmas] de programación principales:

###### Nota: Esta respuesta fue una de las primeras dudas, pues bien podríamos agrupar los paradigmas en programación declarativa e imperativa.

1. **Programación imperativa**: Consistente en dar ordénes a la máquina. Describir pasos computacionales gestionados por estructuras de control. 
2. **Programación funcional**: Basados en el concepto de funciones matemáticas, consiste en evaluar expresiones y utilizar su resultado para algo. Da abstracción natural de las expresiones, elevandolas a funciones, y siendo éstas, un tipo de dato más.
3. **Programación lógica**: Consiste en extraer conocimiento de un conjunto de hechos y relaciones para responder a una pregunta.
4. **Programación orientada a objetos**: Encapsular datos y operaciones en estructuras denominadas objetos. Esos objectos se comunican entre sí para simular un fénomeno del mundo real.

¿Qué lenguajes representan estos paradigmas?
- Imperativos: Fortran, Algol, Pascal, C...
- Funcionales: Haskell, Lisp, R...
- Lógicos:  Prolog, Answer set programming...
- Orientados a Objectos: Ruby, Java, C++...

**¿Y los lenguajes concurrentes?**

En [Programming Language Pragmatics. Michael L. Scott. Morgan Kaufmann. Introducction. Pg. 12.Michael L.Scott] encontramos esto:

>Uno puede sospechar que los lenguajes concurrentes forman una clase separada, pero la distinción entre ejecución secuencial y concurrente es independiente de la clasificación hecha arriba.
>Muchos lenguajes concurrentes se escriben usando lenguajes secuenciales y librerías especiales.

Por tanto, podemos considerar la concurrencia como una característica de los lenguajes pero no un estilo de programación en sí.

###Un poco de historia

Algunas personas confunden estos dos conceptos tan comunes antaño:

**Lenguaje máquina**: Se trata de un conjunto de instrucciones ejecutadas directamente por una CPU.

**Lenguaje ensamblador**: Se trata de un lenguaje de programación de bajo nivel que simboliza el lenguaje máquina mediante el uso de mnemónicos.


###A día de hoy

Hoy en día trabajamos típicamente con lenguajes de alto nivel que son compilados o interpretados (o ambas cosas, como el caso de Java).

Por ello es importante aclarar las diferencias entre estos términos, a mí me gusta como se aclara en [Programmer Interview]:

- **Compilación**: Un programa se encarga de traducir el código fuente a un código específico para la máquina seleccionada. Luego, el ordenador podrá ejecutar este código por sí mismo.

- **Interpretación**: Un programa se encarga de leer y ejecutar el código fuente original. 

Pero que sean diferentes, no los excluyen. Si tuvieramos que decantarnos por un compilación o interpretación habria que tener en cuenta esto:

1. Los lenguajes compilados suelen ser más rápidos.
2. Los lenguajes interpretados suelen ser más flexibles y portables. 

###¿Por qué hay tantos lenguajes?

Un conjunto de razones pueden encontrarse en el libro [Programming Language Pragmatics. Michael L. Scott. Morgan Kaufmann. Introducction. Pg. 7.Michael L.Scott].

- Evolución.

- Propósitos específicos.

- Preferencia personal.

###¿Qué hace que un lenguaje triunfe?

De nuevo volvemos al libro [Programming Language Pragmatics. Michael L. Scott. Morgan Kaufmann. Introducction. Pg. 7.Michael L.Scott]


- Evolución.

- Propósitos específicos.

- Preferencia personal.

- Potencia de expresión.

- Curva de aprendizaje.

- Facilidad de implementación.

- Estandarización: La existencia de un estándar en el lenguaje y las librerías es lo único que permite asegurar la portabilidad del código. 

- Open source: Algunos lenguajes están más asociados que otros al mundo open source. Ahora que Unix ha evolucionado hasta convertirse en el sistema operativo por excelencia para la informática académica podemos ver como C por ejemplo, tiene una fama enorme.

- Compiladores excelentes.

- Intereses económicos, patronazgo, inercia: Cobol y Ada por ejemplo, le deben la vida al Departamento de Defensa de los Estados Unidos.

*Sólo se aclaran aquellos conceptos que se consideran necesarios*.

[paradigmas]: http://people.cs.aau.dk/~normark/prog3-03/html/notes/paradigms_themes-paradigm-overview-section.html
[Programming Language Pragmatics. Michael L. Scott. Morgan Kaufmann. Introducction. Pg. 7.Michael L.Scott]: https://books.google.es/books?id=GBISkhhrHh8C&printsec=frontcover&dq=Programing+language+pragmatics&hl=es&sa=X&ei=1h8oUv_HF6fZ0QXTzoGIDA&ved=0CDQQ6AEwAA#v=onepage&q=Programing%20language%20pragmatics&f=false
[Programming Language Pragmatics. Michael L. Scott. Morgan Kaufmann. Introducction. Pg. 12.Michael L.Scott]: https://books.google.es/books?id=GBISkhhrHh8C&printsec=frontcover&dq=Programing+language+pragmatics&hl=es&sa=X&ei=1h8oUv_HF6fZ0QXTzoGIDA&ved=0CDQQ6AEwAA#v=onepage&q=Programing%20language%20pragmatics&f=false
[Programmer Interview]: http://www.programmerinterview.com/index.php/general-miscellaneous/whats-the-difference-between-a-compiled-and-an-interpreted-language/