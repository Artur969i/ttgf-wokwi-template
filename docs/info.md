<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Este proyecto es un traductor digital que toma un número en código binario de 4 bits (unos y ceros) y lo convierte en un número visible del 0 al 9. Para lograrlo, usa interruptores de entrada que envían señales a un grupo de compuertas lógicas en el centro, las cuales actúan como filtros inteligentes para decidir qué rayitas del display derecho deben encenderse.

## How to test

Para probar el circuito, solo debes iniciar la simulación con el botón verde de encendido, mover las palanquitas rojas para elegir una combinación binaria y presionar el botón de reloj ("Paso") para que el sistema actualice la pantalla. Al instante verás cómo los cables con corriente se iluminan en verde brillante y el display de la derecha dibuja el número decimal correspondiente.

## External hardware

Si quisieras construir este circuito en la vida real, necesitarías un display LED de 7 segmentos para mostrar los números, una cajita de 4 interruptores (DIP switch) para ingresar los datos, dos botones pulsadores para el reinicio y el reloj, resistencias para proteger los componentes y una fuente de energía de 5 voltios con conexión a tierra.
