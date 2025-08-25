# DESCRIPCION

El CSS es un lenguage de estilado, nos permite darle forma a nuestra aplicación y convertirla visualmente en un producto atractivo.
CSS (Cascade Style Sheet) ha ido evolucionando con el tiempo y nos ha dejado varias paginas o recursos que podemos utilizar para en poco tiempo comprender toda la complejidad que trae detras este lenguaje.

[IA](https://chat.qwen.ai)
[FlexBox](https://flexboxfroggy.com/#es)
[Playground](https://flexbox.tech)

### Situación de ROL

Un empleado que fue despedido dejó un desastre y lo unico que nos dejó fue una imagen de cómo deberia ser el resultado final, es tu tarea ahora.
Convertir la pagina entregada en ![Resultado 1](<Resultado 1.png>) (Ver imagen) modificando unicamente el [CSS](style.css)

Muchas veces para resolver problemas logaritmicos o de fuerte complejidad numerica tener una interfaz que facilite la visualizacion de datos ayuda mucho.

# TEST TEORIA

1. ¿Qué hace la propiedad display?
2. ¿Qué propiedad del display: flex nos permiten centrar el contenido de forma horizontal?
3. ¿Y verticalmente?
4. ¿Cómo se comporta el display: grid?
5. Explica las modificaciones que hiciste con tus palabras linea por linea

1.
En JavaScript, cuando hablamos de la propiedad display, en realidad nos referimos a la propiedad CSS display que indica cómo se muestra un elemento en la página. JavaScript no tiene una propiedad propia llamada display, pero sí puede modificarla o leerla a través del estilo de un elemento.
¿Qué hace display en CSS?
Define cómo se comporta un elemento en el flujo del documento, es decir, si se muestra como bloque, en línea, se oculta, etc.



2.
Cuando usamos display: flex, la propiedad que permite centrar el contenido de forma horizontal es:

✅ justify-content

Esta propiedad alinea los elementos a lo largo del eje principal (en un flex-direction: row —que es el valor por defecto— el eje principal es horizontal).
--display: flex;




3.
  justify-content: center; /* Horizontal */
  align-items: center;    /* Vertical */






4.
display: grid convierte a un elemento en un contenedor de cuadrícula bidimensional (grid container), lo que significa que podés organizar su contenido en filas y columnas de forma precisa, a diferencia de flex que trabaja en un solo eje principal.







5.
Se modifica el body ( contenedor de todos los elementos) para que centre los datos en la pantalla 
se realiza con un Display:flex;
se hace la misma modificación en el Header donde se ingresan las líneas: 
  display: flex; // para que muestre los datos centrados dentro del contenedor
  justify-content: center; // los alínea horizontalmente
  align-items: center;// los alínea verticalemente
y se utiliza Display grid dentro del contenedor de días para que queden distribuidos correctamente de acuerdo al día de la semana.








