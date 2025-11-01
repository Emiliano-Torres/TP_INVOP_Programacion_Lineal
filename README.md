### 🧮 Licitación de Escuelas — TP de Investigación Operativa y Optimización (UBA)

Este proyecto corresponde a un **trabajo práctico universitario** de la materia **Investigación Operativa y Optimización** (UBA).  
El objetivo es modelar y resolver un **problema de licitación** mediante **programación lineal y entera**, aplicando herramientas de optimización y análisis de soluciones óptimas.

#### 📘 Descripción general
El trabajo consiste en simular una licitación para **709 escuelas**, geolocalizadas dentro de un área rectangular, que reciben **ofertas de un conjunto de empresas ficticias** (A, B, C, ...).  
Se generan **tres instancias independientes** del problema, se resuelve el **modelo básico de licitación** para cada una, y se analiza la existencia de **óptimos alternativos**.

Además, se implementa un **algoritmo greedy de asignación** sobre las **unidades de competencia (UC)** en las que se detecta más de una empresa ganadora.

#### ⚙️ Componentes principales
- Generación reproducible de datos (escuelas y ofertas)
- Modelos de licitación y detección de óptimos alternativos  
- Identificación de unidades de competencia (UC)  
- Algoritmo greedy de asignación dentro de UC  
- Visualización de resultados y análisis de soluciones  

#### 🧰 Tecnologías utilizadas
- **Python 3**
- **NumPy**, **Pandas**, **Matplotlib**
- **PySCIPOpt** (solver principal para programación lineal y entera)
- *(Opcional)* **OR-Tools** o **PuLP** para comparación

#### 🎯 Objetivo académico
El trabajo busca aplicar los conceptos de **modelización, optimización y análisis de soluciones múltiples**, combinando herramientas de **programación lineal entera mixta (MILP)** y **heurísticas de asignación**.
