# 📞 Proyecto 14. Identificación de Operadores Ineficaces – CallMeMaybe

## 📌 Descripción del proyecto
En este repositorio se analiza datos de telecomunicaciones del servicio CallMeMaybe con el objetivo de identificar operadores ineficaces a partir de métricas operativas clave como llamadas perdidas, tiempos de espera y volumen de llamadas salientes.

El enfoque combina análisis exploratorio, estadística aplicada y normalización de métricas, priorizando decisiones basadas en datos y criterios de negocio reales.

---

## 🎯 Objetivo
Detectar operadores con bajo desempeño operativo para apoyar la toma de decisiones estratégicas y mejorar la eficiencia del call center.

Un operador se considera ineficaz si presenta:
- Alta cantidad de llamadas perdidas (internas y externas)
- Tiempos de espera elevados
- Bajo volumen de llamadas salientes

---

## 🧠 Enfoque analítico
- Análisis exploratorio de datos (EDA) con interpretación de negocio
- Gestión diferenciada de valores nulos y duplicados
- Evaluación consciente de valores atípicos (no eliminación automática)
- Agregación y comparación de métricas por operador
- Construcción de un índice de ineficiencia normalizado
- Validación estadística mediante prueba de Levene

---

## 📊 Principales métricas utilizadas
- Llamadas perdidas internas y externas
- Tiempo promedio de espera
- Cantidad de llamadas entrantes y salientes
- Duración promedio de llamadas
- Índice de ineficiencia (score compuesto)

---

## 📈 Resultados clave
- ~44% del total de llamadas fueron perdidas
- Las llamadas salientes presentan mayor duración y tiempo de espera
- Se identificaron operadores con patrones extremos de ineficiencia
- La prueba estadística confirmó diferencias significativas entre operadores eficientes e ineficientes

---

## 🧪 Prueba estadística
- Hipótesis: comparación de la varianza del índice de ineficiencia
- Método: Prueba de Levene
- Resultado: diferencia estadísticamente significativa entre operadores más y menos eficaces

---

## 📊 Dashboard
📍 Visualización interactiva en Tableau Public:
- Distribución de duración de llamadas
- Llamadas internas vs externas
- Métricas de ineficiencia por operador

**Enlace disponible en el repositorio** 
https://public.tableau.com/views/DashboardProyectofinalTelecomunicaciones/Dashboard2?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## 🚀 Habilidades demostradas
- Análisis estadístico aplicado a negocio
- Construcción de métricas normalizadas
- Pensamiento analítico orientado a predicción
- Evaluación crítica de datos atípicos
- Comunicación clara de hallazgos
- Preparación de proyectos para portafolio profesional

---

## 🛠️ Herramientas y tecnologías
- Python (Pandas, NumPy, SciPy)
- Visualización: Matplotlib, Seaborn
- Estadística inferencial
- Tableau Public (Dashboard)
- GitHub & Markdown
  
---

## 🛠️ Herramientas y tecnologías
- Python (Pandas, NumPy, SciPy)
- Visualización: Matplotlib, Seaborn
- Estadística inferencial
- Tableau Public (Dashboard)
- GitHub & Markdown
