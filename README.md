# 🧭 Curso: **Python Avanzado – 25 h**

> Modalidad: práctica 100 % en Jupyter Notebooks (GitHub Codespaces)
> Nivel: intermedio-avanzado
> Requisitos: conocimientos básicos de Python, estructuras y sintaxis general.

---

## 🧩 Módulo 1 – Expresiones Regulares (2 h)

### Objetivos

* Comprender la sintaxis básica y avanzada del módulo `re`.
* Buscar, validar y reemplazar patrones de texto.
* Aplicar regex a limpieza de datos y validaciones.

### Contenidos

1. Introducción al módulo `re`.
2. Metacaracteres básicos: `. ^ $ * + ? { } [ ] | ( )`.
3. Cuantificadores, grupos y alternativas.
4. Escapes especiales: `\d`, `\w`, `\s`, `\b`, etc.
5. Funciones principales: `search`, `match`, `findall`, `sub`, `split`.
6. Validación de formatos (email, matrícula, fecha).
7. Casos prácticos: limpieza de texto y extracción de números.

🧪 **Laboratorio**
Notebook `01_exp_regulares_lab.ipynb`: ejercicios guiados con texto real (teléfonos, correos, tokens de logs).

---

## 🧩 Módulo 2 – Colecciones Avanzadas (2 h)

### Objetivos

* Dominar listas, tuplas, conjuntos y diccionarios.
* Aplicar operaciones de comprensión y manipulación eficiente.

### Contenidos

1. Repaso de estructuras básicas.
2. Métodos útiles (`append`, `pop`, `update`, `items`, `setdefault`, etc.).
3. Comprensiones de listas, diccionarios y sets.
4. Copias, referencias y mutabilidad.
5. Uso combinado de colecciones (listas de dicts, dicts de listas).

🧪 **Laboratorio**
Notebook `02_estructuras_lab.ipynb`:
gestión de un inventario (listas → dict → set), búsquedas, filtrado y agregación simple.

---

## 🧩 Módulo 3 – Funciones y Parámetros Avanzados (2 h)

### Objetivos

* Crear funciones reutilizables y flexibles.
* Comprender parámetros variables, funciones anidadas y cierres (closures).

### Contenidos

1. Repaso de `def` y retorno múltiple.
2. Parámetros opcionales, `*args`, `**kwargs`.
3. Ámbito de variables, `global` y `nonlocal`.
4. Funciones anidadas, closures y decoradores básicos.
5. Documentación y tipado (`docstring`, `typing`).

🧪 **Laboratorio**
Notebook `03_funciones_lab.ipynb`:
crear un sistema de registro flexible de logs y validadores con decoradores.

---

## 🧩 Módulo 4 – Programación Orientada a Objetos (3 h)

### Objetivos

* Diseñar clases, métodos y constructores.
* Aplicar herencia, polimorfismo y abstracción.

### Contenidos

1. Clases, atributos y métodos de instancia.
2. Constructores (`__init__`) y destructores (`__del__`).
3. Herencia simple y múltiple.
4. Clases abstractas y métodos abstractos (`abc`).
5. Sobrescritura y `super()`.
6. Encapsulación y propiedades (`@property`).
7. Colecciones de objetos y métodos mágicos (`__str__`, `__len__`, `__iter__`).

🧪 **Laboratorio**
Notebook `04_poo_lab.ipynb`:
modelo de facturación con clases `Producto`, `Factura`, `Cliente`; cálculos automáticos de totales.

---

## 🧩 Módulo 5 – Programación Funcional (2 h)

### Objetivos

* Integrar el paradigma funcional en Python.
* Usar funciones de orden superior y expresiones lambda.

### Contenidos

1. Funciones anónimas (`lambda`).
2. Comprensiones y expresiones generadoras.
3. `zip`, `enumerate`, `any`, `all`.
4. `map`, `filter`, `reduce` (módulo `functools`).
5. Inmutabilidad y pureza de funciones.

🧪 **Laboratorio**
Notebook `05_funcional_lab.ipynb`:
transformar y filtrar listas de datos (ventas, puntuaciones) con funciones puras.

---

## 🧩 Módulo 6 – Entrada/Salida y Serialización (2 h)

### Objetivos

* Gestionar archivos y directorios.
* Serializar y deserializar datos en distintos formatos.

