DBSCAN (Density-Based Spatial Clustering of Applications with Noise) es un algoritmo de *clustering* no supervisado que agrupa puntos de datos en función de su densidad espacial y es capaz de identificar puntos atípicos o de ruido. Este algoritmo es útil en escenarios donde no se conoce el número de clústeres y los datos tienen formas arbitrarias.

### Características principales:
1. **No supervisado**: DBSCAN no requiere etiquetas previas y no necesita especificar el número de clústeres de antemano.
2. **Basado en densidad**: Forma clústeres a partir de puntos densamente agrupados y puede identificar puntos aislados como ruido.
3. **Parámetros clave**:
   - **Epsilon (ε)**: Distancia máxima para considerar que dos puntos están en la misma vecindad.
   - **MinPts**: Número mínimo de puntos en la vecindad de un punto para considerarlo central y formar un clúster.

### Ventajas:
- **No requiere número predefinido de clústeres**.
- **Detecta clústeres de formas arbitrarias**.
- **Identifica y maneja ruido de manera efectiva**.

### Desventajas:
- **Sensibilidad a los parámetros**: La elección de `ε` y `MinPts` puede afectar el rendimiento.
- **Dificultades en alta dimensión**: Puede ser menos efectivo en espacios con muchas dimensiones debido a la definición de vecindades.

En resumen, DBSCAN es un algoritmo de *clustering* no supervisado que es ideal para datos con formas complejas y ruido, pero su efectividad depende de la correcta configuración de sus parámetros.
