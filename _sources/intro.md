# LendingClub — Modelo de Clasificación Supervisada

En el presente JBook documenta la construcción de un modelo de clasificación supervisada para predecir si un préstamo emitido por la plataforma Lending Club resultará en default (1) o será pagado completamente (0).

**Objetivo:** Comparar el desempeño de los modelos construidos con **scikit-learn** y **PySpark**, además de aplicar **LIME** para interpretar predicciones.

| Sección | Contenido |
|---------|-----------|
| 1 | Análisis exploratorio (EDA) |
| 2 | Preprocesamiento (sklearn y PySpark) |
| 3 | Modelado + GridSearchCV / CrossValidator |
| 4 | Evaluación: AUC, F1, matriz de confusión |
| 5 | Interpretabilidad con LIME |
| 6 | Reflexión crítica comparativa |

**Dataset:** [Lending Club Loan Data](https://www.kaggle.com/datasets/wordsforthewise/lending-club)