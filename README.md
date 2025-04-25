# Análisis de Rentabilidad de Tiendas

## Descripción del Proyecto

Este proyecto analiza datos de ventas de cuatro tiendas diferentes con el objetivo de identificar la tienda menos rentable para considerar su venta. El análisis se basa en datos reales de ventas obtenidos del repositorio de Alura Latam para el Challenge de Data Science.

## Datasets

Los datos utilizados provienen de los siguientes archivos:
- tienda_1.csv
- tienda_2.csv
- tienda_3.csv
- tienda_4.csv

Estos datasets contienen información sobre transacciones de ventas incluyendo:
- Producto
- Categoría del Producto
- Precio
- Costo de envío
- Fecha de Compra
- Vendedor
- Lugar de Compra
- Calificación
- Método de pago
- Cantidad de cuotas
- Datos geográficos (lat, lon)

## Metodología

El análisis se enfoca en calcular la rentabilidad de cada tienda considerando:

1. **Margen por venta**: Diferencia entre el Precio y el Costo de envío.
2. **Rentabilidad total**: Suma de los márgenes de todas las ventas realizadas por cada tienda.
3. **Indicadores adicionales**: 
   - Margen promedio por venta en cada tienda
   - Volumen de ventas (número de transacciones)
   - Rentabilidad por lugar de compra (cuando está disponible)

## Estructura del Código

El script principal `analisis_rentabilidad.py` contiene todo el código necesario para:

- Cargar los datos de las cuatro tiendas
- Calcular los indicadores de rentabilidad
- Generar visualizaciones
- Identificar la tienda menos rentable

## Resultados

El análisis proporciona:

- Una tabla clasificando las tiendas por su rentabilidad total
- Una visualización gráfica de la rentabilidad por tienda
- Detalles sobre márgenes promedio y volumen de ventas
- Una recomendación clara sobre qué tienda debería ser considerada para la venta

## Requisitos

Para ejecutar este análisis se requiere:

```
pandas
matplotlib
```

## Cómo Ejecutar el Análisis

1. Clone este repositorio
2. Instale las dependencias: `pip install pandas matplotlib`
3. Ejecute el script: `python analisis_rentabilidad.py`

## Autor

[Tu Nombre]

## Agradecimientos

- Datos proporcionados por el challenge de Data Science de Alura Latam
