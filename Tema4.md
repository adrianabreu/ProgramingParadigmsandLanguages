#Tema 4. Bloques

**Bloque**: Función anónima que se pasa como argumento a otras funciones. Visualmente corresponde a un conjunto de sentencias agrupadas por llaves ({ }) o por las palabras claves do y end.

**Proc**: Clase de ruby que nos permite definir un bloque como un objeto.

**Lambda**: Otra forma de instanciar bloques también perteneciente a la clase Proc. [Se diferencian] de estos en el tipo de retorno y en que lamdba comprueba los argumentos que se le pasan.

**Clausura**: Objeto (dejémmoslo como tal, puesto que puede ser un bloque o una función) que puede llamar a variables definidas en el entorno de su creación, no teniendo que ser locales

**Efectos laterales**: Cualquier cambio que una función produce fuera de su ámbito.

**Funciones de orden superior**: Aquellas funcionen que reciben una función como argumento y devuelven otra función como resultado.

**[DSL]**: Es un lenguaje de especificación dedicado a resolver un problema en particular. Se representa un problema en concreto y se provee una técnica para solucionar una situación particular. Por ejemplo, Rails es un DSL de Ruby.

[Se diferencian]: http://awaxman11.github.io/blog/2013/08/05/what-is-the-difference-between-a-block/
[DSL]: https://es.wikipedia.org/wiki/Lenguaje_espec%C3%ADfico_del_dominio