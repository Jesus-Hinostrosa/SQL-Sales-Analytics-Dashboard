# SQL-Sales-Analytics-Dashboard

### Contexto: 
La empresa ha experimentado un crecimiento constante en el volumen de ventas durante los últimos meses; sin embargo, la dirección comercial necesita comprender mejor el comportamiento de los clientes,
productos y regiones para optimizar la toma de decisiones y detectar oportunidades de mejora.

Como Analista de Datos Junior, se te solicita realizar un análisis exploratorio y ejecutivo utilizando la información de órdenes, clientes y productos proporcionada por las áreas operativas.

### Objetivo del análisis

Desarrollar un análisis de desempeño comercial que permita identificar:

- Las categorías y productos con mayor impacto en ingresos,
- patrones de compra de los clientes,
- tendencias temporales en ventas,
- mercados/regiones con mejor y peor desempeño,
- y oportunidades potenciales para mejorar ingresos y retención de clientes.

### Descripción del dataset
El proyecto anterior consistió en limpiar un dataset con más de 2000 datos en la tabla principal. Contamos con tres tablas: 
- "orders_cleaned" es la tabla principal, tiene información acerca de los pedidos, los clientes y las transacciones
- "products_cleaned" tiene información acerca de los productos, indicado su categoria y precio
- "customers_cleaned" tiene información de los clientes, indicando el país de origen y la fecha en la que comenzaron a ser clientes

### Herramientas técnicas
- SQL
- Excel
- Tablas dinámicas
- Gráficas dinámicas
- Herramientas de limpieza de datos

### Análisis de KPIs
En el documento "Análisis de KPIs.docx" enlistamos preguntas diseñadas para entender los patrones y tendencias de nuestro dataset.

### Dashboard
En el documento "Dashboard ejecutivo.xlsx" mostramos las Querys ocupadas para responder a las preguntas planteadas en "Análisis de KPIs.docx", las tablas de resultados obtenidas con dichas Querys y un dashboard 
que presenta la información de manera dinámica.

### Insights
En el archivo "Dashboard ejecutivo.xlsx" mostramos el siguiente dashboard 
<img width="1442" height="661" alt="image" src="https://github.com/user-attachments/assets/2f3367ce-32bc-4a7b-ac16-719fc96703a7" />

Que ejemplifica nuestras key insights:
1.	Concentración de ingresos: La categoría “electrónicos” generó un 42% del porcentaje total de ingresos, siendo esta la categoría más rentable, lo que indica que hay una alta demanda de productos de este tipo entre nuestros clientes.
2.	Distribución de clientes: El 65% de los clientes compra frecuentemente nuestros productos. Esta categoría generó un ingreso de $741,279.86, lo que la convierte en la categoría más rentable, seguida por la categoría de clientes leales.
3.	Desempeño geográfico: El ingreso varía en gran proporción entre cada país, al menos 100,000 entre cada uno. Lo que significa que hay una gran oportunidad de mejora para USA y Colombia. Es importante notar que este resultado puede estar sesgado debido a que hay ingresos que no se atribuyen a ningún país en los datos proporcionados.
4.	Tendencias en ventas: Las ventas se mantuvieron estables en 2023, no hubo caídas o subidas pronunciadas. Entre mayo y agosto se registraron las ventas más altas, lo que sugiere un alza en la demanda durante los periodos vacacionales.
5.	Calidad de datos: Durante el análisis se encontrados dos principales problemas en los datos que requieren estandarización: 
  a. Hay ingresos en los que no se puede identificar el país del cual provienen, segando el análisis. 
  b. En análisis temporal corresponde únicamente 2023 ya que solo hay dos datos asociados otros años. Un análisis seccionado en meses por año podría dar un mejor panorama de las tendencias y el estado actual del comercio.


### Recomendaciones
Basandonos en los insights hacemos las siguientes recomendaciones: 

-	Considerar mejoras en el servicio que generen un crecimiento en el número de clientes leales. El segmento de clientes frecuentes genera muchas ganancias y es una gran oportunidad para obtener una mayor cantidad de clientes leales, tener una mayor cantidad de clientes leales contribuye a la estabilidad de un negocio.
-	Crear más publicidad para las demás categorías de productos y proporcionar datos de más fechas. Conociendo las tendencias a lo largo de distintos años podríamos determinar que productos se venden más en distintas temporadas del año, creando campañas publicitarias que se encarguen de maximizar las ganancias en cada periodo.
-	Mejorar la calidad geográfica de los datos para obtener un análisis más certero. Este análisis sugiere que México es el país que mejor se desempeña pero que en los demás países fluctúa demasiado el ingreso.

### Habilidades mostradas
- SQL JOINs
- Análisis KPI
- Segmentación de clientes
- Limpieza de datos 
- Visualizacion de datos 
- Business Storytelling
- Análisis de bases relacionales
