# default-client-pred
Модель для прогнозирования дефолтов по кредитам

## 📌 Задачи
- Построение модели с ROC-AUC > 0.7
- Анализ важности признаков
- Оптимизация F1-score для дисбалансированных классов

## 🛠 Технологии
- Python 3.8+
- Pandas/NumPy для анализа
- Seaborn/matplotlib для визуализации
- Logistic regression, XGBoost, Random Forest

## 📊 Результаты
| Модель              | Accuracy | F1-score | ROC-AUC |
|---------------------|----------|----------|---------|
| Logistic Regression | 0.78     | 0.51     | 0.67    |
| XGBoost             | 0.75     | 0.43     | 0.77    |
| Random Forest       | 0.74     | 0.45     | 0.63    |
