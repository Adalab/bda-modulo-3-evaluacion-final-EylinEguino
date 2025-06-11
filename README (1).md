# ✈️ Customer Loyalty & Flight Activity Analysis

Este repositorio contiene un análisis exploratorio de datos (EDA), limpieza y visualización, basado en dos datasets proporcionados por una aerolínea ficticia: uno sobre la actividad de vuelo de sus clientes "Customer Flight Activity.csv" y otro sobre su historial de fidelización " Customer Loyalty History.csv".

## 📁 Estructura del repositorio

FASE 1.-
├──Carga de data sets:
├──Analisis_exploratorio
├──Unión de Dataframes
├──limpieza de datos
FASE 2.-
├── Visualización
BONUS
```

## 📊 Datasets

### `Customer Flight Activity.csv`
Contiene detalles sobre vuelos realizados por los clientes:
- `Customer ID`
- `Flight Date`
- `Flight Number`
- `Origin`, `Destination`
- `Fare Class`
- `Miles Flown`
- `Segment Revenue`
- Otros campos relacionados con los vuelos

### `Customer Loyalty History.csv`
Contiene información sobre la participación de los clientes en el programa de fidelización:
- `Customer ID`
- `Enrollment Date`
- `Tier Level`
- `Points Earned`
- `Redemption Activity`
- `Status Change Dates`, etc.

---

## 🔍 Análisis exploratorio
incluye:

- Vista general del dataset (`head`, `tail`, `sample`)
- Número de filas y columnas
- Tipos de datos y columnas categóricas
- Valores únicos, nulos y duplicados
- Columnas constantes
- Estadísticas descriptivas numéricas y categóricas
- Unificación de datasets por `Customer ID`
- Análisis por niveles de fidelidad (`Tier Level`)
- Insights de comportamiento

---

## 📊 Visualizaciones
Incluye;
1. ¿Cómo se distribuye la cantidad de vuelos reservados por mes durante el año?

2. ¿Existe una relación entre la distancia de los vuelos y los puntos acumulados por los cliente?
3. ¿Cuál es la distribución de los clientes por provincia o estado?
4. ¿Cómo se compara el salario promedio entre los diferentes niveles educativos de los clientes?
5. ¿Cuál es la proporción de clientes con diferentes tipos de tarjetas de fidelidad?
6. ¿Cómo se distribuyen los clientes según su estado civil y género?


---

## 🛠️ Herramientas utilizadas

- Python 3.8+
- Jupyter Notebook
- Librerías:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`


## 🚀 Cómo ejecutar

1. Clona este repositorio:

```bash
git clone https://github.com/tu-usuario/customer-loyalty-analysis.git
cd customer-loyalty-analysis
```

2. Coloca los archivos `.csv` en la raíz del proyecto.
3. Abre el notebook en Jupyter o VSCode y ejecuta las celdas paso a paso.

---

## 📌 Notas adicionales

- El código incluye funciones reutilizables para hacer EDA de forma automática (`eda_basico()`).
- Puedes adaptar estas funciones a cualquier dataset tabular.
