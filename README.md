# Estudio de Caso: Análisis del Conjunto de Datos de Vinos

El Objetivo de este estudio de caso es analizar un conjunto de datos que contiene los resultados de un análisis químico de vinos cultivados en la misma región de Italia pero derivados de tres cultivares (clases) diferentes. Utilizaremos diversas técnicas de análisis y preprocesamiento de datos para:
- Comprender la estructura y características del dataset.
- Identificar posibles problemas en los datos (valores faltantes, outliers).
- Preparar los datos para posibles modelos de Machine Learning (transformación, escalado).
- Explorar la separabilidad de las clases de vino mediante técnicas de reducción de dimensionalidad (PCA y t-SNE).

## 📊 Dataset: [`wine_data.csv`](https://www.kaggle.com/datasets/biyazejaan/wine-datacsv)

### 🎯 Variable Objetivo:
- **`class_label`**: Clase o cultivar del vino (`1`, `2`, `3`).


### 🍷 Características del Dataset:

| Columna                          | Descripción                                                   |
|----------------------------------|----------------------------------------------------------------|
| `class_label`                    | Clase o cultivar del vino (`1`, `2`, `3`)  |
| `alcohol`                        | Contenido de alcohol                                           |
| `malic_acid`                     | Ácido málico                                                   |
| `ash`                            | Ceniza                                                         |
| `alcalinity_of_ash`              | Alcalinidad de la ceniza                                       |
| `magnesium`                      | Magnesio                                                       |
| `total_phenols`                  | Fenoles totales                                                |
| `flavanoids`                     | Flavonoides                                                    |
| `nonflavanoid_phenols`           | Fenoles no flavonoides                                         |
| `proanthocyanins`                | Proantocianinas                                                |
| `color_intensity`                | Intensidad del color                                           |
| `hue`                            | Tono del vino                                                  |
| `OD280/OD315_of_diluted_wines`  | Medida de dilución (OD280/OD315)                               |
| `proline`                        | Prolina                                                        |

### ✅ Propósito Cumplido:

Hemos explorado y preparado exitosamente el dataset de vinos. Las visualizaciones de PCA y t-SNE demuestran que las características químicas medidas contienen información suficiente para distinguir entre los tres cultivares de vino. Los datos escalados y las representaciones de baja dimensionalidad (PCA/t-SNE) están ahora listos para ser utilizados en tareas posteriores, como la construcción de modelos de clasificación (e.g., K-NN, SVM, Random Forest) para predecir la clase de un vino basándose en sus propiedades químicas.
