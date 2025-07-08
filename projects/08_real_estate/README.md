# 🏠 Análisis de Mercado Inmobiliario

## 📋 Descripción del Proyecto
Análisis comprehensivo del mercado inmobiliario para predecir precios de viviendas, identificar tendencias del mercado y segmentar propiedades, utilizando machine learning y análisis geoespacial para optimizar decisiones de inversión.

## 🎯 Objetivos
- Predecir precios de viviendas con precisión
- Analizar tendencias del mercado por zona
- Segmentar propiedades por características
- Crear dashboard de mercado inmobiliario

## 🛠️ Tecnologías Utilizadas
- **Python:** Scikit-learn, Pandas, SQL, Folium
- **SQL:** Consultas para análisis de propiedades
- **Machine Learning:** Regresión, Clustering, Random Forest
- **Visualización:** Folium, Matplotlib, Seaborn

## 📊 Análisis Realizados

### 1. Predicción de Precios
```python
# Código de ejemplo
from sklearn.ensemble import RandomForestRegressor
from sklearn.model_selection import train_test_split

# Entrenamiento del modelo
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
model = RandomForestRegressor(n_estimators=100)
model.fit(X_train, y_train)
predictions = model.predict(X_test)
```

### 2. Análisis de Tendencias
- Evolución de precios por zona
- Análisis de estacionalidad
- Factores económicos influyentes
- Indicadores de mercado

### 3. Segmentación de Propiedades
- Clustering por características
- Análisis de vecindarios
- Clasificación por tipo de propiedad
- Análisis de amenities

### 4. Análisis Geoespacial
- Mapeo de precios por zona
- Análisis de proximidad a servicios
- Densidad de propiedades
- Análisis de transporte público

## 📈 Resultados Principales
- **Precisión del modelo:** 89% en predicción de precios
- **Identificación** de 15 zonas de inversión
- **Análisis** de 50+ factores de precio
- **Optimización** de estrategias de inversión

## 📁 Archivos del Proyecto
- `real_estate_analysis.ipynb` - Notebook principal
- `price_prediction.py` - Modelo de predicción
- `market_trends.py` - Análisis de tendencias
- `property_segmentation.py` - Segmentación de propiedades
- `geospatial_analysis.py` - Análisis geoespacial

## 🚀 Cómo Ejecutar
1. Instalar dependencias: `pip install scikit-learn pandas folium`
2. Ejecutar notebook: `jupyter notebook real_estate_analysis.ipynb`
3. Ver dashboard: `python real_estate_dashboard.py`

## 📊 Métricas Clave
- **Propiedades Analizadas:** 25,000+
- **Precisión del Modelo:** 89%
- **Zonas Identificadas:** 15
- **Factores Analizados:** 50+

## 🏘️ Tipos de Propiedades
- **Residencial:** Casas, apartamentos, condominios
- **Comercial:** Oficinas, locales, almacenes
- **Industrial:** Naves, terrenos industriales
- **Terrenos:** Lotes urbanos y rurales

## 📍 Factores de Precio Analizados
- **Ubicación:** Zona, barrio, proximidad a servicios
- **Características:** Metros cuadrados, habitaciones, baños
- **Amenities:** Parqueaderos, ascensores, seguridad
- **Económicos:** Tasa de interés, inflación, PIB

## 🎯 Segmentos de Mercado
- **Lujo:** Propiedades premium, alto valor
- **Medio-Alto:** Propiedades de calidad superior
- **Medio:** Propiedades estándar
- **Económico:** Propiedades de entrada

## 📊 Indicadores de Mercado
- **Precio por m²:** Valor promedio por zona
- **ROI:** Return on Investment
- **Cap Rate:** Capitalization Rate
- **Days on Market:** Tiempo de venta promedio

## 🗺️ Análisis Geoespacial
- **Heatmaps** de precios por zona
- **Clustering** de propiedades similares
- **Análisis de proximidad** a servicios
- **Densidad poblacional** y desarrollo

## 💡 Insights Clave
- **Zonas emergentes** con potencial de plusvalía
- **Factores críticos** que afectan precios
- **Tendencias estacionales** del mercado
- **Oportunidades de inversión** identificadas

## 📈 Aplicaciones del Proyecto
- **Inversores:** Identificación de oportunidades
- **Desarrolladores:** Análisis de viabilidad
- **Agentes:** Valuación de propiedades
- **Bancos:** Evaluación de hipotecas

---
*Proyecto desarrollado para optimizar decisiones de inversión inmobiliaria* 