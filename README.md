# MLlib-Simulador

```
/*******************************************
-Nombre: Salomon Avila
-Materia: HPC (Computacion de Alto Rendimiento)
-Maestria en Inteligencia Artificial
-Pontificia Universidad Javeriana
-Taller 02
-Temas: Arbol de decision, implementacion
        de arboles de decision de Spark MLlib, simulacion
*******************************************/
```

Simulador estático (un solo `index.html`) de **árboles de decisión de Spark MLlib**
([guía oficial](https://spark.apache.org/docs/latest/mllib-decision-tree.html)),
hecho con **Three.js** y estilos **glassmorphism + neumorfismo**.

Abrir `index.html` en el navegador (necesita internet para cargar Three.js y las fuentes desde CDN).

## Secciones
1. **Autor y membrete**: datos del autor y del taller (el membrete también va como comentario en la primera línea del HTML).
2. **Objetivos y contexto**: objetivo general y específicos, contexto de HPC y Spark, cómo usar el simulador, alcance y limitaciones.
3. **Didáctica y conceptual**:
   - *Conceptual*: algoritmo, impureza (Gini, entropía, varianza), ganancia de información, candidatos de split, regla de parada, consejos de uso, caché y checkpointing, escalamiento y ejemplos en PySpark (alineado con la guía oficial de Spark 4.3.0).
   - *Didáctica*: calculadora de impureza, ganancia de información paso a paso, splits categóricos, pseudocódigo y autoevaluación.
4. **Simulador frente a carga**:
   - *Simulador 3D*: entrena un árbol (réplica del algoritmo de MLlib con bins) sobre datasets 2D, con parámetros ajustables, `toDebugString`, crecimiento animado, inspección de nodos y predicción con un clic.
   - *Carga del clúster*: modelo de costos didáctico (instancias, features, maxBins, maxDepth, ejecutores, maxMemoryInMB, useNodeIdCache…) con ejecución animada del clúster y gráficas de escalamiento.
