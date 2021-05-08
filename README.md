# MINDRover
A four wheeled human powered vehicle created for the NASA Human Exploration Rover Challenge 2021.

Although we call him "Robert" :)

#TODO:

- DIMA
- DIMA and MIND websites

Programa de Investigación en Transporte, Movilidad y Territorio (PIT) is a research group within the Department of Civil and Agricultural Engineering at the Universidad Nacional de Colombia working on issues such as transport, mobility and territory.

Observatorio de Diseño Aplicado (ODA) is a research group within the School of Industrial Design at the Universidad Nacional de colombia working on the development and consolidation of a design culture in Colombia.

PIT website: https://ingenieria.bogota.unal.edu.co/pit/
ODA website: http://odaobservatorio.unal.edu.co/

## Notes for X CIMM

- Estructura: simulación tipo beam + simulación en elementos tridimensionales
- Modelado matématica basado en estática para sacar fuerzas y condiciones en el diseño general (resultado: fuerzas y condiciones de falla [pasa de quieto//no desliza y pasa a volcarse]

Componentes:

- Modelo de elementos finitos (simples y elementos tridi es más mejor :v) con convergencia (refinar la malla hasta que no varíe significativamente), sino hay una convergencia los resultados no son válidos.
- Mecanismos se simularon (no FEA, sino dinámicas) mediante elementos tipo link: Simplificar la geometria a puras lineas y mirar cómo se mueven esas lineas (asumiendo que son indeformables).
- Optimización topológica (transmisión), paso por diferentes etapas. Optimización > Modela > Fea (según resultados) se elije si sí o no; hay que elegir un criterio (falla, parada)
- Dirección: sim dinámica para determinar los radios de giro, sensibilidad y cargas aplicadas. Engranes porque se pueden cambiar esos paramétros.
- Transmisión: poleas dentadas (caras) (idea: imprimirlas en 3d, tiempo, prototipo)
- Molde llantas: Rapid tooling y rapid prototyping. (Caro), materiales mas economicos, funcionamiento como NASA


Cambios/Lecciones:

- Fabricar esos engranes es complicado, hacer prototipos en madera, caja de cambios en 3D. Parámetros uno se da cuenta conforme el diseño avanza.

Diapositivos:

- Inicio, intermedio, final.
