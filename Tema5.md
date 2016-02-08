#5. Hilos y Fibras

**Fibra**: Una fibra en ruby es a efectos prácticos un bloque cuya ejecución puede ser suspendida -devolviendo el control al que lo llamó-. Es posible continuar con la fibra en el punto en el que fue puesta en suspensión, y destaca en que mantiene su estado através de las llamadas. 

**Thread**:  Son la implementación del modelo de programación concurrente en Ruby. Son objetos de la cclase Thread y su ejecución puede ser pausado y su control cedido, pero es el sistema el que los gestiona, no el usuario.

**Condición de carrera**: Es la situación en la que múltiples procesos -o hilos- entran en conflicto a la hora de acceder a un dato, ya que acceden al mismo instante de tiempo. Esto puede dar lugar a una corrución de datos, ya que puede haber un valor no esperado como consecuencia de la incertidumbre en el orden de los accesos.

**Exclusión Mutua**: En programación concurrente es el requisito que asegura dos procesos no están en su sección crítica en el mismo momento. La sección crítica es normalmente un fragmento de código donde puede modificarse
el valor de un recurso compartido. 

**Semáforos**: Son objetos de la clase Mutex que coordinan el acceso a los datos compartidos en hilos concurrentes.

**Abrazo mortal**: Una condición de bloqueo generada por la competitividad por los recursos. Pongamos un ejemplo, dos procesos requieren de dos recursos para completarse. El primer proceso accede a un recurso y lo bloquea en su ejecución.
El segundo proceso accede al segundo recurso y lo bloquea también. Ahora ambos bloquean ambos recursos y ninguno puede completarse, quedan los dos en espera
indefinida.

**Variables de Condición**: Mecanismo de protección para los deadlock, que permiten la comunicación mediante eventos o condiciones entre dos hilos. De esta forma, un hilo puede esperar por la ejecución del otro sin miedo a quedar en un bucle infinito al estar dentro de un mutex.

