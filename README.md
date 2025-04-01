# MSF-Practica-2
[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Dario-Mtz/MSF-Practica-2)
# MSF-Practica-2
Practica 2: Mecanica Pulmonar
# Modelado de Sistemas Fisiológicos. Práctica 2: Mecanica Pulmonar [Martinez21210684]

## Autor
Dario Antonio Martinez Camarena

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: L21210684@tectijuana.edu.mx

Práctica: Sistema respiratorio
  Objetivo. Diseñar un controlador que permita formular un protocolo de tratamiento para que un paciente
 con en sema (caso) presente la misma presión alveolar que un individuo sano (control).
 Michael Khoo modeliza el sistema respiratorio mediante el circuito RLC de tercer orden.
## Actividades
Actividades
 1. Calcular analíticamente la función de transferencia del sistema pulmonar.
 2. Establecer el modelo de ecuaciones integro-diferenciales.
 3. Determinar el error en estado estacionario y la estabilidad del sistema en lazo abierto.
 4. Construir el diagrama de bloques como se indica en la Figura 5.4.
 5. Diseñar el controlador con Simulink utilizando el bloque PID Controller y la herramienta Tune para
 sintonizar los valores óptimos para cada una de las ganancias kP, kI y kD.
 6. Ilustrar el cambio del ujo de aire y el volumen tidal en respuesta a las siguientes formas de onda
 de presión sinusoidal en la apertura de la vía aérea [Pao (t)] :
 a) 15 respiraciones por minuto con una amplitud (A) de 2:5 cmH2O, es decir, respiración normal 98
 b) 30 respiraciones por minuto con una amplitud (A) de 1:5 cmH2O, es decir, respiración elevada
 o taquipnea.
 8. Determinar la respuesta a la función sinusoidal [u(t) = Asin!t] en el intervalo t 2 [0;30] (segundos),
 en Python, Simulink y Multisim en lazo abierto y en lazo cerrado con el controlador.
 9. Elaborar el diagrama biológico del sistema con BioRender.com.
 10. Discutir los resultados obtenidos en la experimentación in silico y elaborar el reporte de la práctica.

## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus para la asignatura de Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/scl/fi/4gl55ccrjm9yulvziikxs/Modelado-de-Sistemas-Fisiologicos.pdf

[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway,
 New Jersey, USA: IEEE Press, 2018, Section 2, pages 24, 44 and 53
