## Модели и метрики

Дата обучения: 2026-09-29
Данные: 891 строка, 80/20 train/test, stratify по Survived

| Модель | Accuracy | Precision | Recall | F1 | ROC-AUC |
|--------|----------|-----------|--------|-----|---------|
| Logistic Regression | 0.8044 | 0.7833 | 0.6811| 0.7286 | 0.8486 |
| Decision Tree | 0.7821| 0.7419| 0.6666| 0.7022 | 0.8132 |

Артефакты: `models/lr_model.pkl`, `models/dt_model.pkl`, `models/scaler.pkl`,
`models/feature_cols.json`, `models/metrics.json`.