# telecom-churn-analysis
Análisis exploratorio de datos y pruebas de hipótesis estadísticas para identificar factores relacionados con la pérdida de clientes en una empresa de telecomunicaciones.

Descripción

Este proyecto analiza el comportamiento de 500 usuarios del operador de telecomunicaciones Megaline durante 2018. El objetivo es determinar cuál de los planes de prepago, Surf o Ultimate, genera mayores ingresos para apoyar la toma de decisiones del departamento de marketing.

El análisis incluye la preparación de los datos, el cálculo de métricas de consumo, la exploración estadística, la visualización de distribuciones y la realización de pruebas de hipótesis para responder preguntas de negocio.

Objetivos
Preparar y limpiar los datos.
Calcular el consumo mensual de llamadas, mensajes e internet por usuario.
Estimar los ingresos mensuales considerando las reglas de facturación.
Comparar el comportamiento de los usuarios entre ambos planes.
Aplicar pruebas de hipótesis para evaluar diferencias estadísticas.
Formular recomendaciones de negocio basadas en los resultados.

Tecnologías utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Jupyter Notebook

Principales resultados
Los usuarios de ambos planes presentan un comportamiento similar en llamadas e internet.
Los usuarios del plan Ultimate envían más mensajes en promedio.
El ingreso promedio por usuario es mayor en Ultimate.
El plan Surf presenta una mayor variabilidad en ingresos debido a los cargos por excedentes.
Surf genera mayores ingresos totales porque concentra un mayor número de usuarios.
Las pruebas de hipótesis confirmaron diferencias estadísticamente significativas tanto entre los planes como entre las regiones analizadas.

Proceso de desarrollo

Este proyecto fue desarrollado de forma iterativa siguiendo el proceso de revisión del proyecto. Después de recibir retroalimentación se realizaron varias mejoras, entre ellas:

Se reforzaron las interpretaciones de los gráficos utilizando estadísticas descriptivas como medias, desviaciones estándar y percentiles.
Se añadieron interpretaciones de negocio después de cada prueba de hipótesis, explicando el significado práctico de los resultados.
Se mejoró la conclusión general incorporando los principales supuestos y decisiones metodológicas del análisis (reglas de redondeo, tratamiento de ingresos y pruebas estadísticas utilizadas).
Se revisó la redacción y organización del notebook para hacer más claras las explicaciones y facilitar la lectura.

Conclusión

El análisis muestra que el plan Ultimate genera un mayor ingreso promedio por usuario y presenta ingresos más estables, mientras que Surf produce mayores ingresos totales debido a que cuenta con una base de usuarios más amplia. Dependiendo del objetivo de negocio, Megaline puede priorizar la promoción de uno u otro plan.

Autor

Alí Mayo Gómez
