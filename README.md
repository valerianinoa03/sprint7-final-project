# Análisis de una empresa de telecomunicaciones - Proyecto Sprint 7

## Objetivo del Proyecto


Entregar un reporte para ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia, con el fin de entender cómo los clientes usan realmente los servicios móviles (llamadas y mensajes).

El objetivo de la empresa es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

## Datasets utilizados

- plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

## Etapas del análisis
1. Cargar y explorar bases de datos para entender la estructura y tipos de datos.	
2. Identificación de problemas de calidad:	Contar nulos, detectar sentinels y revisar fechas fuera de rango.
3. Limpieza básica:	Reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas y análisis realizado
4. Summary statistics:	Revisar las medidas clave como media, mediana y opercentiles tanto en variables categóricas y numéricas para entender el comportamiento de las variables. 
5. Visualización & outliers:	Creación de histogramas y boxplots para entender sesgos, patrones de usuarios o datos atípicos.
6. Segmentación: Crear segmentaciones basadas en edad (Jóven/Adúlto/Adúlto Mayor) y grupo de uso (alto/medio/bajo) para visualizar proporciones. Con estos segmentos se concluyeron las recomendaciones diseñar ofertas, campañas y migraciones de plan.
7. Insight ejecutivo:	Se hicieron conclusiones del análisis y recomendaciones comerciales de diseño de oferta, campañas y tipos de planes. 

## Preguntas del negocio
- ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
- ¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro?
- ¿Cómo varía el uso según la edad y el tipo de plan contratado?
- ¿Qué patrones pueden ayudar a diseñar mejores planes, optimizar la oferta y mejorar la satisfacción del cliente?

## Cómo ejecutar el notebook
En Github:
1. Haz click en el archivo `.ipynb` en GitHub:

[Link Archivo Github](https://github.com/valerianinoa03/sprint7-final-project/blob/main/S7%20Version-Estudiante-Project-ConnectaTel.ipynb)

2. En Colab:
Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LfKVW-KR4OIMVMacFDfG5nx74INgN6c5?usp=sharing)




