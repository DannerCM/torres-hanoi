# Torres de Hanói

Laboratorio de Inteligencia Artificial. Un solo notebook, sin módulos aparte.

## Contenido

| Sección | Qué hay |
|---------|---------|
| 1 | Reglas, cómo se guarda un estado y de dónde sale el mínimo de `2^n - 1` movimientos |
| 2 | Predicados, axiomas y la acción `mover` con su precondición y sus efectos |
| 3 | BFS, DFS y A* con dos heurísticas, más la solución recursiva de referencia |
| 4 | Comparación con n de 3 a 10: nodos expandidos, frontera y largo de la solución |
| 5 | Dibujos: el tablero paso a paso y el grafo de Sierpiński con los estados |
| 6-7 | Conclusiones y referencias |

Las afirmaciones se comprueban en el propio notebook. Los axiomas y la equivalencia entre la
precondición lógica y el código se verifican sobre los `3^n` estados hasta n = 5. La heurística
exacta se contrasta contra las distancias reales calculadas con BFS inverso.

## Ejecución

El notebook ya viene ejecutado, con sus salidas y sus tres figuras guardadas. Para correrlo de nuevo:

```bash
pip install -r requirements.txt
jupyter notebook torres-hanoi.ipynb
```

Ejecutar las celdas en orden. Tarda menos de un minuto. También corre en Google Colab sin cambios.

## Requisitos

Python 3.10 o más, `matplotlib` y `pandas`. El resto es biblioteca estándar.
