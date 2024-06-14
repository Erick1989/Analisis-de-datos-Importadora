# Analisis-de-datos-Importadora
# Data-Analyst-Portafolio
Los siguientes son mis proyectos en Excel y RStdio

Este repositorio contiene el proyecto de una importadora. Este proyecto se encuentra modelados en documento en Excel y el proyecto de ingeniería de Datos, ciencia de datos, limpieza y transformación de datos, visualización de datos 

## Tabla de Contenido
### Proyecto de la Empresa de Importación
- Limpieza y Transformación de Datos
- Análisis de Datos
- Visualización de Datos
- Ciencia de datos
- Análisis de ventas descriptivo
- Análisis de descriptivo de asesores
- Análisis de distribución de probabilidad
- Análisis predictivo
- Promedio móvil
- Promedio móvil ponderado
- Suavización Exponencial
- Tendencias 

  
## La empresa de Importaciones necesita realizar un análisis sobre las ventas mensuales del año 2022 . (EXCEL)
La empresa de importaciones necesita evaluar las ventas del año 2022 con el fin de verificar el rendimiento y el crecimiento que ha tenido durante el año 2022 y poder determinar el rendimiento de ventas de los asesores.
Por ello se necesita lo siguiente:
- Realizar una limpieza y transformación de datos de los años descritos en la data.
- Realizar un análisis de las ventas, tipo de servicio, ventas por asesor comercial y linea de servicios.
- Realizar graficos dinamicos para tener una mejor visualización de los datos
- Realizar un análisis descriptivo de ventas y asesores comerciales.
- Realizar un análisis de probabilidad sobre los minimos de ventas asi como el máximo de ventas.
- Realizar una proyección de ventas por medio de promedios (móvil, Promedio móvil ponderado, Suavización exponencial).
- Realizar un análisis para las ventas del año 2023.

### Primer Paso
- Revisión de datos de la pestaña Data.
- Seleccionar de la columna A hasta la AG para insertar varias tablas dinamicas en una hoja nueva.
- Instar tabla dinamica de las ventas mensulases.
- En la misma hoja de tabla dinamica crear una TD por tipo de servicio e ingresos.
- Crear una TD por tipo de servicios y servicios brindados.
- Crear una TD por asesor comercial y las ventas realizadas.
- Crear una TD de lina de servicios, cantidad de fletes y valor del flete.

### Segundo Paso
- Insertar graficos por cada tabla dinamica para tener una mejor vizualización de datos.
- Análisis de cada grafico para evaluar los meses con mayores ventas y menores ventas.
- Análisis del grafico de las lineas de negocio.
- Análisis por medio del grafico el asesor con mayor ventas y el asesor con las menores ventas.
  
### Tercer Paso
- Copiar los gráficos en una hoja nueva para poder tener una mejor vizualización de todos los datos.
- Entrelazar los graficos para que se vuelvan dinamicos.
- Por medio de la segmentación de datos (en la herramienta analisis de gráfico dinámico) crear una segmentación del tiempo (fecha).
- En la herramienta de tabla dinamica insertar la segmentación de datos Fecha lo facturado, tipo de servicio y asesor comercial.
- En la herramienta de exel DATOS seleccionar análisis de datos, en la ventana desplegada seleccionar estadística descriptiva de la tabla dinamica ordenada por mes y el valor de la venta.  
- En el misma hoja insertar el analisis, en el rango de entrada insertar el valor de la venta mensual (B7 a B18)
- Realizar un analisis de los resultados: Promedio de ventas, error típico, la mediana, Desviación estándar,Varianza de la muestra, Coeficiente de asimetría, Mínimo, Máximo.
- Crear una nueva pestaña y realizar el En la herramienta de exel DATOS seleccionar análisis de datos, en la ventana desplegada seleccionar Histrograma ingresar en clases los rangos frecuencia o rango de los taso y el valor de la venta.
- Crear una nueva pesataña para realizar el análisis del asesor comercial en la herramienta de exel DATOS seleccionar análisis de datos, en la ventana desplegada seleccionar estadística descriptiva de la tabla dinamica ordenada por asesor comercial y el valor de la venta por asesor.
- En la misma hoja con la herramienta de exel DATOS seleccionar análisis de datos, en la ventana desplegada seleccionar Histrograma ingresar en clases los rangos frecuendica o rango de los asesores comerciales y la venta por asesores comerciales.
  
