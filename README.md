# Semana-13-Ejercicios-de-estructuras-de-rboles-en-Python

# Estructuras de Árboles con Treelib 

Este repositorio contiene la implementación práctica y documentación de estructuras de datos no lineales, específicamente **Árboles Generales**, utilizando la biblioteca `treelib` en Python.

##  Contenido de la Actividad

El proyecto se compone de 5 ejercicios prácticos diseñados para comprender el ciclo de vida de una estructura jerárquica:

1. **Diseño de un Catálogo Comercial (Ejercicio 1):** Creación de un árbol con estructura jerárquica multinivel (Raíz, Categorías y Productos).
2. **Consultas de Relaciones (Ejercicio 2):** Identificación de nodos padre, nodos hijo, nodos hoja y tamaño total del árbol.
3. **Mutaciones Estructurales (Ejercicio 3):** Modificación segura de etiquetas, reubicación de ramas (`move_node`) y eliminación de nodos (`remove_node`) preservando la inmutabilidad de la estructura original mediante copias profundas (`deep=True`).
4. **Algoritmos de Recorrido (Ejercicio 4):** Comparación empírica y conceptual entre recorridos en Profundidad (DFS - Depth-First Search) y en Anchura (BFS - Breadth-First Search).
5. **Caso Aplicado (Ejercicio 5):** Desarrollo de un sistema de migas de pan (Breadcrumbs) para un portal universitario, mapeando la ruta de navegación desde cualquier hoja hasta la raíz.

##  Requisitos de Instalación

Para ejecutar el notebook de esta actividad, es necesario instalar la librería `treelib`:

```bash
pip install treelib
```

##  Conclusiones Técnicas

* **Identificadores vs Etiquetas:** La separación entre identificadores únicos (`identifier`) y etiquetas descriptivas (`tag`) previene colisiones lógicas y simplifica las consultas estructurales en $O(1)$.
* **Recorridos Estructurales:** BFS prioriza la exploración por niveles jerárquicos de forma óptima, mientras que DFS profundiza de forma completa por ramas individuales.
* **Ascenso Jerárquico:** El proceso de búsqueda hacia la raíz tiene una complejidad temporal de $O(h)$ donde $h$ es la altura del árbol, garantizando alta eficiencia para sistemas de navegación.


