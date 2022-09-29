#Introducción: Criptomonedas.

*Una criptomoneda es algo similar a dinero digital con el cual podemos pagar una salida a un bar, comprar ropa, reservar vuelos/hoteles, etc. 
Como las criptomonedas son digitales, podemos transferirlas sin importar en qué parte del mundo estemos (similar a una transferencia bancaria, en realidad es mucho más interesante).
Los sistemas de pagos online que conocemos se encuentran centralizados en bancos y son ellos quienes tienen nuestro dinero. Con las criptomonedas, el sistema se descentraliza, desaparece el banco, lo que nos permite ser nuestro propio banco al estar en comunicación directa con otras personas sin intermediarios.
Para usar nuestras criptomonedas no necesitamos registrarnos en algún sitio web, usar un correo electrónico o una contraseña. Podemos descargar una amplia gama de aplicaciones en nuestro smartphone para enviar y recibir criptos en cuestión de minutos.

*¿Por qué se llaman criptomonedas?
El nombre de criptomonedas es la combinación entre criptografía y moneda. Con el uso de la criptografía se proporciona seguridad a la criptomoneda, asegurándonos de que nadie más a excepción de su propietario pueda usarla.

*¿Qué es Blockchain?
Blockchain es solamente una base de datos, podemos crearlo incluso en una hoja de cálculos. Existen algunas particularidades con estas BD.
Las blockchains son anexadores. Esto se refiere a que solo pueden añadir información, en otros términos, no podemos hacer clic en una celda que ya hemos agregado anteriormente para eliminarla o cambiarla.
Cada entrada (llamada un bloque) en la base de datos es encriptada hasta la última entrada. En otros términos, cada entrada nueva contiene una huella identificadora (hash) proveniente de la última.
Así como se registra cada huella en el último bloque, terminamos obteniendo una cadena de bloques consecutiva (blockchain).
Una blockchain es inmutable: Si alteramos un bloque, cambiamos la huella y dado que esa huella se marca en el próximo bloque, el siguiente bloque también sufre ese cambio y así el siguiente y así sucesivamente hasta que el último termina en un efecto dominó donde cualquier cambio que hagamos a la red queda en evidencia. No podemos alterar ninguna información de la cadena sin que todos los que estén dentro (y fuera) del ecosistema de criptomonedas se den cuenta.

#Desarrollo:

*Selección de 10 criptomonedas para el reporte.
En esta oportunidad  y de acuerdo a la consigna, trabajamos seleccionando 10 criptomonedas.
Para su elección tuve presente el listado de las principales 100 Criptomonedas por capitalización de mercado. Las elegidas fueron:
1.-Bitcoin (BTC)
2.-Ethereum (ETH)
3.-Tether (USDT)
4.-Solana (SOL)
5.-Dogecoin (DOGE)
6.-Dai (DAI)
7.-Polygon (MATIC)
8.-Shiba Inu (SHIB)
9.-TRON (TRX)
10.-Avalanche (AVAX)

*API de FTX (https://ftx.com)
Por consigna se debió trabajar directamente con conexión a la API de FTX para obtener información histórica y actual de las cotizaciones.
FTX es un intercambio de criptomonedas creado por comerciantes para comerciantes.
Realicé la conexión correspondiente a través de Power BI, obteniendo los datos de forma directa desde la web. 

*Dashboard en Power BI
Opté por presentar la información desde un Dashboard en Power BI. Tuve en cuenta lo siguiente:
**Evolución de los precios de cada moneda: No se realizó filtros por fechas. Consideré toda la información disponible en FTX, la cual correspondía a 3 años atrás (desde 2019 a la fecha). Para cada moneda tomé para el análisis el precio de baja, de alta, de apertura y de cierre. En el filtro de fechas consideré el mes, trimestre y año, a los fines de tener información relevante de tendencias.

**Gráfico de velas: Se definió presentar la evolución de los precios en el tiempo por medio de gráficos de velas, mejor conocidos como velas japonesas, puesto que muestran información detallada sobre las acciones del precio de activos. Las velas japonesas se usan ampliamente en el análisis técnico.
En este sentido, resulta imprescindible que cualquier trader que desee especializarse en la compra y venta de activos criptográficos, sepa cómo leer estos gráficos y pronosticar si el precio de una criptomoneda subirá o bajará próximamente. 
Todos los datos de un gráfico de velas se encuentran sobre un marco de tiempo, el cual visualiza las horas, días, meses o años en los que se registró la información. Adicional a estos datos, las velas japonesas son muy conocidas porque generan señales sobre el sentimiento que domina en un mercado o los posibles cambios en el precio de una criptomoneda.
Por ejemplo, gracias al color de una vela se puede saber si un activo está en tendencia alcista o bajista. Si estamos analizando el comportamiento de bitcoin y las últimas velas han sido verdes, entonces se puede decir que el precio de la moneda ha estado en alza y que los compradores dominan el mercado. Por este motivo mantuve en cada gráfico de vela los colores rojo y verde como indicadores de tendencia alcista y bajista respectivamente.

**Volumen de transacción:  El volumen de una criptomoneda es un indicador básico que se utiliza para el análisis técnico de una bolsa. El análisis técnico se trata de un conjunto de técnicas que tienen como objetivo predecir el precio o la tasa futura de un activo seleccionado (acción, criptomoneda, etc). 
El objetivo del análisis técnico es estimar los momentos óptimos de compra y venta para un inversor. 
El volumen de transacción es uno de los indicadores más importantes para el análisis técnico del mercado, que representa la actividad de los operadores -compra y venta de criptodivisas- en un marco temporal determinado. En esta oportunidad para seleccionar las fechas tomé los mismos criterios que para la evolución de los precios.


**Media móvil: Se trata de una medida del precio en un periodo concreto de un activo. De este modo, podemos ver la tendencia en el precio con más claridad, a pesar de ser un indicador que se forma con retraso, y por tanto, no se anticipa al movimiento del mercado.

**Varianza: La varianza es una medida de dispersión que representa la variabilidad de una serie de datos respecto a su media. Formalmente se calcula como la suma de los residuos al cuadrado divididos entre el total de observaciones. Power BI permite su cálculo directo generando una medida.

En el dashboard confeccionado al filtrar por un período específico se pueden apreciar en simultáneo la tendencia de los precios, volumen de transacción, precio promedio y varianza.

**Calculadora de conversión: Para cada criptomoneda se confeccionó una calculadora que permite realizar la conversión de un valor a dolares y viceversa.

#Conclusiones:

Realizar el trabajo de referencia me permitió conocer conceptos básicos en relación a las criptomonedas, esta tecnología plantea la posibilidad de un sistema financiero descentralizado. Su uso está creciendo exponencialmente, funcionando las 24 horas , es anónimo y transparente.
 
Desde la Ciencia y el análisis de datos podemos brindar información clave a inversores interesados para que puedan conocer la tendencia de las diferentes monedas y  los momentos óptimos para la compra y la venta, así como los riesgos asociados. 