# 📌 Resumen del Proyecto Final – Sistema de IA para Detección de Fraude en Pagos Digitales

## 🧾 Contexto
- Fraude financiero: 0.1% de transacciones → 60% de pérdidas.
- Problema actual: alta tasa de falsos positivos → bloqueos de pagos legítimos.

## 🎯 Objetivo General
Diseñar y validar un sistema supervisado de IA, explicable y adaptable, que maximice la detección de fraudes y minimice falsos positivos, integrando aprendizaje continuo.

## ✅ Objetivos Específicos
- Pipeline automatizado con >200 variables derivadas.
- Implementar IA explicable (SHAP) para justificar ≥95% de alertas.
- Arquitectura de scoring en tiempo real + dashboard de monitoreo.
- Estrategia de online learning para actualización periódica.

## 🛠️ Solución Propuesta
- **Tipo de problema**: Clasificación binaria (fraude vs legítimo).
- **Modelos**: XGBoost, LightGBM, ANN → Ensemble híbrido.
- **Explicabilidad**: SHAP para transparencia y cumplimiento.
- **Pipeline**: modular, escalable, adaptable a sistemas financieros.

## 🧠 Arquitectura Preliminar
1. Flujo transaccional en tiempo real.
2. Pipeline de feature engineering.
3. Modelos paralelos:
   - Ensemble supervisado + SHAP.
   - Autoencoder para anomalías.
   - GNN para patrones colusivos.
4. Consolidación de alertas → Dashboard de monitoreo.

## 📊 Datos
- Dataset sintético: 200,000 transacciones, 5,000 usuarios.
- Variables: demográficas, transaccionales, temporales, contextuales.
- Desbalance intencional: 0.1% fraude.
- Almacenamiento en CSV, estructura jerárquica (raw, processed, results).

## 📈 Metodología (14 semanas)
- F1–EDA y diseño de features.
- F3–Entrenamiento y comparación de modelos.
- F4–Explicabilidad con SHAP + GNN preliminar.
- F5–Dashboard prototipo con Streamlit.
- F6–Documentación y presentación final.

## 📌 Métricas
- Negocio: Precisión a Recall fijo (95%).
- Técnicas: AUC-PR, F1, matriz de confusión.

## ⚙️ Herramientas
- Python, Jupyter Notebook.
- Librerías: Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, TensorFlow/PyTorch, SHAP, Optuna.
- Visualización: Matplotlib, Seaborn, Plotly, Streamlit, Power BI.
- Infraestructura: Google Colab Pro, instancias cloud con GPU.

## 🧾 Viabilidad
- Hardware: GPU NVIDIA T4 o superior.
- Presupuesto: $150–$500 (cloud computing).
- Riesgos: integración de múltiples enfoques, claridad de explicaciones SHAP.
- Mitigación: enfoque modular + reportes estandarizados.

## 📚 Referencias
- Chen & Guestrin (2016) – XGBoost.
- Ke et al. (2017) – LightGBM.
- Lundberg & Lee (2017) – SHAP.
- Molnar (2022) – Interpretable ML.
- Zhou et al. (2021) – GNNs en fraude.
- Chalapathy & Chawla (2019) – Anomaly detection.
- Bhattacharyya et al. (2011) – Credit card fraud mining.
