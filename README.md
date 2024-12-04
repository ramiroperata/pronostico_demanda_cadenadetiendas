# 📊 Pronóstico de Ventas con Prophet  

Este proyecto utiliza un enfoque basado en series temporales para pronosticar las ventas de una cadena de tiendas. A través de un análisis exhaustivo de los datos, ingeniería de características, e implementación del modelo Prophet, se busca proporcionar predicciones precisas y accionables.  

## 🛠️ Componentes del Proyecto  
### 1. Análisis de Datos Exploratorio (EDA)  
Se llevó a cabo un EDA para identificar patrones y tendencias clave en los datos, incluyendo:  
- Identificación de tendencias generales de ventas.  
- Análisis de estacionalidad semanal, mensual y anual.  
- Detección y tratamiento de valores atípicos.  

### 2. Ingeniería de Características  
Para mejorar el rendimiento del modelo, se generaron nuevas características basadas en los datos originales:  
- Variables de tiempo como el día de la semana, mes y año.  
- Indicadores de días festivos y promociones.  
- Agrupaciones por categoría de producto y ubicación de la tienda.  

### 3. Implementación de Prophet  
El modelo de series temporales `Prophet`, desarrollado por Facebook, fue utilizado para el pronóstico de ventas. Algunas características clave incluyen:  
- Manejo de tendencias no lineales.  
- Incorporación de efectos de días festivos.  
- Ajuste de hiperparámetros para optimizar el modelo.  

### 4. Resultados  
El modelo logró capturar patrones de demanda con alta precisión, reduciendo el error de pronóstico en comparación con métodos más básicos. Los resultados incluyen:  
- Gráficos de predicción con intervalos de confianza.  
- Identificación de períodos de alta y baja demanda.  
- Métricas de evaluación como MAE y RMSE.  

## 📂 Estructura del Repositorio
```
📁 pronostico_demanda_cadenadetiendas
├── 📂 data/ # Datos originales
├── 📂 notebook/ # Notebook con el análisis y modelo
├── 📜 README.md # Este archivo
└── 📜 LICENSE # Información sobre la licencia
```

## 🚀 Cómo Ejecutar  
1. Clona este repositorio:  
   ```bash
   git clone https://github.com/ramiroperata/pronostico_demanda_cadenadetiendas.git

2. Instala las dependencias necesarias:  
   ```bash
   pip install -r requirements.txt

3. Ejecuta el notebook en un entorno compatible, como Jupyter Notebook o Google Colab.

##🤝 Contribuciones
¡Contribuciones y sugerencias son bienvenidas! Por favor, abre un issue o envía un pull request.

📜 Licencia
Este proyecto está bajo la licencia Apache 2.0. Consulta el archivo [LICENSE](LICENSE) para más detalles.
