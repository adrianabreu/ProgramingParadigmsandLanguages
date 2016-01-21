#Tema 2. Programación Imperativa, Ruby

[Abstracción]: Técnica para manejar la complejidad de los sistemas computaciones. Cómo dice John V. Guttag, su esencia radica en preservar la información relevante para el contexto dado y olvidar la que no lo es.

[Procedimiento]: Secuencia de instrucciones de un programa que realizan una determinada tarea, empaquetadas todas como una unidad. Otros nombres que reciben son: funciones, rutinas, métodos, subprogramas... 

[Pila de llamada]: Estructura de datos en forma de pila que almacena información de las subrutinas activas de un programa.

[Registro de activación]: La pila de llamada se divide entre partes contiguas llamadas stack frames (registros de activacion). Cada frame representa los datos asociados a una llamada a una función. Este registro tiene los argumentos dados a la función, las variables locales de la función y la dirección de donde se está ejecutando la función. 

[Programación procedural]: Se trata de un tipo de programación imperativa que funciona mediante la llamada a procedimientos. Cualquier procedimiento se puede llamar desde cualquier lado del programa, haciendo uso de la pila de llamada y generando incluso, la abstracción mentada al principio.

[Go to]: Instrucción que permitía desplazarse de una zona a otra del programa. Actualmente en desuso y considerada perjudicial, debido a que su abuso dificultaba enormemente seguir la traza de un programa.

[Teorema de la programación estructurada]: Teorema que dice que toda función computable puede realizarse si se combinan subprogramas en tres formas específicas (estructuras de control):

1. Ejecutando un subprograma, y despues otro subpgrograma (secuencia).
2. Ejecutando uno de los dos subprogramas de acuerdo a una expresión booleana (selección).
3. Ejecutar un subprograma hasta que se cumpla una expresión booleana (iteración).

##Ruby

Me gustaría no meterme en todos los pormenores de sintaxis del lenguaje. Pero existen ciertos detalles que considero interesantes.
Aún así, en [este] documento, he hecho un pequeño cheatsheet para poder consultar la sintaxis de Ruby.

[Ruby] es un lenguaje de programación interpretado, orientado a objetos y de propósito general. Creado por un desarrollador de origen japonés denominado "Matz" en los años 90.







[Abstracción]: https://en.wikipedia.org/wiki/Abstraction_%28computer_science%29
[Procedimiento]: https://en.wikipedia.org/wiki/Subroutine
[Pila de llamada]: https://en.wikipedia.org/wiki/Call_stack
[Registro de activación]: ftp://ftp.gnu.org/old-gnu/Manuals/gdb/html_node/gdb_41.html
[Go to]: https://en.wikipedia.org/wiki/Goto#Criticism
[Teorema de la programación estructurada]: https://en.wikipedia.org/wiki/Structured_program_theorem
[Ruby]: https://www.ruby-lang.org/es/
[este]: https://github.com/aabreuglez/ProgramingParadigmsandLanguages/blob/master/RubyCheatsheet.md
[Programación procedural]: https://en.wikipedia.org/wiki/Procedural_programming
