# OHCE Kata

Fuente original: http://garajeando.blogspot.com.es/2016/05/the-ohce-kata-short-and-simple-exercise.html 

**ohce** es una aplicación de consola que escribe lo que se escribe a través de la consola, pero dandole la vuelta.

Aunque parezca una aplicación tonta, **ohce** consta de una cosa o dos a tener en cuenta:

1. Cuando se arranca **ohce**, esta te saluda de forma diferente dependiendo de la hora del día, pero solo en Español.  
     - Entre las 20 y las 6, **ohce** te saludará diciendo: *!Buenas noches <tu_nombre>!*  
     - Entre las 6 y las 12, **ohce** te saludará diciendo: *!Buenos días <tu_nombre>!*  
     - Entre las 12 y las 20, **ohce** te saludará diciendo: *!Buenas tardes <tu_nombre>!*  
2. Cuando introduces un palíndromo, este le gusta a **ohce** y, después de darle la vuelta y mostrarlo, añade: *¡Bonita palabra!*  
3. Ohce sabe cuando parar, solo tienes que escribir Stop! y contestará Adios <tu nombre> y finalizará.

Este es un ejemplo de uso de ohce por la mañana:  
```
$ ohce Pedro
> !Buenos días Pedro!
$ hola
> aloh
$ oto
> oto
> !Bonita palabra!
$ stop
> pots
$ Stop!
> Adios Pedro
```

_**ohce** Kata - Agile Aragon_
