# ¿Qué es la complejidad algorítmica?  

Es una forma de medir cuántos recursos (tiempo o memoria) usa un algoritmo al crecer el tamaño de la entrada, normalmente expresado con la notación Big O.  

## ¿Cómo se analiza?  

Se observa cuantas veces se ejecuta cada operación *dependiendo del tamaño de la entrada (usualmente `n`)*.  

<pre>
function imprimirNumeros (n) {
  for ( let i = 0; i < n; i++ ) {
    console.log(i);
  }
}
</pre>

#### Análisis  

- Hay un solo bucle que se ejecuta `n` veces.

- Dentro del bucle solo hay una operación simple.

- Complejidad temporal: **O(n)**


---   

## Tipos de complejidad temporal más comunes  

1. Tiempo Constante - O(1) 


---


## Tipos de estructuras que afectan la complejidad

- Bucles (for, while): agregan O(n), O(n²), etc.  

- Condicionales (if/else): no afectan directamente, a menos que contengan bucles.  

- Recursión: depende de cuántas veces se llama la función recursiva.  

- Funciones anidadas: si tienes un bucle dentro de otro, puede ser O(n²).


---  
