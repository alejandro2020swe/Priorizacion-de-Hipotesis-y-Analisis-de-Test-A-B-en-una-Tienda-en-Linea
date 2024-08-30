# Prioritización de Hipótesis y Análisis de Test A/B en una Tienda en Línea

## Descripción del Proyecto

Este proyecto se centra en la priorización de hipótesis para aumentar los ingresos en una tienda en línea y el análisis de un test A/B. La primera parte del proyecto implica priorizar las hipótesis utilizando los frameworks ICE y RICE. La segunda parte se enfoca en analizar los resultados de un test A/B para evaluar el rendimiento de diferentes estrategias.

## Datos Utilizados

### Datos para la Prioridad de Hipótesis
- **hypotheses_us.csv**: 
  - `Hypotheses`: Breves descripciones de las hipótesis.
  - `Reach`: Alcance del usuario (escala 1 a 10).
  - `Impact`: Impacto en los usuarios (escala 1 a 10).
  - `Confidence`: Confianza en la hipótesis (escala 1 a 10).
  - `Effort`: Recursos necesarios para probar la hipótesis (escala 1 a 10).

### Datos para el Análisis de Test A/B
- **orders_us.csv**:
  - `transactionId`: Identificador del pedido.
  - `visitorId`: Identificador del usuario.
  - `date`: Fecha del pedido.
  - `revenue`: Ingresos del pedido.
  - `group`: Grupo del test A/B.
- **visits_us.csv**:
  - `date`: Fecha.
  - `group`: Grupo del test A/B.
  - `visits`: Número de visitas.

## Parte 1: Priorizar Hipótesis

1. Aplicación del framework **ICE** para priorizar las hipótesis y ordenarlas en orden descendente de prioridad.
2. Aplicación del framework **RICE** para priorizar las hipótesis y ordenarlas en orden descendente de prioridad.
3. Comparación entre los resultados obtenidos con ICE y RICE para entender cómo cambia la priorización.

## Parte 2: Análisis de Test A/B

1. **Ingreso Acumulado**: Gráfico del ingreso acumulado por grupo.
2. **Tamaño de Pedido Promedio Acumulado**: Gráfico del tamaño de pedido promedio acumulado por grupo.
3. **Diferencia Relativa en el Tamaño de Pedido Promedio**: Gráfico que muestra la diferencia relativa entre el grupo B y el grupo A.
4. **Tasa de Conversión**: Gráfico de las tasas de conversión diarias por grupo.
5. **Análisis de Anomalías**:
   - Gráfico de dispersión del número de pedidos por usuario.
   - Percentiles 95 y 99 para el número de pedidos por usuario.
   - Gráfico de dispersión de los precios de los pedidos.
   - Percentiles 95 y 99 de los precios de los pedidos.
6. **Significancia Estadística**:
   - Diferencia en la conversión entre los grupos.
   - Diferencia en el tamaño promedio de pedido entre los grupos.
   - Análisis de los datos filtrados.

## Evaluación del Proyecto

- Preparación y limpieza de los datos.
- Priorización de hipótesis utilizando ICE y RICE.
- Análisis y representación gráfica de los resultados del test A/B.
- Cálculo de la significancia estadística y conclusiones basadas en los resultados.
