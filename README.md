Nombre:Jose Alfredo Hernandez Hernandez.

Ejercicio Resta 👋

Primero, en la sección `.data`, se definen algunos mensajes que serán mostrados en la pantalla.  `msg_1` contiene el mensaje "Resta de 3 números enteros!" y `msg_2` tiene el mensaje "Se restarán los valores de 9 y 3 y 2". Además, se definen algunas variables numéricas como `num1`, `num2`, `num3` para representar los números que se van a restar, y `res` para almacenar el resultado de las restas.

Luego, en la sección `.text`, empieza la ejecución del programa con la etiqueta `_start`.

1. El programa escribe el mensaje `msg_1` que indica el propósito del programa.
2. Después, escribe el mensaje `msg_2` que especifica qué números se van a restar.
3. Luego, realiza la resta del segundo número (`num2`) al primero (`num1`), y guarda el resultado en `res`.
4. Realiza otra resta, esta vez del tercer número (`num3`) al resultado anteriormente guardado en `res`.
5. Convierte el resultado a su equivalente en código ASCII, para poder imprimirlo correctamente.
6. Posteriormente, imprime el mensaje `msg_3` que indica que va a mostrar el resultado.
7. Finalmente, imprime el resultado de la resta almacenado en `res`.

Ejercicio Multiplicacion 👋

En primer lugar, en la sección `.data`, se definen dos números enteros de 32 bits (`num1` y `num2`) con un valor de 2 cada uno, y se declara un mensaje que dice "Resultado: ".

Luego, en la sección `.bss`, se reserva espacio para almacenar el resultado de la multiplicación en la variable `mult`.

En la sección `.text`, comienza la ejecución del programa con la etiqueta `_start`.

1. Se carga el primer número (`num1`) en el registro `eax`.
2. Se realiza la multiplicación del contenido de `eax` con el segundo número (`num2`), y el resultado se guarda nuevamente en `eax`.
3. Se almacena el resultado de la multiplicación en la variable `mult`.
4. Se prepara un bucle para convertir el resultado de la multiplicación en una cadena de caracteres.
5. Se divide el resultado entre 10 para obtener el dígito de la unidad.
6. Se convierte el dígito en su representación ASCII y se guarda en la variable `mult`.
7. Se repiten los pasos 5 y 6 hasta que el resultado sea cero.
8. Se escribe el mensaje "Resultado: " en la salida estándar.
9. Se escribe el resultado de la multiplicación convertido a una cadena de caracteres en la salida estándar.
10. Se realiza una llamada al sistema para salir del programa.

Ejercicio Division👋

En la sección `.data`, se definen mensajes que se mostrarán al usuario, indicando que se va a realizar una división entre dos números enteros de 32 bits. También se declaran las variables `num1` y `num2` con los valores 9 y 3 respectivamente.

En la sección `.bss`, se reserva espacio para almacenar el resultado de la división en la variable `res`.

En la sección `.text`, comienza la ejecución del programa con la etiqueta `_start`.

1. Se escribe en la salida estándar el mensaje que indica el propósito del programa.
2. Se escribe otro mensaje indicando qué números se van a dividir.
3. Se cargan los números `num1` y `num2` en los registros `eax` y `ebx` respectivamente.
4. Se inicializa el registro `edx` a 0 antes de la división.
5. Se realiza la división de `eax` por `ebx`, el resultado se almacena en `eax`.
6. Se convierte el resultado de la división a su equivalente en código ASCII.
7. Se guarda el resultado en la variable `res`.
8. Se escribe un mensaje que indica que se mostrará el resultado de la división.
9. Se escribe el resultado de la división en la salida estándar.
10. Finalmente, se realiza una llamada al sistema para salir del programa.









Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
