<div align="center">

![Visualización](https://img.shields.io/badge/VISUALIZACI%C3%93N-00838F?style=for-the-badge)

# Storytelling con datos: cancelaciones de reservas hoteleras

Narrativa visual sobre por qué se cancelan las reservas de hotel en Portugal: análisis exploratorio en R y Python y un dashboard narrativo en Streamlit.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) ![R Markdown](https://img.shields.io/badge/R_Markdown-276DC3?style=flat-square&logo=r&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

<img src="imgs/Mapa%20detallado%20de%20Portugal%20y%20hoteles.png" alt="Mapa de Portugal con la ubicación de los hoteles del conjunto de datos" width="100%" />

</div>

---

## Descripción general

A partir del conjunto de datos *Hotel Bookings*, el proyecto busca primero problemas de calidad y patrones con un análisis exploratorio, y después construye una historia: qué reservas se cancelan, cuándo y por qué canales. El resultado es un dashboard que guía al lector paso a paso.

## Funcionalidades

- **Análisis exploratorio** en R Markdown y en Python: hoteles y cancelaciones, estacionalidad, antelación de la reserva, estancias, precios, mercados de origen y canales de distribución.
- **Dashboard narrativo en cinco pestañas:** el problema, radiografía del conjunto de datos, el factor tiempo, canales y comportamiento, y conclusiones.
- **Presentación** en diapositivas y vídeo con el guion de la historia.

## Tecnologías y herramientas

| Ámbito | Herramientas |
| --- | --- |
| Dashboard | Streamlit, Plotly |
| Análisis | Python (pandas), R y R Markdown |

## Estructura del proyecto

```text
.
├── dashboard_PEC3_completo.py   # Versión final del dashboard (v1 y v2 son versiones previas)
├── 1. Datos/                    # Descripción del conjunto de datos y del EDA
├── 5. Notebook/                 # EDA en Jupyter y en R Markdown
├── 3. Presentacion y video/     # Diapositivas, guion e informe
├── imgs/                        # Imágenes del dashboard
└── requirements.txt
```

## Instalación y uso

```bash
pip install -r requirements.txt
streamlit run dashboard_PEC3_completo.py
```

## Aspectos técnicos destacados

- Del análisis exploratorio a una narrativa progresiva: cada pestaña responde a una pregunta y prepara la siguiente.
- Mismo análisis en R y en Python.

## Autor

**Julio Úbeda Quesada** · Data Scientist

[![Portfolio](https://img.shields.io/badge/Portfolio-0B2545?style=flat-square&logo=astro&logoColor=white)](https://juliouq.github.io/Portfolio-Web---JulioUQ/es/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square)](https://www.linkedin.com/in/juliouq/) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JulioUQ)

<sub>Proyecto realizado en el Máster Universitario en Ciencia de Datos.</sub>
