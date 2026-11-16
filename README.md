# 📊 Experimento A/B en Página de Inicio (Landing Page)

Evaluación estadística de un experimento A/B con 40,000 usuarios expuestos a dos variantes de una página de inicio (**Versión A** vs. **Versión B**), con el objetivo de determinar qué diseño maximiza la tasa de conversión y el gasto promedio por cliente.

## 🛠️ Herramientas y Librerías
- **Python 3**
- **Pandas & NumPy:** Limpieza, validación de integridad y análisis exploratorio.
- **SciPy (`ttest_ind`, `chi2_contingency`) & Statsmodels (`proportions_ztest`):** Pruebas de hipótesis (Prueba t de Welch, Prueba Z de dos proporciones y Prueba Chi-cuadrado con V de Cramér).
- **Matplotlib & Seaborn:** Visualización de distribuciones absolutas y proporciones normalizadas.

## 📈 Principales Hallazgos
- **Gasto promedio por comprador:** La versión B alcanzó un promedio de **USD 68.75** frente a **USD 61.09** en la versión A (+USD 7.66 por comprador / +12.5%; $p = 3.63 \times 10^{-21}$).
- **Tasa de conversión:** La versión B convirtió al **15.96%** frente al **12.57%** de la versión A (+3.39 puntos porcentuales; $p = 3.76 \times 10^{-22}$).
- **Canales de tráfico y tipo de usuario:** El comportamiento de conversión se mantiene estable entre usuarios nuevos y recurrentes ($p = 0.474$) y presenta variaciones mínimas entre canales de adquisición ($V \text{ de Cramér} = 0.015$).

## 💡 Recomendación de Negocio
Desplegar la **Versión B** como página principal y mantener una experiencia unificada sin segmentar por historial previo del usuario.
