# Estructuras de Datos - Curso Universitario

## Indices

1. [Descripción](#descripción)
2. [Objetivos de Formación](#objetivos-de-formación)
3. [Contenidos Temáticos](#contenidos-temáticos)
4. [Estrategias Pedagógicas](#estrategias-pedagógicas)
5. [Evaluación](#evaluación)
6. [Recursos Bibliográficos](#recursos-bibliográficos)
7. [Horario y Carga Horaria](#horario-y-carga-horaria)
8. [Contenidos](#contenidos)
9. [Ejemplo de Aplicación en la Vida Real](#ejemplo-de-aplicación-en-la-vida-real)
10. [Proyecto](#proyecto)
## Descripción

En el desarrollo de software, es común tratar con grandes cantidades de información que requieren una representación lógica, ordenada y manejable. Las **Estructuras de Datos** son fundamentales para el funcionamiento eficiente de los sistemas de cómputo y almacenamiento en la vida real. Este curso se enfoca en el estudio de las estructuras contenedoras de datos básicas y los algoritmos relacionados con ellas, con un enfoque en proyectos de desarrollo de software de mediana complejidad que aborden problemas reales.

## Objetivos de Formación

1. Presentar los principios de la complejidad algorítmica como un criterio de calidad para los algoritmos.
2. Proporcionar al estudiante herramientas para diseñar **Tipos Abstractos de Datos** (TADs), especialmente en el diseño de estructuras contenedoras.
3. Mostrar estrategias para implementar estructuras de datos y los algoritmos asociados en un lenguaje de programación (se utiliza C++).
4. Exponer al estudiante a entornos de desarrollo de software donde se aborden las etapas de concepción, diseño, implementación y pruebas.

## Contenidos Temáticos

El curso abarca los siguientes temas:

1. Bases de complejidad algorítmica.
2. Estructuras lineales.
3. Estructuras recurrentes.
4. Estructuras no lineales.

## Estrategias Pedagógicas

El curso emplea diversas estrategias para facilitar el aprendizaje:

1. **Clases Magistrales:** Sesiones teóricas dirigidas por el profesor para introducir los conceptos fundamentales.
2. **Talleres Individuales:** Se presentan problemas sencillos para que los estudiantes pongan en práctica los conceptos aprendidos.
3. **Aprendizaje por Proyectos:** Los estudiantes desarrollan un proyecto que resuelve un problema acotado en el ámbito de estructuras de datos y algoritmos.
4. **Aprendizaje Colaborativo:** Se fomenta el trabajo en grupos para que los estudiantes compartan conocimientos y refuercen el aprendizaje de manera significativa.

## Evaluación

La evaluación del curso se compone de varias partes:

1. Tres parciales que evalúan los conocimientos sobre estructuras lineales, jerárquicas y no lineales.
2. Cinco talleres individuales que refuerzan conceptos específicos.
3. Un proyecto de desarrollo a lo largo del semestre que demuestra la aplicación práctica de las estructuras de datos y algoritmos aprendidos.

## Recursos Bibliográficos

Se utilizarán diversos recursos bibliográficos para apoyar el aprendizaje, entre ellos:

1. "TADs, Estructuras de datos y resolución de problemas con C++" de L.R. Nyhoff.
2. "Data Structures and Algorithm analysis in C++" de M.A. Weiss.
3. "Algoritmos y Estructuras de Datos: Una perspectiva en C" de L. Joyanes Aguilar e I. Zahonero Martínez.
4. "Diseño y manejo de estructuras de datos en C" de J.A. Villalobos.
5. "Fundamentos de Algoritmia" de G. Brassard y P. Bratley.
6. "Data structures with C++ using STL" de W. Ford.
7. "Data Structure programming with the standard template library in C++" de J. Bergin.
8. "Modelado y diseño orientado a objetos, metodología OMT" de J. Rumbaugh.
9. "C++ Templates the Complete guide" de D. Vandevoorde.
10. "Problem solving, Abstraction, and design using C++" de F.L. Frienman.

## Horario y Carga Horaria

El curso consta de 4 horas presenciales por semana, distribuidas en general en 2 horas de teoría y 2 horas de práctica (talleres). Se recomienda dedicar al menos 5 horas de trabajo autónomo adicional para el estudio y resolución de ejercicios.

## Contenidos

Los contenidos vistos en el curso de Estructuras de Datos incluyen los siguientes temas:

1. **Bases de complejidad algorítmica:**
   - Notación O-grande.
   - Aritmética de cotas.
   - Análisis de complejidad por inspección.
   - Complejidad básica de "dividir-y-vencer" y fuerza bruta.

2. **Estructuras lineales:**
   - Secuencias.
   - Vectores.
   - Cola de doble cabeza (deque).
   - Listas encadenadas.
   - Pilas.
   - Colas.

3. **Estructuras recurrentes:**
   - Motivación.
   - Árboles binarios de búsqueda.
     - Árboles binarios balanceados de búsqueda.
     - Conjuntos y mapas.
   - Montículos.
   - Representación de jerarquías.
     - Árboles de decisión.
     - Árboles de sintaxis.
     - Árboles de codificación.
   - Árboles de partición del espacio.
     - Quadtrees.
     - Octrees.
     - KD-trees.

4. **Estructuras no lineales:**
   - Motivación.
   - Tablas de dispersión (hash tables).
   - Grafos.
     - Implementación de un grafo por matrices de adyacencia.
     - Recorridos básicos:
       - Plano.
       - Pre-orden.
       - Niveles.
     - Algoritmos en grafos:
       - Grafos bipartitos.
       - Algoritmos de circuitos:
         - Euler.
         - Hamilton.
       - Algoritmos de caminos más baratos:
         - Floyd-Warshall.
         - Prim.
         - Kruskal.
         - Dijkstra.

Cada uno de estos temas aborda diferentes estructuras de datos, sus características, implementaciones y algoritmos asociados. Los conceptos vistos permiten a los estudiantes comprender cómo seleccionar y utilizar las estructuras de datos adecuadas para resolver problemas específicos en el desarrollo de software.

## Ejemplo de Aplicación en la Vida Real

Un ejemplo práctico de cómo las estructuras de datos son vitales en la vida real es el manejo de información en una red social. Cuando un usuario publica un mensaje, se almacena en una estructura de datos lineal, como un "vector" o "lista", para mantener el orden de las publicaciones. Estos mensajes también pueden organizarse en una estructura jerárquica, como un "árbol", para mostrar comentarios relacionados con las publicaciones originales.

Además, para sugerir amistades, la red social puede utilizar una estructura de datos no lineal, como una "tabla de dispersión" o "hash table", para indexar rápidamente los perfiles de usuario y encontrar conexiones potenciales. Los algoritmos asociados, como el algoritmo de búsqueda de caminos más cortos (por ejemplo, Dijkstra), pueden usarse para calcular la ruta más rápida entre dos usuarios y así sugerir amistades que tengan intereses comunes o amigos en común.

## Proyecto
El proyecto se encuentra actualmente disponible Aqui [Descargar PDF](ruta/al/archivo.pdf)

