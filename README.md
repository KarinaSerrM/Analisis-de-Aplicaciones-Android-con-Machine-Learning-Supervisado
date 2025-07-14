# Análisis de Aplicaciones Android con Machine Learning Supervisado

Este repositorio documenta un análisis completo de datos extraídos de Google Play Store, donde se aplican técnicas de aprendizaje supervisado para descubrir patrones en calificaciones, precios, categorías y opiniones de los usuarios.

## Contenido del proyecto

### 1. Limpieza de datos
- Transformación de variables no numéricas (`Installs`, `Price`)
- Eliminación de duplicados
- Codificación y conversión de texto a formato analizable

### 2. Análisis estadístico y visualización
- Estadísticas descriptivas de variables numéricas y categóricas
- Frecuencias de categorías y géneros
- Histograma de calificaciones
- Gráficos de dispersión: tamaño vs calificación, precio vs calificación

### 3. Estrategias de monetización
- Comparación de aplicaciones gratuitas y de paga
- Análisis de precios extremos por categoría
- Relación entre tipo de app y comportamiento de mercado

### 4. Análisis de sentimientos
- Minería de reseñas de usuarios
- Evaluación de polaridad de sentimiento por tipo de aplicación
- Visualización con boxplots para identificar diferencias emocionales

## Herramientas utilizadas

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- ydata-profiling

## Conclusiones

- Las categorías FAMILY y GAME dominan el mercado de apps.
- Las aplicaciones con calificaciones altas suelen pertenecer a categorías como EDUCATION y EVENTS.
- Las apps gratuitas son más comunes, pero las de paga tienden a ofrecer experiencias más especializadas.
- El análisis de sentimiento muestra diferencias claras entre las percepciones de usuarios de apps gratuitas vs de pago.

## Recomendación

Este proyecto es ideal para desarrolladores, analistas de datos y emprendedores que deseen entender el comportamiento de las apps en Google Play y aplicar técnicas supervisadas para extraer insights valiosos.
