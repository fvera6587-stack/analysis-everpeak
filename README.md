# LADB Mobility Economy Analysis – Sprint 5

Este repositorio contiene el análisis realizado para el American Development Bank sobre la relación entre movilidad urbana y productividad económica en las principales ciudades del mundo.

🎯 Objetivo del proyecto
Analizar cómo la movilidad urbana (niveles de congestión, tiempos de viaje, retrasos) se relaciona con la productividad económica (PIB per cápita, desempleo) para identificar ciudades donde invertir en infraestructura de transporte.

📂 Contenido del repositorio
notebooks/ladb_mobility_analysis.ipynb → Notebook principal con limpieza, unión de datasets, análisis exploratorio y visualizaciones.
data/tomtom_traffic.csv → Datos de tráfico y congestión vehicular (TomTom Traffic Index).
data/oecd_city_economy.csv → Indicadores económicos y ambientales por ciudad (OECD Cities).
data/mobility_economy_2024.csv → Dataset final unificado listo para análisis.

Abre el archivo .ipynb en GitHub
Haz clic en Open in Colab
📘 Cómo reproducir el análisis
Abre notebooks/ladb_mobility_analysis.ipynb
Ejecuta las celdas en orden
Los datasets se cargan automáticamente desde las URLs proporcionadas
El notebook genera automáticamente el archivo final mobility_economy_2024.csv
🔍 Preguntas de negocio analizadas
¿Qué ciudades presentan alta congestión y baja productividad económica?
¿Cuáles muestran los mejores indicadores combinados (movilidad eficiente y economía fuerte)?
¿Qué variables tienen una relación más fuerte con el desarrollo urbano?
📊 Datasets utilizados
### TomTom Traffic Index (tomtom_traffic.csv)
- Fuente: Datos de tráfico en tiempo real de TomTom
- Período: 2024
- Variables clave: TrafficIndexLive, JamsDelay, TravelTimeLivePer10KmsMins

### OECD Cities (oecd_city_economy.csv)
- Fuente: Organización para la Cooperación y el Desarrollo Económico
- Período: 2024
- Variables clave: City GDP/capita, Unemployment, PM2.5, Population

🛠 Herramientas utilizadas
Python: pandas, numpy, seaborn, matplotlib
Jupyter Notebook
Google Colab
📈 Principales hallazgos
- **Ciudades con alta congestión y baja productividad**: Identificamos oportunidades de inversión en infraestructura donde mejorar la movilidad podría impulsar el crecimiento económico.
- **Correlación movilidad-economía**: Los datos muestran una relación significativa entre eficiencia del transporte y indicadores económicos urbanos.
- **Ciudades modelo**: Detectamos casos de éxito donde la movilidad eficiente coincide con alta productividad económica.

## 👥 Equipo

Análisis realizado para el American Development Bank (LADB) como parte del Sprint 5 - Proyecto de Movilidad Urbana y Economía.

**Analista**: Fernanda Vera
**Fecha**: 03/04/2026 
**Contacto**: fvera6587@gmail.com / Linkdln: https://www.linkedin.com/in/fernanda-vera-data-analyst/ 

## 📄 Licencia

Este proyecto fue desarrollado con fines educativos y de investigación para el American Development Bank.

---

*Para más información sobre este análisis, consulta el notebook principal o contacta al equipo de análisis.*
