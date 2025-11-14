
> [!NOTE]
Parcial Diseño y Desarrollo Web I
 Nombre: David Enrique Pérez Bejarano
 Fecha:07/11/2025
 La pagina web intenta dar a conocer uno de las tantas funciones tanto de los Sistemas Operativos como de lo que conlleva a saber sobre ellos como ser: sus lenguajes de programación, los servidores y como funcionan

> [!CAUTION]
Es necesario el copiado mediante git bash en condición de windows abajo del 11 o uso simple de la terminal para activar este archivo para su mejor comprensión

> [!IMPORTANT]
El archivo cuenta con uso pleno de html simple acompañado de css y un poco de Java respecto a operaciones aplicadas

```
<script>
                  let count = 0;
                  function incrementCounter() {
                    count++;
                    document.getElementById('counter2').querySelector('span').textContent = 'Contador: ' + count;
                  }
                  function resetCounter() {
                    count = 0;
                    document.getElementById('counter2').querySelector('span').textContent = 'Contador: ' + count;
                  }
                  function decrementCounter() {
                    if (count > 0) {
                      count--;
                      document.getElementById('counter2').querySelector('span').textContent = 'Contador: ' + count;
                    }
                  }
 </script>
 ```
