# Normas del Torneo Bocobot

El torneo consta de **5 pruebas diferentes** donde cada equipo competirá con su robot BocoBot. A continuación se detallan las reglas específicas de cada prueba.

!!! info "Algunos detalles pendientes"
    Los campos marcados con **TODO** están pendientes de confirmar. Se avisará a todos los equipos inscritos en cuanto se definan.

!!! note "Orden y sistema de turnos"
    El **orden de las pruebas se anunciará el día del torneo**. En principio, cada prueba tendrá **slots de 1-2 minutos** asignados aleatoriamente a cada equipo. Cada equipo dispondrá de un **comodín** que le permite "saltar" su turno e ir al final de la cola de esa prueba, ganando tiempo extra para ajustes de última hora (pendiente de confirmación).

---

## 1. Siguelíneas

**¿En qué consiste?** Tu robot deberá seguir un recorrido marcado en el suelo con cinta adhesiva, detectándola con su sensor de línea e intentando no perderse. Además, habrá obstáculos en el camino que el robot deberá esquivar sin tocarlos. ¡El más rápido gana!

### Especificaciones del circuito

| Característica | Detalle |
|----------------|---------|
| **Ancho de la cinta adhesiva** | 17 mm |
| **Color de la cinta** | Negra |
| **Longitud total del recorrido** | 4-5 metros |
| **Número de obstáculos** | 2 |
| **Dimensiones de los obstáculos** | Latas de 33 cl |
| **Ubicación de obstáculos** | En tramos rectilíneos |
| **Radio mínimo de curvas** | 5 centímetros |
| **Cruces** | No |

### Reglas

- **Objetivo**: Completar una vuelta completa en el menor tiempo posible
- **Tiempo máximo**: 90 segundos
- **Evasión de obstáculos**: El robot debe bordearlos por el exterior sin tocarlos
- **Penalizaciones**:
    - Tocar un obstáculo: +5 segundos al tiempo total
    - Tirar un obstáculo: Intento nulo
    - Salirse del recorrido y tardar más de 10 segundos en volver: Descalificación
    - Saltarse parte del recorrido: Descalificación

### Puntuación

| Posición | Puntos |
|----------|--------|
| 1º | 10 |
| 2º | 8 |
| 3º | 6 |
| 4º | 5 |
| 5º | 4 |
| 6º | 3 |
| 7º | 2 |
| 8º | 1 |

---

## 2. Limpieza

**¿En qué consiste?** Dentro de un recinto cuadrado delimitado con cinta adhesiva se colocarán varios objetos. Tu robot deberá empujarlos y sacarlos todos fuera del recinto lo más rápido posible; como un robot aspiradora, pero a la inversa. ¡El que "limpie" más rápido gana!

### Especificaciones del recinto

| Característica | Detalle |
|----------------|---------|
| **Forma del recinto** | Cuadrado |
| **Dimensiones** | 1,2 x 1,2 metros |
| **Delimitación** | Cinta adhesiva en el suelo |
| **Número de objetos** | 5 |
| **Tipo de objetos** | Cilindros tipo lata de refresco (330ml) o cubos de espuma 5x5cm |

### Reglas

- **Objetivo**: Sacar todos los objetos del recinto en el menor tiempo posible
- **Tiempo máximo**: 90 segundos (aunque puede ajustarse)
- **Descalificación**: Si el robot sale completamente del recinto

### Puntuación

Mismo sistema que Siguelíneas: 10, 8, 6, 5, 4, 3, 2, 1 puntos según la posición.

---

## 3. Sumo

**¿En qué consiste?** Dos robots se colocan dentro de un ring circular y se enfrentan uno contra uno. El objetivo es empujar al rival fuera del círculo, ¡como en el sumo japonés! Se compite en formato torneo por eliminación.

### Especificaciones del recinto

| Característica | Detalle |
|----------------|---------|
| **Forma del recinto** | Circular |
| **Diámetro** | 1 metro |
| **Delimitación** | Cinta adhesiva |
| **Peso máximo del robot** | 450 gramos |

