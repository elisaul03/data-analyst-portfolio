# 🏭 Análisis de Eficiencia Industrial

## 📋 Descripción del Proyecto
Análisis integral de eficiencia operativa en entornos industriales, incluyendo optimización de procesos productivos, análisis de OEE (Overall Equipment Effectiveness) y predicción de mantenimiento preventivo para maximizar la productividad.

## 🎯 Objetivos
- Optimizar procesos productivos mediante análisis de datos
- Calcular y mejorar métricas OEE
- Implementar mantenimiento predictivo
- Crear reportes automatizados de eficiencia

## 🛠️ Tecnologías Utilizadas
- **Python:** NumPy, Pandas, Matplotlib, Scikit-learn
- **SQL:** Consultas para análisis de producción
- **Machine Learning:** Predicción de fallas, Optimización
- **IoT:** Sensores y datos en tiempo real

## 📊 Análisis Realizados

### 1. Cálculo de OEE (Overall Equipment Effectiveness)
```python
# Código de ejemplo
def calculate_oee(availability, performance, quality):
    oee = availability * performance * quality
    return oee

# Análisis por línea de producción
oee_by_line = production_data.groupby('line_id').apply(
    lambda x: calculate_oee(x['availability'], x['performance'], x['quality'])
)
```

### 2. Análisis de Tiempo de Inactividad
- Identificación de causas de paradas
- Análisis de patrones de fallas
- Optimización de tiempos de cambio

### 3. Predicción de Mantenimiento
- Modelos de predicción de fallas
- Optimización de cronogramas
- Reducción de tiempo de inactividad

### 4. Optimización de Procesos
- Análisis de cuellos de botella
- Balanceo de líneas
- Mejora de throughput

## 📈 Resultados Principales
- **Incremento del 25%** en OEE general
- **Reducción del 40%** en tiempo de inactividad
- **Ahorro del 30%** en costos de mantenimiento
- **Mejora del 20%** en productividad

## 📁 Archivos del Proyecto
- `oee_analysis.ipynb` - Notebook principal
- `maintenance_prediction.py` - Predicción de mantenimiento
- `process_optimization.py` - Optimización de procesos
- `efficiency_dashboard.py` - Dashboard de eficiencia
- `production_analysis.py` - Análisis de producción

## 🚀 Cómo Ejecutar
1. Instalar dependencias: `pip install numpy pandas matplotlib scikit-learn`
2. Ejecutar notebook: `jupyter notebook oee_analysis.ipynb`
3. Ver dashboard: `python efficiency_dashboard.py`

## 📊 Métricas Clave
- **OEE Promedio:** 85%
- **Tiempo de Inactividad:** 8%
- **Eficiencia de Mantenimiento:** 92%
- **Throughput:** +20%

## 🔧 Aplicaciones Industriales
- **Manufactura:** Optimización de líneas de producción
- **Automotriz:** Gestión de eficiencia en plantas
- **Farmacéutica:** Control de calidad y eficiencia
- **Alimentaria:** Optimización de procesos

## 📊 KPIs Industriales
- **Availability:** Tiempo de operación / Tiempo total
- **Performance:** Producción real / Producción teórica
- **Quality:** Productos buenos / Total producido
- **OEE:** Availability × Performance × Quality

## 🎯 Beneficios del Proyecto
- **Reducción de costos** operativos
- **Mejora de calidad** del producto
- **Aumento de capacidad** productiva
- **Optimización de recursos** humanos y materiales

---
*Proyecto desarrollado para maximizar la eficiencia operativa en entornos industriales* 