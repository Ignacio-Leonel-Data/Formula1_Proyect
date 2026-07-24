# Dashboard Power BI – Formula 1

<img width="1516" height="848" alt="1ba05e466c1e7d9473da190bf5777362-Photoroom (1)" src="https://github.com/user-attachments/assets/7f4fb0d9-0b36-40e2-b914-04a7e02a65c7" />

Período analizado: temporadas 1996–2005 y 2014–2024.

## 📁 Estructura

| Archivo | Descripción |
|---------|-------------|
| Tablero/Formula1_Proyect.pbix | Dashboard interactivo |
| Docs/Documentacion_Tecnica.pdf | Detalle técnico del modelo |
| Docs/MEDIDAS_DAX.md | Medidas DAX utilizadas |
| images/ | Capturas del modelo y reportes 

## 💾 Modelo de Datos

El proyecto se basa en un modelo relacional donde la tabla Results actúa como núcleo del análisis, conectando pilotos, escuderías, carreras y circuitos mediante claves primarias y foráneas.


## 📐 Medidas DAX

Incluye:
- KPIs de victorias, podios, pilotos analizados y carreras disputadas.
- Puntos promedio por carrera y tiempo promedio de carrera.
- Porcentaje promedio de abandonos.

Más detalles en: [Medidas DAX utilizadas](Docs/MEDIDAS_DAX.md)

## ✅ Conclusión

El proyecto permitió integrar un flujo completo de análisis de datos, desde la preparación del dataset hasta la construcción de un dashboard interactivo. La combinación de Python para la limpieza, SQL Server para el modelado y Power BI para la visualización hizo posible transformar datos históricos de la Fórmula 1 en información clara y útil para comparar el rendimiento de escuderías y pilotos entre dos eras del campeonato
## 📄 Documentación Técnica

- [Documentacion Tecnica del Proyecto Formula 1](Docs/Documentacion_TecnicaF1.pdf)
- [Medidas DAX utilizadas](Docs/MEDIDAS_DAX.md)

## 🎨 Tema personalizado

El diseño visual del dashboard está basado en un archivo `.json` personalizado con colores Rojos y Negros. Puedes descargarlo y aplicarlo desde Power BI:
