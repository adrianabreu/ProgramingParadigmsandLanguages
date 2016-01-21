#Ruby Cheatsheet

Esta pequeña recopilación solo pretender servir de repaso. Por favor, ante cualquier error contacta conmigo en: aabreuglez@gmail.com. Intenta consultar siempre una fuente actualizada.

###Comentarios:
`#Comentario de una sola linea`
```
=begin
 Esto es
 un comentario
 multilinea
=end
```

###Cadenas:

1. Cadenas literales (no se interpretan): 
   ```
   'Hola\nchicos'
   Hola\nchicos
   ```
   (No genera un salto de línea como sería lo esperado).

2. Cadenas: 
   ```
   "Hola\nchicos"
   Hola
   chicos
   ```
3. Símbolos: Cadenas inmutables. `:simbolo` o `:"simbolo con espacios"`

###Condicionales:
```
if condición
   do_something
elsif condition
   do_something
else
   do_something
end
```

```
unless condición [then]
   do_something
else
   do_something
end
``` 

###Bucles:
```
for variable in rango
   do_something
end
```

```
while/until condición [do]
    do_something
end
```

##EN CONSTRUCCION