# Predicción de Series de Tiempo en Criptomonedas

Este es un **proyecto personal** que aborda el flujo completo de un análisis y modelado de series de tiempo aplicado a precios de criptomonedas. Se exploran diferentes enfoques de predicción, desde modelos clásicos hasta modelos basados en Deep Learning, con el objetivo de capturar tendencias y picos de manera más precisa.

---

## 📌 Tabla de Contenidos
1. **Obtención de datos**  
   - Automatización para descargar datos hasta la fecha actual y hacia atrás N días.  
2. **Preprocesamiento**  
   - Ordenar fechas y eliminar duplicados.  
   - Manejo de valores faltantes (relleno, interpolación, eliminación).  
   - Conversión de precios a retornos logarítmicos.  
3. **Visualización exploratoria**  
   - Gráficos de series de precios y retornos.  
   - Histogramas y análisis de autocorrelación.  
4. **Modelado**  
   - Modelos clásicos: ARIMA, SARIMA, GARCH (para volatilidad).  
   - Modelos recientes: LSTM y Transformers.  
   - Comparación de modelos (incluyendo XGBoost).  
5. **Evaluación y validación**  
   - Métricas: MSE, RMSE, MAE, MAPE.  
   - Walk-forward validation.  
6. **Predicción / Forecasting**  
   - Pronósticos de precios futuros.  
   - Intervalos de confianza y análisis de resultados.  

---

## ⚙️ Tecnologías utilizadas
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)  
- **Modelos clásicos**: statsmodels (ARIMA, SARIMA, GARCH)  
- **Machine Learning**: XGBoost  
- **Deep Learning**: TensorFlow/Keras (LSTM, Transformers)  

---

## 📊 Resultados principales
- El modelo **XGBoost** mostró el mejor desempeño en la captura de tendencias y picos, superando a los modelos clásicos y de Deep Learning en este conjunto de datos.  
- Se observa que los modelos basados en redes neuronales (LSTM) son capaces de adaptarse a patrones complejos, pero requieren mayor ajuste para mejorar su capacidad predictiva.  

---

## 🚀 Conclusión
Este **proyecto personal** evidencia la importancia de combinar enfoques clásicos y modernos en el análisis de series de tiempo en criptomonedas. Mientras que modelos como ARIMA aportan una base sólida para patrones lineales, algoritmos como **XGBoost** destacan en la captura de tendencias abruptas y no lineales, lo que los hace especialmente útiles en mercados volátiles como el de las criptomonedas.

---

✍️ Autor: **Juan Carvajal**  
📅 Año: 2025
