# R-Bank-Captacion-VEC-VAR-Analysis

## Descripción

Análisis econométrico de la relación entre la captación total de HSBC y Scotiabank México utilizando modelos de series de tiempo. El estudio evalúa si existe una relación de largo plazo (cointegración) entre ambas variables mediante modelos VEC/VAR.

## Objetivos

- Analizar el comportamiento de la captación bancaria en México
- Determinar si existe relación de cointegración entre HSBC y Scotiabank
- Modelar las interacciones de corto plazo mediante VAR
- Evaluar efectos de impulso-respuesta entre las variables

## Datos

- **Fuente**: Banco de México
- **Variables**: Captación total mensual de HSBC y Scotiabank
- **Periodo**: Diciembre 2000 - Actual
- **Transformación**: Logaritmos naturales y primeras diferencias
- **Frecuencia**: Mensual

## Metodología

### Pruebas Preliminares
- Pruebas de estacionariedad (Dickey-Fuller Aumentado)
- Análisis gráfico de series temporales
- Transformación logarítmica y diferenciación

### Cointegración
- Método de Engle-Granger (dos etapas)
- Regresión lineal y análisis de residuos
- Prueba de estacionariedad en residuos

### Modelado VAR
- Especificación del modelo VAR
- Funciones de impulso-respuesta
- Descomposición de varianza

## Resultados

- **No se encontró cointegración** (τ = -2.0004 > -3.07)
- Relación potencialmente espuria en niveles
- **No existe relación de largo plazo** entre las captaciones
- Cada banco sigue su propia dinámica en el corto plazo
- Efectos cruzados limitados
- Fuerte autorregresión negativa

## Autor

- José Luis Corona López

## Referencias

- Banco de México. Indicadores gráficos Captación de Recursos. https://www.banxico.org.mx/IndicadoresGraficos/actions/contenidoPortal/pyramid/23/50?menu=221&seccion=1596&locale=es
- Hamilton, J. D. (1994). Time Series Analysis. Princeton University Press.
