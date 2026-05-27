# 📊 Proyecto de Análisis de Datos — ConnectaTel

## 📌 Descripción del proyecto

Este proyecto consiste en un análisis exploratorio y estadístico de datos para la empresa ficticia de telecomunicaciones **ConnectaTel**, enfocada en clientes de Latinoamérica.

El objetivo principal es analizar el comportamiento de los usuarios a partir de diferentes fuentes de datos para:

* Identificar patrones de consumo.
* Detectar valores atípicos y problemas de calidad de datos.
* Analizar el uso de servicios como llamadas y mensajes.
* Construir perfiles de clientes.
* Generar información útil para estrategias de retención y mejora de planes.

El análisis se desarrolla utilizando Python en un notebook de Jupyter/Google Colab, aplicando técnicas de limpieza, exploración y análisis de datos.

---

# 🎯 Objetivo del proyecto

Como analista de datos, el propósito del proyecto es evaluar el comportamiento de los clientes de ConnectaTel mediante el análisis de información histórica registrada hasta 2024.

A partir de los datasets disponibles, se busca:

* Explorar y comprender la estructura de los datos.
* Detectar inconsistencias y valores faltantes.
* Realizar limpieza y transformación de datos.
* Generar métricas de uso por usuario.
* Identificar comportamientos de consumo.
* Obtener insights que apoyen la toma de decisiones de negocio.

---

# 🗂️ Datasets utilizados

El proyecto utiliza tres datasets principales:

## 1. `plans.csv`

Contiene información sobre los planes de telefonía disponibles.

### Variables principales:

* Precio del plan
* Minutos incluidos
* GB incluidos
* Costos adicionales

---

## 2. `users.csv`

Contiene información demográfica y administrativa de los clientes.

### Variables principales:

* Edad
* Ciudad
* Fecha de registro
* Plan contratado
* Estado de churn

---

## 3. `usage.csv`

Incluye el detalle del uso real de servicios por parte de los usuarios.

### Variables principales:

* Tipo de actividad
* Duración de llamadas
* Cantidad de mensajes
* Consumo histórico

---

# ⚙️ Tecnologías y librerías utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

# 🔍 Etapas del análisis realizadas

## 1. Carga y exploración de datos

* Importación de librerías.
* Carga de datasets.
* Revisión inicial con `.head()`, `.shape()` e `.info()`.

---

## 2. Identificación de problemas de calidad de datos

* Detección de valores nulos.
* Revisión de proporciones de datos faltantes.
* Identificación de valores inválidos y sentinels.
* Exploración de columnas numéricas y categóricas.
* Revisión y validación de fechas.

---

## 3. Limpieza y transformación de datos

* Reemplazo de sentinels.
* Conversión de formatos de fecha.
* Corrección de valores fuera de rango.
* Tratamiento de valores nulos.

---

## 4. Generación de métricas y análisis de comportamiento

* Agrupación de datos por usuario.
* Cálculo de:

  * Cantidad de mensajes.
  * Cantidad de llamadas.
  * Total de minutos consumidos.
* Integración de métricas con información de usuarios.

---

## 5. Análisis exploratorio de datos

* Distribuciones de variables.
* Identificación de patrones de consumo.
* Detección de posibles outliers.
* Comparaciones entre segmentos de usuarios.

---

# ▶️ Cómo ejecutar el notebook

## Opción 1: Google Colab

1. Descarga el archivo `.ipynb`.
2. Abre Google Colab.
3. Selecciona:

   * `Archivo` → `Subir notebook`
4. Carga el notebook del proyecto.
5. Sube los datasets necesarios (`plans.csv`, `users.csv`, `usage.csv`).
6. Ejecuta las celdas en orden.

---

## Opción 2: Jupyter Notebook local

### Requisitos:

Instalar Python 3 y las librerías necesarias.

### Instalar dependencias:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Ejecutar:

```bash
jupyter notebook
```

Después, abrir el archivo `.ipynb` y ejecutar las celdas.

---

# 🔁 Guía breve de reproducción

1. Clonar o descargar el repositorio.
2. Colocar los datasets en la carpeta correspondiente.
3. Abrir el notebook en Google Colab o Jupyter.
4. Ejecutar las celdas de forma secuencial.
5. Revisar los resultados del análisis y visualizaciones.

---

# 📈 Resultados esperados

Al finalizar el proyecto se obtiene:

* Un dataset limpio y preparado para análisis.
* Métricas de comportamiento por usuario.
* Identificación de patrones de uso.
* Insights útiles para estrategias de negocio y retención de clientes.

---

# 👩‍💻 Autor

Proyecto realizado por **María Fernanda Soní** como práctica de análisis de datos y limpieza de información utilizando Python.
