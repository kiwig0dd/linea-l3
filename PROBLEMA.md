# Maratón de Soluciones | Linea L-3

_Una línea de empaquetado pierde cajas, tiempo y personal. Tienen 60 minutos para rediseñarla, programar una herramienta que lo demuestre y defenderla ante el jurado._

### Situación

###### La planta empaca 1.200 cajas por turno (480 min, 40 min de descansos: 26.400 s productivos). El takt time exigido es 22 s por caja. Hoy la línea entrega unas 690 cajas. El paletizado y el etiquetado esperan caja a caja, el sellado se atasca varias veces por turno y no hay buffers entre estaciones: cuando una se detiene, las demás se detienen o se llenan.

### Fallas Observadas

#### Cuello de Botella

Encajado manual: 38 s por caja con 1 operario, casi el doble del takt.

#### Tiempos Muertos

Etiquetado espera 52 min por turno; sellado sufre microparos por 35 min.

#### Desacoplamiento

Sin buffers ni FIFO: la variabilidad de una estación se propaga a toda la línea

#### Ergonomía

Encajado: alcance de 62 cm, cajas de 9 kg, 14 ciclos por minuto, postura de tronco flexionado (RULA 6).

### Entregables

##### Computación:

- Herramienta en Python, dashboard o mini app de cálculo
- Debe recibir tiempos y operarios
- Debe devolver cuello de botella, capacidad y propuesta
- Debe correr en vivo ante el jurado

##### Pitch de 5 minutos:

- Problema y diagnóstico (1 min)
- Solución IE y demo digital (2,5 min)
- Impacto cuantificado y plan (1,5 min)

> ### Reglas y restricciones
>
> _Tiempo total: 60 minutos_
> Equipos mixtos de 4 a 6 personas, con al menos 2 de Industrial y 2 de Computación
>
> Máximo 9 operarios en la línea
> Sí se permiten ayudas de bajo costo: mesas, rodillos, gravedad, kanban
>
> Se pueden asumir datos faltantes, pero hay que declararlos en el pitch
>
> Se permiten documentación y librerías públicas
>
> **No se puede comprar maquinaria nueva**
> **No se permite código ya hecho para este caso**
