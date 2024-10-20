# LAB2EDD2

# Proyecto de Análisis de Grafos de Vuelos

Este proyecto realiza análisis sobre un grafo que representa rutas de vuelos. Utiliza algoritmos de teoría de grafos para resolver problemas como caminos mínimos, conectividad y árboles de expansión mínima (MST), y permite visualizar el grafo en un mapa.

## Requisitos

1. **Descargar el dataset**: 
   - Descargue el archivo `flights_final.csv` desde este repositorio.

2. **Abrir en Google Colab**:
   - Vaya a [Google Colab](https://colab.research.google.com/).
   - Haga clic en el ícono de carpeta ubicado en la parte superior izquierda.

3. **Subir el dataset**:
   - Suba el archivo `flights_final.csv` a la carpeta en Colab.

4. **Configurar ruta del archivo**:
   - Copie la ruta del archivo subido y péguela en la variable `RUTA_ARCHIVO_CSV`, que se encuentra en el segundo bloque de código del notebook.

5. **Ejecutar el programa**:
   - Ejecute los bloques de código en orden:
     1. Primer bloque: carga de librerías y funciones.
     2. Segundo bloque: carga y preprocesamiento del dataset.
     3. Tercer bloque: ejecución de los algoritmos.
   - Al final, ingrese el número de su selección en el menú interactivo para utilizar las funcionalidades.

## Funcionalidades del Programa

1. **Mostrar información de vértices y caminos mínimos**:
   - Dado un vértice de inicio, muestra su información y los 10 vértices con los caminos mínimos más largos desde este.

2. **Camino mínimo entre dos vértices**:
   - Determina el camino más corto entre dos vértices dados por el usuario.

3. **Conectividad del grafo**:
   - Evalúa si el grafo es conexo, es decir, si existe un camino entre todos los pares de vértices.

4. **Árbol de Expansión Mínima (MST)**:
   - Determina el árbol de expansión mínima, que conecta todos los vértices del grafo con el costo mínimo.

5. **Mapa del grafo**:
   - Crea y muestra un mapa visual del grafo, donde se representan los vértices y las rutas de vuelo.

## Ejecución en Local

Si desea ejecutar el programa localmente en lugar de Colab, asegúrese de tener instaladas las dependencias necesarias, como `networkx`, `matplotlib` y otras, utilizando:

```bash
pip install -r requirements.txt
```
