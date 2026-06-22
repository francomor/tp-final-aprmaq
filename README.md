# TP Final - Aprendizaje de Máquinas

Trabajo final de la materia **Aprendizaje de Máquinas** de la Carrera de Especialización en Inteligencia Artificial (CEIA - FIUBA).

## Descripción

Clasificación de objetos astronómicos (estrellas, galaxias y cuásares) a partir del dataset `star_classification.csv`, basado en observaciones del Sloan Digital Sky Survey (SDSS). Incluye análisis exploratorio de datos (EDA) y entrenamiento de múltiples modelos de machine learning.

## Estructura

| Archivo | Descripción |
|---------|-------------|
| `eda-star_classification.ipynb` | Análisis exploratorio de datos |
| `marcos.ipynb` | Notebook de modelos |
| `tp_final.ipynb` | Notebook principal del trabajo final |
| `star_classification.csv` | Dataset |
| `images/` | Imágenes y gráficos |

## Requisitos

- Python `>=3.11,<3.13`
- [uv](https://github.com/astral-sh/uv) para gestión de dependencias

## Instalación

```bash
uv sync
```

## Uso

```bash
uv run jupyter notebook
```

Abrir `tp_final.ipynb` para ver el trabajo completo.