### Cuarto Paso
- Instalar un complemento en excel Excel QM v5.3 para poder realizar las probabilidades de ventas.
- En el exel se agrega una nueva herramienta llamada QM en la herramienta seleccionar Normal Dist Calculator
- En la herramienta ingresar seleccionar Probability given value,  en la pestaña Mean ingresar el promedio de la venta (obtenida del análisis descriptivo), en la siguiente pesataña seleccionar la desviación estandar (ingresar la desviación estandar obtenido del análisis descriptivo), Seleccionar la venta esperara para el año 2023 ingresar el dato en Value cutoff el valor de la venta esperada seleccionar un corte y brindara la probabilidad. En la parte se puede seleccionar si se necesita que sea a un corte o a dos cortes en la campana de gauss para ver si toma solo un extremo o ambos extremos esto de acorde a las probabilidades que se quieran analizar de las ventas esperadas cual seria la minima venta esperada y cual seria la maxima venta esperada.
- Para evaluar las probabilidades de venta con un nivel de confianza del 70% se puede utilizar la formula INTERVALO.CONFIANZA.T con los datos estimados, Confianza (alfa) Media, Desviacion estandar, tamaño de la muestra en este caso es de 9 asesores se puede evaluar el máximo y el mínimo.
- En la herramienta Alphabetical, seleccionar Forecasting
- Para el promedio movil seleccionar Moving Average Including Naive (crear 12 periodos que son las ventas a evaluar) Se crea una nueva pesataña donde se ingresa el valor de las ventas y brindara el promedio de movil de las ventas.
- Para el Promedio movil ponderado Seleccionar Weighted Moving Average (crear 12 periodos y 3 pesos a evaluar) se crea una nueva pesataña donde se ingresa el valor de las ventas y brindara el promedio de movil Ponderado de las ventas.
- Para Suavización Exponencial Seleccionar Exponential Smoothing (crear 12 periodos que son las ventas a evaluar) se crea una nueva pesataña donde se ingresa el valor de las ventas y brindara la Suavización Exponencial de las ventas
- Para realizar una proyección de las ventas esperadas para el primer trimiestre por el método Tendencia-desestacionalización En la herramienta Alphabetical, seleccionar Forecasting (crear 12 periodos y 3 Season para evaluar la proyeccion del primer trimestre)

#### Análisis: De acuerdo a los datos la empresa de importación son los siguientes:
- Según los datos analizados, los meses con mayores niveles de ventas durante el año 2022 fueron en agosto y septiembre.
- Las ventas por línea de negocio de Courier consolidado representan el 81% del total de ventas anuales.
- La línea de negocio principal es la de Courier consolidado, los clientes prefieren consolidar sus importaciones para reducir costos de transporte.
- Se observa que Barbie Guzman tiene un alto nivel de ventas, se estima que cuenta con la cartera de clientes con mayor nivel de importaciones.
#### Análisis descriptivo de las ventas:
- Media	 Q3,195,096.38 	El promedio de ventas durante el 2022 fue de Q3,195,096.38	
- Error típico	197785.98	El error típico muestra que no hubo una diferencia significativa	
- Mediana	 Q3,095,210.65 	El punto medio de las ventas durante el año 2022 es de Q3,095,210.65, que equivale el 50% bajo o sobre	
- Moda	#N/D	No interpretar.	
- Desviación estándar	 Q685,150.74 	La variación de las ventas con respecto a la media fue de +/- Q685,150.74	
- Varianza de la muestra	469431532760.78	No es representativo para la toma de decisiones	
- Curtosis	4.0022133934	Leptocúrtica	
- Coeficiente de asimetría	1.656987418	Curva de asimetría positiva	
- Rango	 Q2,656,427.94 	La diferencia entre el valor menor y el valor mayor fue de Q2,656,427.94	
- Mínimo	 Q2,331,450.60 	El mes con ventas más bajas fue mayo con Q2,331,450.60	
- Máximo	 Q4,987,878.54 	El mes con ventas más altas fue agosto con Q4,987,878.54	
- Suma	 Q38,341,156.50 	El total de ventas durante el año 2022 fue de Q38,341,156.50	
- Cuenta	12	El total de meses analizados fueron 12
#### Análisis descriptivo Asesores:
- Media	 Q4,260,128.50 	El promedio de ventas de todo el equipo comercial fue de Q4,260,128.50
- Error típico	 Q3,502,372.32 	El error típico muestra que hubo una diferencia significativa
- Mediana	 Q56,242.32 	El punto medio de las ventas de todo el equipo comercial es de Q56,242.32, que equivale el 50% bajo o sobre
- Moda	#N/D	No interpretar.
- Desviación estándar	 Q10,507,116.97 	La variación de las ventas con respecto a la media fue de +/- Q10,507,116.97
- Varianza de la muestra	110399506963240.00	No es representativo para la toma de decisiones
- Curtosis	8.61	Leptocúrtica
- Coeficiente de asimetría	2.918578398	Curva de asimetría positiva
- Rango	 Q32,070,605.97 	La diferencia entre el valor menor y el valor mayor fue de Q32,070,605.97
- Mínimo	 Q67.20 	Las ventas más bajas corresponden al asesor Kristel Valdez con un total de Q67.20
- Máximo	 Q32,070,673.17 	Las ventas más altas corresponden al asesor Barbie Guzmán con un total de Q32,070,673.17
- Suma	 Q38,341,156.50 	El total de las ventas de todo el equipo comercial fue de Q38,341,156.50
- Cuenta	9	El total de asesores analizados fueron 9
#### Análisis Probabilidades:
- La probabilidad que las ventas sean mayores a Q3.500,000.00 para el año 2023 es de un 32.82%
- Se estima que el asesor puede vender para el año 2023 un mínimo de Q 378,990.56 y un máximo de Q 8.141,266.44 con un nivel de confianza del 70%.
- La probabilidad de obtener un nivel de ventas entre Q2.000,000.00 y 4.000,000.00 es del 83.94%.
#### Análisis Proyecciones:
- Según la proyección, se estima que para enero 2023 las ventas serán entre Q.3,030,687.89 y 2,989,648.50
- Según la proyección para el próximo trimestre el crecimiento es positivo, sin embargo, enero 2023 se proyecta más bajo que enero del año 2022.
  
#### Calcular medidas de resumen estadístico 
summary_stats <- infobox_clean %>% 
 summarise( 
 Mean = mean(NumericValue), 
 Median = median(NumericValue), 
 SD = sd(NumericValue), 
 Min = min(NumericValue), 
 Max = max(NumericValue) 
