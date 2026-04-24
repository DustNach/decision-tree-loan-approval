# Decision Tree - Loan Approval Classifier

Modelo de clasificación binaria usando DecisionTreeClassifier de Scikit-learn para predecir aprobación de préstamos.

## 🎯 Objetivo
Predecir si un préstamo será aprobado o rechazado basándose en el ingreso mensual del solicitante y el monto solicitado.

## 📊 Dataset
- **Registros**: 10 solicitudes de préstamo
- **Features**: 
  - Ingreso mensual (monthly_income)
  - Monto del préstamo (loan_amount)
- **Target**: approved (0 = Rechazado, 1 = Aprobado)

## 🛠️ Tecnologías
- Python
- Scikit-learn
- Pandas
- Jupyter Notebook

## 📈 Proceso
1. **Preparación de datos**
   - Dataset sintético de 10 registros
   - Features: ingreso y monto del préstamo
   - División train/test 80/20

2. **Modelado**
   - DecisionTreeClassifier
   - Sin limitación de profundidad
   - Random state: 42

3. **Evaluación**
   - Accuracy en train: 100%
   - Accuracy en test: 100%

## 🚀 Uso
```bash
jupyter notebook decision_tree/dtree.ipynb
```

## 📊 Resultados
- **Precisión Train**: 100%
- **Precisión Test**: 100%
- **Modelo**: DecisionTreeClassifier

## 📝 Estructura
```
decision-tree/
├── decision_tree/
│   ├── dtree.ipynb    # Jupyter notebook principal
│   └── env/           # Entorno virtual (no incluido en repo)
├── .gitignore
└── README.md
```

## 💡 Notas
- Modelo simple ideal para demostración de árboles de decisión
- Perfecto para entender clasificación binaria
- Dataset pequeño para fines educativos
