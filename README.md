# Predicciones Mundial

Proyecto en notebook para entrenar un modelo de predicción de resultados de partidos usando ratings ELO, variables del torneo y XGBoost.

## Estructura

- `MundialPredidcciones.ipynb`: notebook principal con carga de datos, limpieza, entrenamiento y predicción.
- `data/results.csv`: historial de partidos.
- `data/elo_ratings_wc2026.csv`: ratings ELO por año y selección.
- `.env/`: entorno virtual local con las dependencias instaladas.

## Requisitos

Instala las dependencias del proyecto con:

```bash
pip install -r requirements.txt
```

Dependencias principales:

- pandas
- numpy
- scikit-learn
- xgboost
- seaborn
- matplotlib

## Uso

1. Abre `MundialPredidcciones.ipynb` en VS Code o Jupyter.
2. Selecciona el kernel de Python del entorno local.
3. Ejecuta las celdas en orden.

## Notas

- El notebook espera que la carpeta `data/` esté al mismo nivel que el archivo `.ipynb`.
- Si cambias la ubicación del notebook, revisa las rutas que construyen `results.csv` y `elo_ratings_wc2026.csv`.
- La carpeta `.env/` contiene el entorno virtual del proyecto y no debería versionarse.
