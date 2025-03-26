# Ej2_knn.py
from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score

# Datos: Etiquetas reales (y_true) y predicciones del modelo (y_pred)
y_true = [1] * 40 + [0] * 30 + [1] * 10 + [0] * 20  # Etiquetas reales
y_pred = [1] * 40 + [0] * 30 + [0] * 10 + [1] * 20  # Predicciones realizadas por el modelo

# Calcular métricas usando funciones de scikit-learn
accuracy = accuracy_score(y_true, y_pred)
precision = precision_score(y_true, y_pred)
recall = recall_score(y_true, y_pred)
f1 = f1_score(y_true, y_pred)

# Mostrar los resultados
print("Resultados de las métricas:")
print(f"Accuracy: {accuracy:.2f}")
print(f"Precision: {precision:.2f}")
print(f"Recall: {recall:.2f}")
print(f"F1-Measure: {f1:.2f}")


git checkout -b main
git branch

git checkout -b secondary-branch
git branch
