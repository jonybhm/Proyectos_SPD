# Proyectos_SPD

Grupo 2 - 21/10/2022

Participantes:

De Castro, Jonathan
Acosta, Nicolas

Idea General:

Dividimos el algoritmo en dos partes:

1°- Usar 4 pulsadores para establecer el nivel que se mostrara en la primera fila del display.

NIVELES: 1, 2, 3, 4

2°-Usar el sensor de Temperatura (el mismo, ira de 0°C a 100°C) que se mostrara a través de la segunda fila del display y distintos leds de colores de la siguiente manera:

LED (Texto Display)
BLANCO (Sin hacer):
Rango Temperaturas: 0° - 70°
NARANJA (Hecho):
Rango Temperaturas: 70° - 90°
ROJO (Quemado): 
Rango Temperaturas: 90° - 100°

Establecemos un delay para cada temperatura, donde luego de un tiempo manteniéndose en la misma pasa a tomar dicho estado, solo se aplica en hecho y quemado. 

Entre  70° y 90° el delay se establece a 10 seg, luego de lo cual pasaría a estar hecho. Luego de esto si se mantiene la temperatura en este rango por 5 seg. más, pasará a estar quemado y suena el buzzer.

Luego de los 90° el delay se establece a 3 seg, luego de lo cual pasaría a estar quemado y suena el buzzer.
