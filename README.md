## 🎯 Objetivo
Este proyecto corresponde al segundo desafío de Data Science.  
El objetivo es aplicar el proceso **ETL (Extract, Transform)** sobre los datos de clientes de Telecom X, con el fin de analizar la evasión de clientes (churn).

## 🛠️ Proceso ETL
- **Extract**: los datos fueron obtenidos desde un archivo JSON en GitHub.
- **Transform**: 
  - Se aplanaron columnas anidadas (customer, phone, internet, account).
  - Se limpiaron valores nulos y duplicados.
  - Se transformaron variables categóricas (“Yes/No”) en numéricas.
  - Se convirtieron cargos y antigüedad a valores numéricos.

## 📈 Insights principales
- La tasa general de churn es del XX %.
- Los clientes con **contratos mensuales** presentan la mayor tasa de churn.
- El servicio de **fibra óptica** tiene mayor evasión en comparación con DSL.
- Los clientes con **cargos mensuales más altos** y **menor antigüedad** tienden a darse de baja.

## 👤 Autor
Proyecto realizado por Christian Nunovero
