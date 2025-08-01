# Modelo Cruce EMAs
Modelo de trading que prediga entradas de compra utilizando la estrategia de cruce de medias moviles exponenciales en este caso utilizaremos las EMA 20 y 50, funciona multitemporal y en cualquier activo, nos arrojara una señales de compra cuando la EMA de 20 incercepte de abajo hacia arriba la EMA de 50.
## Instalación de librerías
Instalaremos las librerías necesarias para obtener datos de mercado, como `yfinance`, y para el análisis y visualización, como `pandas`, `numpy` y `matplotlib`.
## Obtención de datos
Crearemos una función para descargar datos históricos de cualquier activo y en diferentes temporalidades utilizando `yfinance`.
## Cálculo de emas
Implementaremos una función para calcular las Medias Móviles Exponenciales (EMAs) de 20 y 50 períodos.
## Identificación de señales de compra
Desarrollaremos la lógica para identificar los cruces de la EMA de 20 por encima de la EMA de 50, que generarán las señales de compra.
## Visualización de resultados
Crearemos un gráfico que muestre el precio del activo, las EMAs y las señales de compra para una fácil interpretación.
