# MCOC-Proyecto-2
En este proyecto se busca poder simular el transporte de sedimento minero.
Integrantes

    Piedad Bull: https://github.com/piedadbull
    Matias Echagüe: https://github.com/meechaguep
    Pedro Naretto: https://github.com/PedroNaretto
    Catalina Solano: https://github.com/cpsolano

Entrega 4

En este proyecto se busca poder simular el transporte de sedimento minero de fondo de ríos. Esto se realizará en base a métodos langrangianos, es decir, que estudia el movimiento de cada partícula de forma individual.

Se tomarán como supuestos las siguientes condiciones:

    Diámetros de la partícula (d)= 15 mm
    Densidad de la partícula (rho_particula) = 2650 kg/(m^3)
    Densidad del agua (rho_agua) = 1000 kg/(m^3)
    Constante de drag (Cd) = 0.47
    Constante de lifting (Cl) = 0.2
    Constante de peso (Cm) = 0.5
    Velocidad del flujo en x (vfx) se comporta como un perfil logartitmico de la forma vfx = 0.18*/0.41*log(30*(y/d))
    Velocidad del flujo en y (vfy) = 0.0 m/s

Especificaciones computador (Pedro Naretto)

El intervalo de tiempo en los que grafica la posición de la partícula fue de (dt) = 0.001 s, con un tiempo máximo de simulación (tmax) de 1 s. Esto fué igual para las tres pruebas mostradas en los resultados.

Especificaciones del computador (Pedro Naretto)
El computador utilizado por mi parte es un acer de 15.6" Intel Core i5 de 2.3 GHz, 8 GB de Memoria RAM y originalmente 4 GB de RAM.
Resultados

El código se corrió con tres cantidades distintas de partículas. Primero se hizo la simulación con 4 partículas, con el cual se demoró 0.77 segundo en correr. Luego se volvió a realizar la simulación con 11 partículas, demorándose un tiempo de 9.54 segundos. Finalmente, el número de partículas fue 20, con el que demoró un tiempo mayor, el cual fue 39.14 segundos.

Entrega 6

A continuación se presenta la curva de tiempo vs número de particulas del programa.
![al text](https://github.com/PedroNaretto/MCOC-Proyecto-2/blob/master/Captura.PNG)
