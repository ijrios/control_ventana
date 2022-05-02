# SISTEMA DE CONTROL DE VENTANAS AUTOMATIZADO (sensor de lluvia, sensor de temperatura y sensor de luz analógicos). 

## OBJETIVOS 

•	Aplicar las definiciones y conceptos de las asignaturas vistas para implementar un sistema de control de ventanas con motores impulsados por Arduino.

•	Crear y probar sensores para manejar el abrir y cerrar de la ventana

•	Realizar el acondicionamiento de señales respectivo al sistema, para la correcta adquisición y manipulación de los datos en el proceso 

•	Llevar a cabo la puesta en funcionamiento del prototipo utilizando tecnología de tiempo real

## PROBLEMA

• El problema al tener una venta común y corriente es que al momento de no estar en el sitio ya sea casa, oficina, salón de universidad, etc. Cuando llueve o hace mucho sol y salimos del lugar sin percatarnos de si dejamos abierta o cerrada la ventana de nuestra casa, oficina o salón de universidad, tendríamos un problema en el lugar ya que podemos tener cosas al pendiente cerca a la ventana y se puede dañar con la lluvia. El punto es que para evitar esos percances implementaríamos la ventana inteligente, que funciones con sensores de temperatura, luminosidad y humedad para que por medio de estos sensores la ventana se abra y se cierra dependiendo clima de la ciudad, teniando así dos funcionalidades.

## DESCRIPCIÓN TECNOLÓGICA

• Por medio de la información que tomen los sensores, los motores harán mover los engranajes haciendo que la ventana se abra o se cierre dependiendo la situación climática, se podrá controlar la ventana de manera manual.
Los sensores van a emitir una señal al microcontrolador programado para que este haga que los motores cierren o abran la ventana, todo este sistema alimentado energéticamente por un panel solar.

## ESTADOS

• Caso Base: La ventana se cierra cuando está lloviendo o boton manual en estado 1

• Caso 1: La ventana se abre con mucha luz (dia)

• Caso 2: La ventana se abre con mucha luz (dia) y temperatura alta

• Caso 3: La ventana se cierra con poca luz (noche) y temperatura baja

• Caso 4: La ventana se abre con poca luz (noche) y temperatura alta
