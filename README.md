# Technical-Test-QA


Este proyecto consiste en un analisis de calidad de datos de nuestro repositorio de albums de Taylor Switf.

## Archivos

1. **Código Python:** El código fuente se encuentra en el archivo `Análisis_QA_Taylor_.ipynb`. Este archivo contiene la implementación principal del proyecto y adicional incluye la instrucción para montar Google Drive debido a que los archivos de extracción y carga se estan almacenando en el repo :.

2. **HTML Generado:** El archivo `Informe_ Analisis_QA.html` es la salida generada por el código Python. Este HTML muestra el resultado de nuestro analisis de calidad.

3. **Reporte de Calidad de Datos:**
   - Se ha utilizado la librería `pandas_profiling` para realizar un análisis detallado de la calidad de los datos.
   - El informe generado se encuentra en el archivo `quality_report_profiling.html`. Este informe ofrece una visión completa de la calidad de los datos utilizados en el proyecto.

4. **Video Explicativo de nuestro codigo del punto 1-22:**
   - [Enlace al video explicativo](https://drive.google.com/file/d/14Jn0koleVcIgqbixeyuGN83gNCsApuVS/view?usp=sharing) que proporciona una guía detallada sobre el contenido y la interpretación del archivo HTML generado por el código.


## Nota Importante

Este proyecto fue desarrollado y ejecutado en [Google Colab](https://colab.research.google.com/), utilizando Google Drive para cargar archivos. Recomiendo configurar las rutas en el código dependiendo el repositorio donde se encuentran -json y donde desee cargar el csv y .html.


## Requisitos

Para ejecutar el código en Google Colab, asegúrate de tener instaladas las siguientes dependencias:

```bash
pip install https://github.com/pandas-profiling/pandas-profiling/archive/master.zip
pip install mpld3
