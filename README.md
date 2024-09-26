# Dataset Estructura - Información de Cryptomonedas por Clasificacion

Este dataset contiene información detallada sobre varias criptomonedas, incluyendo sus características generales, redes sociales en las que están presentes, y datos históricos relacionados con eventos de **Halving**. La estructura del dataset se detalla a continuación:

## Estructura del Dataset principal

| **Columna**                          | **Significado**                                                                                                 |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------|
| **Ranking**                          | Posición del token en el mercado de criptomonedas, generalmente basado en la capitalización de mercado.          |
| **Name**                             | Nombre completo del token o criptomoneda.                                                                       |
| **Token**                            | Símbolo o abreviatura del token (por ejemplo, BTC para Bitcoin).                                               |
| **Price**                            | Precio actual del token en el mercado, expresado en la moneda correspondiente (por ejemplo, USD).              |
| **One_Hour_Percentage**             | Cambio porcentual en el precio del token en la última hora.                                                    |
| **TwentyFour_Hour_Percentage**      | Cambio porcentual en el precio del token en las últimas 24 horas.                                             |
| **Seven_Days_Percentage**           | Cambio porcentual en el precio del token en los últimos 7 días.                                                |
| **Market_Cap**                      | Capitalización de mercado del token, calculada como el precio del token multiplicado por el suministro circulante. |
| **URL**                             | Dirección web del recurso en la plataforma CoinMarketCap  |
|**socialNetworks**| Lista de todas las redes sociales asociadas al token |
|**socialNetworksCount**| Suma del total de redes sociales asociadas al token |
| **Volume_24h**                      | Volumen total de transacciones del token en las últimas 24 horas.                                             |
| **Circulating_Supply**              | Cantidad de tokens que están actualmente en circulación y disponibles para el comercio.                        |
| **Total_Supply**                    | Total de tokens que existen, incluyendo los que están en circulación y los que no.                             |
| **Max_Supply**                      | Máximo número de tokens que se crearán, si es que hay un límite definido para el token. (Valores nulos significan que el máximo no esta verificado o no tiene limite)                     |
| **Class**                           | Clasificación del token en una categoría específica (0: IA, 1: Gaming, 2: RWA, 3: Meme).                       |
| **Halving_1_RankIndex**             | Ranking del token durante el primer halving de Bitcoin, indicado como un índice para concatenar. (Valores nulos significan que no vivieron esa fecha)                                |
| **Halving_1_Plus250_RankIndex**     | Ranking del token 250 días después del primer halving de Bitcoin, indicado como un índicepara concatenar. (Valores nulos significan que no vivieron esa fecha)                       |
| **Halving_2_RankIndex**             | Ranking del token durante el segundo halving de Bitcoin, indicado como un índicepara concatenar. (Valores nulos significan que no vivieron esa fecha)                                 |
| **Halving_2_Plus250_RankIndex**     | Ranking del token 250 días después del segundo halving de Bitcoin, indicado como un índice para concatenar. (Valores nulos significan que no vivieron esa fecha)                      |
| **Halving_3_RankIndex**             | Ranking del token durante el tercer halving de Bitcoin, indicado como un índice para concatenar. (Valores nulos significan que no vivieron esa fecha)                                  |
| **Halving_3_Plus250_RankIndex**     | Ranking del token 250 días después del tercer halving de Bitcoin, indicado como un índice para concatenar. (Valores nulos significan que no vivieron esa fecha)                        |
| **Halving_4_RankIndex**             | Ranking del token durante el cuarto halving de Bitcoin, indicado como un índice para concatenar. (Valores nulos significan que no vivieron esa fecha)                                 |
| **Capture_Date**                    | Fecha en la que se capturaron los datos de las criptomonedas.                                                 |
| **halving_survive**                    | Indicdor si vivio un halving anteriormente. (0:No vivio, 1: Si vivio)                                            |


## Estructura del Dataset para Halving
Fecha de extracción para los distintas fechas (Más proximas al halving):

halving_1.csv:  (28/04/2013)
halving_1._plus250.csv:  (11/08/2013)

halving_2.csv: (03/07/2016) 
halving_2._plus250.csv: (19/03/2017)  

halving_3.csv: (03/05/2020) 
halving_3._plus250.csv:  (10/01/2021) 

halving_4.csv: (21/03/2024)


| **Columna**                   | **Significado**                                                                                                 |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------|
| **Rank**                      | Posición del token en el mercado de criptomonedas, generalmente basado en la capitalización de mercado.          |
| **Name**                      | Nombre completo del token o criptomoneda.                                                                       |
| **Symbol**                    | Símbolo o abreviatura del token (por ejemplo, BTC para Bitcoin).                                               |
| **Price**                     | Precio actual del token en el mercado, expresado en la moneda correspondiente (por ejemplo, USD).              |
| **Volume_24h**               | Volumen total de transacciones del token en las últimas 24 horas. (Valores nulos significan que no se registraron, comunmente en primeros halving)                                             |
| **Market_Cap**               | Capitalización de mercado del token, calculada como el precio del token multiplicado por el suministro circulante. |
| **Circulating_Supply**       | Cantidad de tokens que están actualmente en circulación y disponibles para el comercio.                        |
| **Total_Supply**             | Total de tokens que existen, incluyendo los que están en circulación y los que no.                             |
| **Max_Supply**               | Máximo número de tokens que se crearán, si es que hay un límite definido para el token. (Valores nulos significan que el máximo no esta verificado o no tiene limite)                       |
| **Percent_Change_1h**        | Cambio porcentual en el precio del token en la última hora. (Valores nulos significan que no se registraron, comunmente en primeros halving)                                                        |
| **Percent_Change_24h**       | Cambio porcentual en el precio del token en las últimas 24 horas. (Valores nulos significan que no se registraron, comunmente en primeros halving)                                               |
| **Percent_Change_7d**        | Cambio porcentual en el precio del token en los últimos 7 días. (Valores nulos significan que no se registraron, comunmente en primeros halving)                                                    |
| **Date_Added**               | Fecha en la que se añadió el token al mercado o a la base de datos.                                            |
| **Capture_Date**             | Fecha en la que se capturaron los datos de las criptomonedas.                                                 |