### Reglas

- **Objetivo**: Sacar al robot rival del círculo
- **Posición inicial**: Robots de espaldas a 20 cm de distancia
- **Tiempo máximo por asalto**: TODO
- **Formato**: Eliminación directa (cuartos → semifinales → final)
- **Restricciones**:
    - Prohibido levantar al rival
    - Prohibido romper o dañar al rival
    - Tendréis que usar un parachoques que os proporcionaermos para proteger los sensores.

### Puntuación por fases

| Fase | Puntos |
|------|--------|
| **Ganador** | 12 |
| **Subcampeón** | 8 |
| **Eliminados en semifinales** | 5 |
| **Eliminados en primera ronda** | 0 |

!!! warning "Nota sobre eliminación temprana"
    Los equipos eliminados en la primera ronda del torneo de sumo **no reciben puntos** en esta prueba. ¡Cada combate cuenta!

---

## 4. Aceleración

**¿En qué consiste?** Tu robot sale a toda velocidad en línea recta, pero al final del recorrido hay una zona de frenado donde debe detenerse con la mayor precisión posible; como un frenado de F1. Si se pasa o se queda corto, ¡descalificación! Es una prueba simple que servirá de testing.

### Especificaciones del recorrido

| Característica | Detalle |
|----------------|---------|
| **Longitud del recorrido** | 2 metros |
| **Zona de frenado** | Últimos 40 cm |
| **Dimensiones zona de frenado** | 30 cm de ancho x 40 cm de largo, marcada con cinta adhesiva |
| **Marcado** | Línea en el centro del recinto |
| **Pared de poliespán** | Colocada al final del recinto de frenado |

### Reglas

- **Objetivo**: Llegar a la zona de frenado en el menor tiempo y detenerse lo más cerca posible del centro
- **Descalificación directa**:
    - Tocar la pared de poliespán (exceso de frenada)
    - Pararse antes de entrar al recinto de frenado (defecto)

### Puntuación

Fórmula mixta basada en dos factores:

- **50% Tiempo**: Se rankean todos los equipos por tiempo de llegada a la zona de frenado (más rápido = mejor posición)
- **50% Precisión**: Se rankean todos los equipos por distancia del morro del robot al centro de la zona de frenado (más cerca = mejor posición)

La puntuación final de cada equipo se calcula como la media de sus posiciones en ambos rankings.

---

## 5. Desfile

**¿En qué consiste?** ¡Aquí la creatividad es la protagonista! Cada equipo personaliza y decora su robot para hacer una "pasarela autónoma". Programad los LEDs, cread melodías con el buzzer, y añadid decoraciones físicas para impresionar al jurado. Es como un concurso de tuning, ¡pero de robots!

### Requisitos

- **Decoraciones modulares**: es importante que podáis **quitar las decoraciones rápidamente** antes de otra prueba (p.ej. Sumo, donde el peso importa), ya que en algunas estas no se permitirán!
- **Movimiento autónomo**: El robot debe moverse de forma autónoma durante el desfile (no vale exponerlo quieto)

### Criterios de evaluación

Se evalúan los siguientes aspectos:

- **Diseño físico**: Creatividad y estética de las decoraciones
- **Uso de LEDs**: Aprovechamiento de los 2 LEDs RGB (NeoPixel) de la placa + los demás LEDs
- **Uso del buzzer**: Melodías o tonos programados
- **Coreografía**: Originalidad del movimiento del robot

### Método de puntuación

- **Jurado docente** o **votación popular**
- Escala del 1 al 10

---

## Clasificación final

La puntuación total de cada equipo se calculará **sumando los puntos obtenidos en las cinco pruebas**. El equipo con mayor puntuación será el **ganador del Torneo Bocobot**. En caso de empate, se desempatará por la prueba de Siguelíneas (mejor tiempo).

¡Buena suerte a todos los participantes! :mechanical_arm:
