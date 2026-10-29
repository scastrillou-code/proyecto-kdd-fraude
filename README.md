Proyecto KDD - Detección de fraude bancario
Este proyecto aplica las cinco etapas del modelo Knowledge Discovery in Databases (KDD) sobre un conjunto de 5.000 transacciones bancarias, con el objetivo de identificar patrones asociados al fraude y evaluar modelos predictivos.
Principales técnicas utilizadas
	•	Limpieza y preprocesamiento de datos.
	•	Detección de outliers con IQR.
	•	Ingeniería de variables.
	•	One Hot Encoding y StandardScaler.
	•	K-Means.
	•	DBSCAN.
	•	PCA.
	•	Regresión Logística.
	•	Random Forest.
Principales resultados
	•	Tasa global de fraude: 2.18%
	•	Fraude en outliers de monto: 13.87%
	•	Fraude en transacciones nocturnas: 6.01%
	•	Cluster K-Means de mayor riesgo: 37.14%
	•	Recall Regresión Logística: 81.82%
	•	Recall Random Forest: 68.18%
La Regresión Logística mostró mayor capacidad para detectar fraudes, mientras que Random Forest redujo considerablemente las falsas alertas.
Archivos principales
	•	proyecto_kdd_fraude.ipynb
	•	README.md
	•	requirements.txt
Ejecución
El notebook puede ejecutarse de principio a fin utilizando Python y las siguientes librerías:
	•	pandas
	•	numpy
	•	matplotlib
	•	seaborn
	•	scikit-learn
Se utiliza random_state=42 para favorecer la reproducibilidad de los resultados.
