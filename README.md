# 📊 TelecomX LATAM – Análisis de Cancelación de Clientes (Churn)

## 📌 Descripción
Este proyecto tiene como objetivo analizar el fenómeno de **evasión de clientes (Churn)** en la empresa **TelecomX LATAM**.  
Se aplican técnicas de análisis de datos y modelos de *machine learning* para **identificar factores clave** asociados a la cancelación de clientes y proponer **estrategias de retención**.

---

## 🗂️ Contenido del Repositorio
- `TelecomX_LATAM.ipynb` → Notebook con todo el análisis paso a paso.  
- `datos_.entrenados.csv` → Dataset limpio y preprocesado (sin columnas irrelevantes).  
- `README.md` → Documentación del proyecto.  

---

## 🛠️ Tecnologías Utilizadas
- **Python 3**  
- **Pandas, Numpy** → Manipulación y transformación de datos.  
- **Matplotlib, Seaborn** → Visualización de datos.  
- **Scikit-Learn** → Modelado predictivo y evaluación.  
- **Google Colab / Jupyter Notebook** → Entorno de trabajo.  

---

## 🔎 Análisis Exploratorio (EDA)
- Distribución general de clientes que cancelan (~26.5%).  
- Variables clave: **tipo de contrato, método de pago, antigüedad (tenure), gasto mensual y total, servicio de internet**.  
- Gráficos de correlación, boxplots y scatter plots para identificar patrones.  

---

## 🤖 Modelos Predictivos
Se entrenaron y evaluaron dos modelos principales:

1. **Regresión Logística (con normalización)**  
   - Accuracy ≈ 80%  
   - Mejor desempeño en recall y F1-score para clientes que cancelan.  

2. **Random Forest (sin normalización)**  
   - Accuracy ≈ 78%  
   - Destacó la importancia de variables como `tenure`, `contract`, y `charges.total`.  

📊 **Conclusión de Modelos:**  
La **Regresión Logística** ofreció mejor equilibrio entre métricas, aunque ambos modelos coincidieron en identificar los mismos factores de churn.  

---

## ✅ Principales Factores de Cancelación
- **Contratos mensuales** → mayor probabilidad de churn.  
- **Clientes nuevos (tenure bajo)** → más propensos a desertar.  
- **Método de pago "electronic check"** → asociado con mayor evasión.  
- **Altos costos mensuales** → incrementan el churn.  
- **Servicio de fibra óptica** → presenta mayor tasa de cancelación que DSL.  

---

## 🚀 Estrategias de Retención Propuestas
1. Programas de **fidelización temprana** para clientes nuevos.  
2. Incentivar **contratos a largo plazo** con beneficios.  
3. Promover **pagos automáticos con tarjeta/débito**.  
4. Diseñar planes flexibles para **clientes con altos costos mensuales**.  
5. Mejorar la experiencia del servicio de **fibra óptica**.  

---

## 👩‍💻 Autor
**Cleysi Yeraldi Ramos Abanto**  
---
