# AC

## Presentación



## Tema 1 - Fundamentos de diseño y evaluación de computadores

Los computadores han evolucionado a tener muchas mayores prestaciones con un 
menor consumo, tamaño, coste.

### Unidades

La memoria se mide en potencias de 2. El resto en potencias de 1.

### Máquina Von Neumann

Von Neumann no invento la máquina.

### Métricas

#### Coste

La sostenibilidad es el equilibro entre coste económico, social y ambiental.

##### Proceso de creación de un chip

Se sacan obleas de un lingote de silicio donde se imprime el circuito a partir
de un material fotosensible. Se descartan los circuitos con problemas y se
encapsula el resto.

##### Evaluación del coste

Coste de un circuito integrado = (coste del die + coste de testeo + coste de
empequetado y test final)/proporción de circuitos correctos

Coste del die (dado) = coste del waffer/(dies por waffer * die yield)

Dies por waffer = area util/area die

Die yield = waffer yield * 1/(1 + defectos por unidad de area * area die)^alfa
(medida de la complejidad aproximado al números de máscaras críticas)

#### Rendimiento

La latenia es el tiempo que transcurren entre la solicitud de un dato. Se suele
medir en ciclos o unidades de tiempo.

En cambio el ancho de banda es la cantidad de bytes que se transmiten por unidad
de tiempo.

Estas dos magnitudes no tiene porqué estar correlacionadas.

El rendimiento de un procesador se mide a partir de la inversa del tiempo de
ejecución, siendo el tiempo de ejecución = número instrucciones * ciclos por
instrucción * tiempo de ciclo.

##### Comparación de rendimiento

Ganacia = T_a/T_b

porcentaje = (T_a/T_b - 1) * 100

##### Mejora del rendimiento

Es mejor mejorar lo más común un poco que algo poco ejecutable mucho.

#### Consumo

La potencia consumida por un circuito CMOS tiene 3 componentes:

- Conmutación: potencia necesaria para cambiar el valor de un transistor.`P =
  Capacidad efectiva * tensión^2 * frecuencia`
- Corriente de fugas: fugas de electrones. `P = I * V`
- Corriente de cortocircuito: Corriente consumida en el tiempo que ambos
  transistores están activados a la vez. `P = `

Eficiencia energética = rendimiento / potencia = 1/energía consumida

#### Fiabilidad
