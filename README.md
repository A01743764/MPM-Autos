# MPM-Autos
Modelos de predicción multivariada para la estimación de precios de automóviles.

## Descripcion del Proyecto

Analisis estadistico multivariado para predecir el precio de vehiculos usados basado en variables clave como antiguedad, kilometraje y condicion. El proyecto implementa y compara diferentes modelos de regresion para identificar los factores que mas influyen en la valoracion de automoviles.

## Objetivos

- Desarrollar modelos predictivos para estimar el precio de venta de autos usados
- Identificar las variables mas significativas en la determinacion del precio
- Evaluar el rendimiento de diferentes enfoques de modelado estadistico
- Proporcionar herramientas confiables para la valoracion de vehiculos

## Estructura del Proyecto

```
ExcelFiles/
  Database_1.xlsx          # Datos principales de vehiculos
  Database_2.xlsx          # Datos adicionales de series de tiempo

MinitabFiles/
  Analisis_Regresion.mpx   # Archivos de analisis en Minitab
  Resultados_Estadisticos/

Reporte-MPM-Autos.pdf      # Reporte completo del proyecto
README.md                  # Este archivo
```

## Datos y Variables

### Dataset Principal: Database_1.xlsx
- Precio de Venta: Variable dependiente (pesos mexicanos)
- Antiguedad: Edad del vehiculo en años
- Kilometraje: Recorrido total en miles de kilometros
- Condicion: Variables categoricas (Promedio, Excelente, Unico Dueño)

## Metodologia

### Modelos Implementados
1. Regresion Lineal Simple
   - Precio vs Antiguedad
   - Precio vs Kilometraje

2. Regresion Multiple
   - Combinacion de multiples predictores
   - Transformaciones logaritmicas para mejor ajuste

3. Validacion de Modelos
   - Analisis de residuos
   - Pruebas de hipotesis (α = 0.05)
   - Verificacion de supuestos estadisticos

## Resultados Principales

### Modelo Optimo
- Ecuacion: ln(Precio) = 13.0863 - 0.1634 Antiguedad - 0.00515 Kilometraje
- R² ajustado: 90.56%
- Significancia estadistica: p-valor < 0.05 para todos los predictores

### Hallazgos Clave
- La antiguedad es el predictor mas significativo del precio
- El kilometraje muestra una relacion inversa con el precio
- La condicion del vehiculo aporta informacion valiosa adicional
- El modelo logaritmico ofrece el mejor ajuste a los datos

## Tecnologias Utilizadas

- Software: Minitab, Excel
- Metodos Estadisticos: Regresion lineal y multiple, ANOVA, analisis de residuos
- Metricas: R², MSE, MAPE, pruebas F y t

## Aplicaciones Practicas

- Compradores: Herramienta para evaluacion justa de precios
- Vendedores: Guia para fijacion de precios competitivos
- Agencias: Sistema de valoracion objetiva de inventario
- Financieras: Metodo para avaluo de garantias vehiculares

## Conclusiones

El modelo desarrollado explica mas del 90% de la variabilidad en los precios de vehiculos usados, demostrando ser una herramienta confiable para la estimacion de valores. La combinacion de variables cuantitativas y cualitativas permite capturar los factores clave que determinan el valor de mercado.

Proyecto de analisis estadistico aplicado - Valoracion objetiva de activos vehiculares
