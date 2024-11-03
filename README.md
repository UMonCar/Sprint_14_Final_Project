# Sprint_14_Final_Project
Sprint 14: Final project

# PROYECTO FINAL DATA ANALYST

## Repositorio:
https://github.com/UMonCar/Sprint_14_Final_Project

## Estructura del repositorio
**La `main branch` del repositorio está dividida en las siguietes carpetas:**
-   Telecomunicaciones
-   Test_AB
-   SQL

### Telecomunicaciones
En esta carpeta se tienen los archivos del ejecicio: `Proyecto Final: Telecomunicaciones: identificar operadores ineficaces`. Se tienen los siguientes archivos:
-   Carpeta `datasets`: Contiene los archivos .csv con los datos de los operadores de la compañía.
-   bad_op_metrics.csv (bad_op_metrics.pkl): dataset filtrado con los operadores clasificados como ineficaces usando los umbrales de las métricas más significativas, tanto en formato csv como pickle.
-   CallMeMaybe.pdf (CallMeMaybe.pptx): presentación con los resultados y conclusiones del análisis.
-   Clusters_calls.png y Clusters_metricas.png: Imágenes obtenidas de los gráficos construidos usando Tableau de las métricas de los opoeradores divididos por clusters.
-   dataset.csv (dataset.pkl): Dataset filtrado, retirando el 5% de valores demasiado altos, usando percentiles.
-   Descomposición_Telecom.ipynb: Archivo recopilatorio de actividades realizadas y referencias que se consideraron.  
-   opeator_efficiency_clusters.csv (opeator_efficiency_clusters.pkl): dataset con los clusters formados de los opearadores.
-   Operators_Dashboard.twb (Operators_Dashboard.twbx) proyeto de Tableau y dashboard. Consultar el dashboar obtenido en: [https://public.tableau.com/views/Operators_Dashboard/Operators_Dashboard?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]
-   telecom.ipnyb (telecom_correcciones.ipnyb): Proyecto con código en lenguaje python y descirpciones en markdown del análisis realizado. Revisar para analizar la transformación de los datos, clasificaciones, filtros, métricas obtenidas, datasets resultantes, gráficas de interés, clusters y umbrales.

### Test_AB
-   Carpeta `datasets`: Contiene los archivos .csv con los datos de la prueba A/B ralizada.
-   Test_AB.ipynb: Proyecto con código en lenguaje python y descirpciones en markdown del análisis realizado. Revisar para analizar la transformación de los datos, filtros, métricas obtenidas, datasets resultantes, gráficas de interés, y resultados y conclusiones de la prueba AB.

### SQL
-   CA.pem: archivo necesario para conectarse a la base de datos.
-   SQL_proyecto.ipynb (SQL_proyecto_correción.ipynb): Proyecto con código en lenguaje python, queries para consultas SQL y descirpciones en markdown.