### Contenidos

1. Módulos `os`, `pathlib`, `shutil`.
2. Lectura/escritura secuencial de archivos de texto.
3. Serialización binaria (`pickle`).
4. JSON (`json.load`, `json.dump`).
5. XML (módulo `xml.etree.ElementTree`).
6. Gestión de errores y context managers (`with`).

🧪 **Laboratorio**
Notebook `06_io_lab.ipynb`:
programa que guarda y carga configuraciones de usuario en JSON y binario.

---

## 🧩 Módulo 7 – NumPy y Pandas (4 h)

### Objetivos

* Manipular datos estructurados y matriciales.
* Realizar análisis estadístico básico.

### Contenidos

#### NumPy

1. Creación de `ndarray`.
2. Tipos, formas y slicing.
3. Operaciones vectorizadas y broadcasting.
4. Funciones estadísticas (`mean`, `std`, `sum`, `argmax`).
5. Funciones avanzadas (`reshape`, `stack`, `concatenate`).

#### Pandas

1. `Series` y `DataFrame`.
2. Lectura de archivos (CSV, Excel, JSON).
3. Indexación y selección (`loc`, `iloc`).
4. Limpieza, filtrado y agregaciones.
5. Uniones y combinaciones (`merge`, `concat`, `join`).
6. Campos calculados y funciones de grupo.

🧪 **Laboratorio**
Notebook `07_pandas_lab.ipynb`:
análisis de un dataset de ventas; KPIs, agrupaciones, joins y filtrado dinámico.

---

## 🧩 Módulo 8 – Visualización de Datos (2 h)

### Objetivos

* Crear gráficos estáticos y dinámicos.
* Personalizar visualizaciones para análisis exploratorio.

### Contenidos

1. Matplotlib: gráficos de líneas, barras, pastel.
2. Seaborn: boxplot, histograma, heatmap.
3. Personalización de estilos, títulos y etiquetas.
4. Plotly: gráficos interactivos y dashboards simples.

🧪 **Laboratorio**
Notebook `08_visualizacion_lab.ipynb`:
representación de métricas de ventas y correlaciones con Seaborn y Plotly.

---

## 🧩 Módulo 9 – Bases de Datos Relacionales (2 h)

### Objetivos

* Conectar Python con una base de datos SQLite.
* Realizar operaciones CRUD desde código.

### Contenidos

1. Introducción a `sqlite3`.
2. Conexión y creación de tablas.
3. Inserción, actualización y borrado.
4. Consultas parametrizadas y lectura a DataFrame (`pandas.read_sql`).
5. Control de transacciones y errores.

🧪 **Laboratorio**
Notebook `09_bbdd_lab.ipynb`:
mini-sistema de tickets con persistencia en SQLite.

---

## 🧩 Módulo 10 – Procesamiento de Lenguaje Natural y Machine Learning (4 h)

### Objetivos

* Introducir técnicas básicas de NLP y ML.
* Comprender el flujo completo de un modelo: preprocesado, entrenamiento y evaluación.

### Contenidos

1. **NLTK**: tokenización, stopwords, stemming y conteo de frecuencias.
2. **Preprocesado ML**: normalización, codificación categórica, partición train/test.
3. **Scikit-learn supervisado**: regresión lineal, clasificación (`LogisticRegression`, `DecisionTree`).
4. **Scikit-learn no supervisado**: clustering (K-Means), reducción de dimensionalidad (PCA).
5. Evaluación: métricas, matriz de confusión, `cross_val_score`.

🧪 **Laboratorio**
Notebook `10_ml_lab.ipynb`:
análisis de sentimientos básico con NLTK y clasificación de textos con `scikit-learn`.

---

# 📂 Estructura final recomendada

```
notebooks/
│
├── 00_intro.ipynb
├── 01_exp_regulares_teoria.ipynb
├── 01_exp_regulares_lab.ipynb
├── 02_estructuras_teoria.ipynb
├── 02_estructuras_lab.ipynb
...
├── 10_ml_teoria.ipynb
├── 10_ml_lab.ipynb
└── utils_validacion.ipynb
```

Cada módulo = 1 notebook teórico + 1 de laboratorio.
Duración media por pareja: 2 h – 2 h 30 min.

