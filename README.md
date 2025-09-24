# Optimizador para la Extracción de Oro

## Tabla de Contenidos
- [Descripción](#Descripción)
- [Datos](#Datos)
- [Análisis](#Análisis)
- [Tecnologías y herramientas](#Tecnologías-y-herramientas)
- [Resultados](#Resultados)
- [Contribuciones](#Contribuciones)
- [Licencia](#Licencia)
- [Contacto](#Contacto)

## Descripción
Zyfra desarrolla soluciones para optimizar la eficiencia en industrias pesadas. Este proyecto crea un prototipo de modelo de Machine Learning para predecir la cantidad de oro extraído del mineral, utilizando datos de extracción y purificación, con el fin de optimizar producción y eliminar parámetros no rentables.

## Datos
Se utilizaron 3 conjuntos de datos principales:  
- **gold_recovery_full.csv**: DataFrame con 22,716 filas y 87 columnas que contiene datos del proceso completo de extracción y purificación de oro.
- **gold_recovery_train.csv**: DataFrame con 16,860 filas y 87 columnas usado para entrenar modelos predictivos con datos preprocesados y etiquetados.
- **gold_recovery_test.csv**: DataFrame con 5,856 filas y 53 columnas para evaluar modelos con datos de prueba, incluyendo variables clave del proceso.

## Análisis
El enfoque incluyó:  
- Procesamiento y limpieza de datos incluyendo conversión de fechas y manejo de valores faltantes.
- Validación precisa del cálculo de recuperación del concentrado rougher, asegurando calidad de datos.
- Exploración de distribuciones y comportamiento de metales en etapas de purificación.
- Eliminación de valores atípicos para evitar sesgos en el modelado.
- Entrenamiento y evaluación de modelos DecisionTreeRegressor, RandomForestRegressor y LinearRegression usando sMAPE y validación cruzada.

## Tecnologías y herramientas
- Python 3.9 para desarrollo y análisis de datos
- Pandas y NumPy para manipulación y procesamiento eficiente de datos
- Matplotlib y Matplotlib.dates para visualización de datos y series temporales
- Scikit-learn con modelos como Linear Regression, Decision Tree, Random Forest y Dummy Regressor para modelado predictivo
- Scikit-learn para evaluación de modelos con validación cruzada y métricas como error absoluto medio y R2

## Resultados
- El modelo RandomForestRegressor obtuvo el mejor desempeño con sMAPE final aproximado de 3.34%.
- Confirmación de la efectividad del modelo para predecir la extracción de oro en producción.
- Identificación de patrones distintos en la concentración de metales (oro, plomo, plata).
- Distribuciones de conjuntos de entrenamiento y prueba adecuadas, garantizando validez de evaluación.

## Contribuciones
Bienvenidas sugerencias, correcciones y nuevas visualizaciones. Por favor, abre un issue o pull request para colaborar.

## Licencia
Este proyecto está bajo la licencia MIT.

## Contacto
Nombre: Alejandro M. García  
Email: [alexkhype@gmail.com](mailto:alexkhype@gmail.com)  
LinkedIn: [linkedin.com/in/amggl](https://linkedin.com/in/amggl)
