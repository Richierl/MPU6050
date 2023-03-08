![portadaSensor_page-0001](https://user-images.githubusercontent.com/124211951/223593512-d42a779b-1150-41f4-956e-555673fd3af7.jpg)

# Sensor MPU6050 Accelerometer + Gyroscope
El MPU6050 es una unidad de medición inercial o IMU (Inertial Measurment Units) de 6 grados de libertad (DoF) pues combina un acelerómetro de 3 ejes y un giroscopio de 3 ejes. Este sensor es muy utilizado en navegación, goniometría, estabilización, etc. 

## Sensor Giroscópico   
Un giroscopio es un dispositivo que funciona para medir velocidades angulares basándose en el mantenimiento del impulso de rotación. Si intentamos hacer girar un objeto que está girando sobre un eje que no es el eje sobre el que está rotando, el objeto ejercerá un momento contrario al movimiento con el fin de preservar el impulso de rotación total. 

El giroscopio muestra el cambio de rango en rotación en sus ejes X, Y y Z.


## Acelerómetro
Mide la aceleración, inclinación o vibración y transforma la magnitud física de aceleración en otra magnitud eléctrica que será la que emplearemos en los equipos de adquisición estándar. Los rangos de medida va desde las décimas de g, hasta los miles de g. 

A continuación se mostraron los rangos de escala y el valor máximo raw. 
<br>

Rango de escala completa Giroscopio | Sensibilidad del Giroscopio 
------------------------------------|-----------------------------
±250                                | 131
±500                                | 65.5
±1000                               | 32.8
±2000                               | 16.4

Rango de escala completa Acelerómetro | Sensibilidad del Acelerómetro
--------------------------------------|------------------------------
±2                                    | 16384
±4                                    | 8192
±8                                    | 4096
±16                                   | 2048

## Imagen del sensor
![image](https://user-images.githubusercontent.com/124211951/223594083-6995d63b-e303-441e-8771-bece84a7d66b.png)

<br>

## Especificaciones del MPU6050
* Salida digital de 6 ejes.
* Giroscopio con sensibilidad de ±250, ±500, ±1000, y ±2000dps.
* Acelerómetro con sensibilidad de ±2g, ±4g, ±8g y ±16g.
* Algoritmos embedidos para calibración.
* Sensor de temperatura digital.
* Entrada digital de video FSYNC.
* Interrupciones programables.
* Voltaje de alimentación: 2.37 a 3.46V.
* Voltaje lógico: 1.8V±5% o VDD.
* 10000g tolerancia de aceleración máxima. 


