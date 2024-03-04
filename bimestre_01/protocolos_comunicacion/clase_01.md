# Clase 01 - 2/03/24
- Israel Pavelek
- Ultima clase tenemos que presentar un trabajo final
- El trabajo puede ser de integrar dos materias para poder hacer un tp unificado entre ambas
- Osea de aca a 8 clases hay que pensar algo para hacer y encima que este funcionando

## Temas de la materia
Device drivers
SPI
I2C
UART
USB

PENSAR TRABAJO PRACTICO FINAL

Condicion para aprobar, el 75% de asistencias
aprobar elt rabajo practico final
HAY dos tps en el medio

Primera entrega del trabajo Final, es para ver como esta


# Introduccion
Atmega328p es lo que esta adentro del arduino, no tiene I2C tiene TWI que es lo mismo que I2C solo que no querian pagar la licencia, ahora yua esta liberada
trabajamops con los cortex-M, de ARM (diseñador de micros pero que no los fabrica solo vende los diseños), implementado por STM
arquitectura de 32 bits
- Tenemos: GPIOs, UARTs, ADC, SPI, I2C, CAN
- Usamos el IDE de STM
- DOXYGEN es para la documentacion de codigo
- Cortex M0, son los mas chicos, 
- M3, son de 32 bits, economicos pero con mucho procesamiento
- M4, dentro estan los M4F, todo esto son los desarrollo de ARM, despues depende de cada fabricante. La F significa que tienen una aritmetica de punto flotante, es decir que si pongo 2 flotantos lo procesa por HARDWARE!. 
- Un float en arduino es una locura, gasta muchisima memoria. Una suma en flotante tiene que ponerle codigo para hacerlo, osea alinea exponente, hace operaciones con mantiza y ademas demanda mas tiempo. 

I2C: protocolo seria sincornico, es porque hay un linea de clock entre los dos.  La sincronia en los protocolos tiene que ver si hay o una una linea FISICA de clock que los sincronice.
Para usar USB hay que pagar un royalty
CAN (Controller Area Network): Nacio apra la red induustrial y para automotricesz
Protocolo I2S, es un protocolo para transportar sonido.
I3C, es I2C con SPI


# Device drivers en sistemas embebidos

