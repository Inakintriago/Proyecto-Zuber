# 🚖 Zuber: Análisis de Datos de Taxis en Chicago

## 📝 Contexto
**Zuber** es un proyecto de análisis de datos enfocado en entender el comportamiento de las empresas de taxis y los patrones de viajes en Chicago durante noviembre de 2017. El objetivo es realizar un análisis exploratorio de datos sobre las compañías de taxis, las ubicaciones de finalización de los viajes y la duración de los viajes, y evaluar cómo las condiciones climáticas afectan la duración de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare. Este análisis proporcionará información valiosa sobre cómo optimizar los servicios de taxi y adaptarse a las condiciones meteorológicas.

## 🛠️ Herramientas Utilizadas
- **Python**: Análisis de datos y modelado estadístico.
- **Pandas**: Limpieza, transformación y análisis de datos.
- **Matplotlib** y **Seaborn**: Visualización de patrones y tendencias en los viajes y las ubicaciones.
- **SciPy**: Pruebas estadísticas para validar las hipótesis sobre la duración de los viajes en condiciones climáticas específicas.
- **Jupyter Notebook**: Documentación interactiva y detallada del análisis.

## 📈 Análisis de Resultados
El proyecto se estructuró en varias fases:

1. **Preprocesamiento de Datos**:
   - Importación de los conjuntos de datos `project_sql_result_01.csv` y `project_sql_result_04.csv`.
   - Verificación y limpieza de los datos para asegurar la integridad de la información.
   - Conversión de los datos a formatos adecuados y verificación de los tipos de datos.

2. **Análisis Descriptivo**:
   - Análisis de las compañías de taxis y el número de viajes realizados en los días 15 y 16 de noviembre de 2017.
   - Identificación de los 10 barrios de Chicago con el mayor número de finalizaciones de viajes.
   - Creación de gráficos para visualizar la relación entre las empresas de taxis y el número de viajes realizados, así como los 10 barrios más populares por finalización de viajes.

3. **Pruebas de Hipótesis**:
   - Evaluación de la hipótesis de que "La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los sábados lluviosos".
   - Análisis de los datos de duración de los viajes, condiciones climáticas y fechas para determinar si hay una diferencia significativa en los viajes durante los sábados lluviosos.

4. **Visualización de Datos**:
   - Gráfico de barras mostrando el número de viajes realizados por cada compañía de taxis.
   - Gráfico de barras con los 10 barrios principales de Chicago por número de finalizaciones de viajes.

## 📋 Conclusiones
- **Compañías de Taxis**: Las compañías con un mayor número de viajes probablemente tienen una mayor cobertura o popularidad entre los usuarios, lo que puede estar relacionado con la ubicación o la calidad del servicio.
- **Ubicación de los Viajes**: Los barrios más populares para la finalización de viajes están concentrados en el centro de Chicago, lo que refleja las áreas de mayor demanda de transporte.
- **Impacto de las Condiciones Climáticas**: La prueba de hipótesis mostró si las condiciones climáticas afectan significativamente la duración de los viajes, y los resultados ayudaron a entender cómo los días lluviosos impactan los viajes desde el Loop hacia el Aeropuerto O'Hare.
- **Optimización de Servicios**: Los resultados de este análisis pueden ayudar a las compañías de taxis a ajustar sus operaciones y a mejorar la planificación de rutas y horarios, especialmente en condiciones climáticas desfavorables.

Este proyecto proporciona una visión valiosa sobre los patrones de viajes en taxi en Chicago, lo que puede ser utilizado para optimizar la eficiencia operativa de las empresas de transporte en la ciudad.
