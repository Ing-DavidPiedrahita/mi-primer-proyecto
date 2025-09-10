# Cálculo de Combustible para Vuelos Diarios de una Aeronave

## 1. Explicación del Problema

El objetivo es calcular la cantidad de combustible necesario para los vuelos diarios de una aeronave. Este cálculo debe considerar múltiples factores que afectan el consumo de combustible, tales como:

- Número de vuelos programados en el día.
- Distancia de cada vuelo.
- Número de escalas.
- Peso de carga transportada.
- Reservas obligatorias de seguridad.
- Posibles desvíos por condiciones imprevistas (en pocas palabras, otra reserva).

Estos elementos permiten estimar con precisión el combustible requerido, optimizar costos y garantizar la seguridad operacional.

## 2. Tabla de Análisis de Variables

| Nombre de la variable         | Tipo       | Tipo de dato | Descripción                                                  |
|------------------------------|------------|--------------|--------------------------------------------------------------|
| cantidad_vuelos              | Entrada    | Entero       | Número total de vuelos programados en el día                |
| distancia_vuelo              | Entrada    | Flotante     | Distancia en kilómetros de cada vuelo                        |
| numero_escalas               | Entrada    | Entero       | Número de escalas en cada vuelo                              |
| peso_carga                   | Entrada    | Flotante     | Peso de la carga en kilogramos. Esta cantidad se obtendrá del problema propuesto anterior                               |
| reserva_seguridad            | Constante  | Flotante     | Porcentaje adicional de combustible por seguridad            |
| combustible_vuelo            | Salida     | Flotante     | Cantidad de combustible estimada para el vuelo               |
| combustible_total            | Salida     | Flotante     | Combustible total requerido para todos los vuelos            |
| precio_combustible           | Entrada    | Flotante     | Precio por litro de combustible                              |
| costo_total_combustible      | Salida     | Flotante     | Costo total del combustible necesario                        |

## 3. Sugerencias para Dividir el Problema en Funciones

- 

- 

- 

## 4. Ejemplos de Mensajes Claros para el Usuario

- "Ingrese la cantidad de vuelos del día:"
- "Distancia del vuelo número X:"
- "Peso de carga para el vuelo número X:"
- "Número de escalas para el vuelo número X:"
- "Precio por litro de combustible:"