# Laboratorio 7: Pipeline ETL, Limpieza Condicionada y Data Lake

Fundamentos de Big Data (IDSD413) - Escuela Politécnica Nacional

Notebook de Google Colab que interviene un pipeline ETL con:

- **Reto 1:** capa de cuarentena (`./datalake/quarantine`, Parquet) para outliers detectados por IQR.
- **Reto 2:** descarte inteligente (`Cancelado` + `monto` nulo se elimina; el resto se imputa con la mediana por categoría).

Data Lake simulado: `raw` (evidencia inmutable), `curated` (dato limpio) y `quarantine` (outliers aislados).
