# [Título del proyecto: ej. Análisis de productos y reseñas de Amazon por categoría]



## Pregunta central

¿Cómo varían los ratings, las reseñas y los descuentos según la categoría del producto en Amazon?

## Sobre el dataset

- **Fuente**: [Kaggle / enlace al dataset]
- **Tamaño**: 1,465 filas y 16 columnas
- **Qué contiene realmente**: catálogo de productos con precios, descuentos, calificaciones y reseñas de usuarios.
- **Qué NO contiene**: cantidades vendidas, fechas ni montos de venta. Por eso este proyecto analiza **productos y reseñas**, no ventas.

## Herramientas

- Python (pandas) para cargar y exportar datos
- SQLite y SQL para limpiar, agrupar y consultar
- Power BI para la visualización

## Metodología

1. **Carga**: [cómo cargaste el CSV y creaste la base `AmazonDB.db`].
2. **Validación de tipos**: [qué columnas venían como texto aunque parecían números].
3. **Limpieza**:
   - `rating_count`: [problema encontrado y cómo lo resolviste]
   - `rating`: [valor inválido encontrado y qué hiciste con él]
   - `discounted_price`, `actual_price`, `discount_percentage`: [símbolos y separadores que quitaste]
4. **Categoría**: [por qué usaste solo la categoría principal y cómo la extrajiste].
5. **Umbral de muestra**: [qué tamaño mínimo exigiste por categoría, con qué cláusula SQL y por qué ese número].
6. **Consultas principales**: [lista breve de qué calcula cada una].

## Hallazgos

| Categoría | Productos | Rating promedio | Reseñas promedio | Descuento promedio |
|---|---|---|---|---|
| [ ] | [ ] | [ ] | [ ] | [ ] |

[2 o 3 observaciones, redactadas como relación o asociación entre variables, no como causa.]

## Visualizaciones

![Descripción del gráfico](ruta/a/imagen.png)

[Una línea por gráfico explicando qué muestra.]

## Limitaciones

- **Tamaño de muestra desigual**: [categorías con 1 o 2 productos y por qué sus promedios no son confiables].
- **Diferencias pequeñas**: [si la diferencia entre categorías es chica frente a la variabilidad, dilo].
- **Sin datos de ventas**: [qué preguntas no se pueden responder con este dataset].
- **Texto de reseñas sin analizar**: [`review_content` queda fuera de este proyecto].

## Cómo reproducirlo

1. Clona el repositorio.
2. Instala las dependencias: `pip install pandas`
3. Ejecuta [nombre del notebook o script] para crear la base de datos.
4. [Cómo abrir los resultados en Power BI.]

## Estructura del repositorio

```
├── README.md
├── amazon.csv
├── [notebook o script].ipynb
├── AmazonDB.db
└── [archivo de Power BI o capturas]
```

## Próximos pasos

- [Ej. análisis de texto de las reseñas como proyecto aparte]