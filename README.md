# Detector de Phishing a Partir de una URL
![Texto alternativo](https://github.com/Capape29/DetectorPhishing/blob/main/Banner.png)



## Autores
**Camilo Iván Palacio Pérez**, **Carlos Eduardo Ayala Moreno**, **Snheider Alejandro Olarte saavedra**

---

## Objetivo


Desarrollar un sistema de detección de phishing capaz de analizar, clasificar y determinar de manera precisa si una URL corresponde a un sitio web legítimo o malicioso, mediante la integración de técnicas de aprendizaje automático, análisis de características estructurales y comportamentales de las URLs, y validación sobre conjuntos de datos reales. 


## Dataset

### Malicious URLs dataset
Este dataset ha recopilado un enorme conjunto de datos de 651.191 URL, de las cuales 428.103 son URL benignas o seguras, 96.457 son URL de desfiguración, 94.111 son URL de phishing y 32.520 son URL de malware. La figura 2 muestra su distribución en términos porcentuales. Como sabemos, una de las tareas más cruciales es seleccionar el conjunto de datos para un proyecto de aprendizaje automático. Hemos seleccionado este conjunto de datos de cinco fuentes diferentes.
[Dataset](https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset?utm_source=chatgpt.com)


## Modelos

### Machine Learning — Clasificación
**Modelos probados**
- Gaussian Naive Bayes  
- Decision Tree Classifier  
- **Random Forest Classifier**  — *Mejor modelo supervisado del proyecto*
- Support Vector Machine (SVM)

### Reducción de dimensionalidad
- PCA  
- **t-SNE** — *Mejor técnica para el proyecto*

### Clustering
- K-Means
- **DBSCAN** — *Mejor modelo no supervisado del proyecto*

---

## Enlaces
- [video](https://youtu.be/NHe4IDqEc6E)
- [código principal](https://github.com/Capape29/DetectorPhishing/blob/main/notebooks/detectorPhishing_Supervisado.ipynb)
- [repositorio](https://github.com/Capape29/DetectorPhishing)
- [Drive](https://drive.google.com/drive/folders/1AjygrvKssQh7en3kD0ei3oMPP59eqlVL?usp=sharing)
