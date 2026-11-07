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
1. **Conceptual**: algoritmo, impureza (Gini, entropía, varianza), ganancia de información, candidatos de split, reglas de parada, parámetros, escalamiento, el árbol como TAD y ejemplos en PySpark.
2. **Didáctica**: calculadora de impureza, ganancia de información paso a paso, splits categóricos, pseudocódigo por niveles y autoevaluación.
3. **Simulador 3D**: entrena un árbol (réplica del algoritmo de MLlib por bins y por niveles) sobre datasets 2D, con parámetros ajustables, `toDebugString`, crecimiento animado, inspección de nodos y predicción con un clic.
4. **Simulación de carga**: modelo de costos didáctico (instancias, features, maxBins, maxDepth, ejecutores, maxMemoryInMB, useNodeIdCache…) con ejecución animada del clúster y gráficas de escalamiento.
