

<img width="936" height="523" alt="image" src="https://github.com/user-attachments/assets/1ce34d03-da97-430b-b2db-71404e7e10cc" />

#  **Proyecto de Análisis de Datos – Metodologia ASUM-DM**
## 👥 **Integrantes**

* **Sarah Katalina González 🐈‍⬛  [Kata45]()**
* **Cristián 🎮 [cristian]()**
* **Daniel Muñoz 🦊 [josedanieru15]()**

---

# 🎯 **Objetivo del Proyecto**

El proyecto busca analizar la distribución geográfica y administrativa de los Centros de Formación del SENA en Colombia, identificando patrones, concentración, cobertura, anomalías y oportunidades de mejora.
---

#  **Propósitos**

- Realizar un EDA (Análisis Exploratorio de Datos) sobre la georreferenciación de los centros del SENA, evaluando calidad, distribución y características del dataset.

- Realizar procesos de limpieza y transformación para obtener un dataset depurado y apto para modelado.

- Aplicar técnicas de clustering (K-Means y DBSCAN) para segmentar los centros de formación según su localización geográfica.

- Interpretar los segmentos generados, identificando patrones y diferencias entre regiones.

---

#  **Función del Proyecto**

El proyecto cumple tres funciones principales:

1. **Académica:** aplicar ASUM-DM paso a paso de forma estructurada.
2. **Analítica:** explorar, transformar y modelar datos para obtener resultados confiables.
3. **Comunicativa:** presentar hallazgos mediante un informe técnico, un notebook, gráficas y una presentación tipo *elevator pitch*.

---

# 🗂️ **Descripción del Dataset**

El dataset seleccionado contiene información relevante sobre la ubicacion de los diferentes centros del sena en el pais

* Revisión de calidad de datos
* Identificación de anomalías
* Limpieza e imputación
* Construcción del dataset final listo para modelamiento

---

# 📌 **Fases ASUM-DM y Roles**

## **🔹 Fase 1 – Comprensión del Negocio (Business Understanding)**

### **Responsables:** Sarah, Cristián y Daniel

Esta fase se desarrolla en conjunto. Incluye la definición del problema, objetivos, alcance del análisis y criterios de éxito.

---

## **🔹 Fases 2 y 3 – Comprensión de Datos + Preparación de Datos (EDA + Cleaning)**

### **Responsable Principal:** Cristian

### **Apoyo:** Daniel y Sarah

Incluye:

* Carga y revisión del dataset
* Análisis exploratorio (EDA)
* Detección de valores faltantes, outliers y anomalías
* Limpieza, imputación, transformación y codificación
* Creación del dataset limpio para el modelado

---

## **🔹 Fases 4 y 5 – Modelado + Optimización del Modelo**

### **Responsable Principal:** daniel

### **Apoyo:** Sarah y cristian

Comprende:

* Selección del modelo (analítica o IA)
* Entrenamiento inicial y obtención de métricas
* Identificación de errores y oportunidades de mejora
* Optimización mediante ajustes de parámetros, ingeniería de características, normalización, etc.
* Comparación entre la primera y segunda iteración

---

## **🔹 Fase 6 – Comunicación de Resultados**

### **Responsable Principal:** Sarah

### **Apoyo:** Cristián y Daniel

Incluye:

* Diseño del informe PDF
* Presentación estilo *elevator pitch*
* Creación del dashboard (si se desarrolla el beneficio adicional)
* Preparación visual de métricas, gráficas y conclusiones

---

# 📁 **Estructura del Repositorio**

```
📦 Proyecto-ASUM-DM
│
├── 📁 Data
│   ├── dataset_original.csv
│   └── dataset_limpio.csv
│   📄 *Contiene el dataset original y la versión limpia usada para modelar.*
│
├── 📁 Documentos
│   └── bitacora.pdf
│   📄 *Incluye la bitácora del proyecto, avances, decisiones y registro del proceso.*
│
├── 📁 src
│   └── modelo.py / o carpeta con scripts
│   📄 *Contiene el código del modelo de analítica/IA y sus iteraciones.*
│
├── 📁 notebook
│   └── EDA.ipynb
│   📄 *Incluye el análisis exploratorio de datos, visualizaciones y conclusiones.*
│
└── README.md  ← este archivo
```

---

# 📌 **Conclusiones Esperadas del Proyecto**

El proyecto debe entregar:

* Un informe técnico en PDF con todas las fases ASUM-DM
* Un notebook claro, limpio y replicable
* Un modelo con iteraciones y optimización documentada
* Una presentación corta tipo *elevator pitch*
* (Opcional) Un dashboard profesional integrado

---

#  **Uso del Proyecto**

1. Clonar el repositorio
2. Revisar el notebook dentro de `/notebook`
3. Ver el dataset en `/Data`
4. Ejecutar el modelo desde `/src`
5. Leer los documentos y reporte final en `/Documentos`
