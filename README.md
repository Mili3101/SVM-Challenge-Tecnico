# SVM-Challenge-Tecnico
"Análisis predictivo de supervivencia en el Titanic (Kaggle). Comparativa de modelos ML con LightGBM, XGBoost y más. ¡Accuracy 82%!"
# 🚢 Análisis de Supervivencia en el Titanic - Kaggle Challenge

![Titanic](https://img.shields.io/badge/Dataset-Titanic-blue) 
![Python](https://img.shields.io/badge/Python-3.8%2B-blue) 
![License](https://img.shields.io/badge/License-MIT-green)

Repositorio con la solución al challenge de **Kaggle: Titanic - Machine Learning from Disaster**.  
Incluye EDA, preprocesamiento, modelado (5 algoritmos) y benchmarking.

---

## 📌 **Descripción del Proyecto**
El objetivo es predecir la supervivencia de pasajeros del Titanic utilizando Machine Learning.  
Se implementaron y compararon 5 modelos:
- Regresión Logística  
- K-Nearest Neighbors (KNN)  
- Árbol de Decisión  
- XGBoost  
- LightGBM  

**Métrica principal**: Accuracy (exactitud).

---

## 📂 **Contenido del Repositorio**
- `titanic_analysis.ipynb`: Notebook con todo el flujo de trabajo (EDA, modelos y resultados).  
- `README.md`: Este archivo.  

---

## 🔍 **Estructura del Dataset (891 registros)**
   python
RangeIndex: 891 entries, 0 to 890
Data columns (total 11 columns):
 #   Column       Non-Null Count  Dtype  
---  ------       --------------  -----  
 0   passengerid  891 non-null    int64  
 1   survived     891 non-null    int64  
 2   pclass       891 non-null    int64  
 3   name         891 non-null    object 
 4   sex          891 non-null    object 
 5   age          891 non-null    float64
 6   sibsp        891 non-null    int64  
 7   parch        891 non-null    int64  
 8   ticket       891 non-null    object 
 9   fare         891 non-null    float64
 10  embarked     889 non-null    object

## 📊**  Resultados ** 
Modelo	            Accuracy	Precision	Recall	F1-Score
KNN	                82.12%	80.33%	71.01%	75.38%
Logistic Regression	81.01%	73.97%	78.26%	76.06%
LightGBM	          81.56%	  82.14%	66.67%	73.60%
XGBoost	            78.77%	70.67%	76.81%	73.61%
Random Forest	      78.77%	73.13%	71.01%	72.06%

**Conclusiones:**

Mejor modelo: KNN (Accuracy: 82.12%)

LightGBM obtuvo la mayor precisión (82.14%)

Logistic Regression mostró el mejor balance (F1-Score: 76.06%)

**🛠️ Cómo Usar**
Clonar repositorio:

bash
git clone https://github.com/tu-usuario/titanic-analysis.git
Instalar dependencias:

bash
pip install -r requirements.txt
Ejecutar Jupyter Notebook:

bash
jupyter notebook titanic_analysis.ipynb


**📜 Licencia** 

Este proyecto está bajo la licencia MIT.

```
