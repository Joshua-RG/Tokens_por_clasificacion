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
| **Volume_24h**                      | Volumen total de transacciones del token en las últimas 24 horas.                                             |
| **Circulating_Supply**              | Cantidad de tokens que están actualmente en circulación y disponibles para el comercio.                        |
| **Total_Supply**                    | Total de tokens que existen, incluyendo los que están en circulación y los que no.                             |
| **Max_Supply**                      | Máximo número de tokens que se crearán, si es que hay un límite definido para el token.                       |
| **Class**                           | Clasificación del token en una categoría específica (por ejemplo, IA, Gaming, RWA, Meme).                       |
| **Halving_1_RankIndex**             | Ranking del token durante el primer halving de Bitcoin, indicado como un índice para concatenar.                                |
| **Halving_1_Plus250_RankIndex**     | Ranking del token 250 días después del primer halving de Bitcoin, indicado como un índicepara concatenar.                     |
| **Halving_2_RankIndex**             | Ranking del token durante el segundo halving de Bitcoin, indicado como un índicepara concatenar.                               |
| **Halving_2_Plus250_RankIndex**     | Ranking del token 250 días después del segundo halving de Bitcoin, indicado como un índice para concatenar.                    |
| **Halving_3_RankIndex**             | Ranking del token durante el tercer halving de Bitcoin, indicado como un índice para concatenar.                                |
| **Halving_3_Plus250_RankIndex**     | Ranking del token 250 días después del tercer halving de Bitcoin, indicado como un índice para concatenar.                     |
| **Halving_4_RankIndex**             | Ranking del token durante el cuarto halving de Bitcoin, indicado como un índice para concatenar.                                |
| **Capture_Date**                    | Fecha en la que se capturaron los datos de las criptomonedas.                                                 |


## Estructura del Dataset para Halving

| **Columna**                   | **Significado**                                                                                                 |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------|
| **Rank**                      | Posición del token en el mercado de criptomonedas, generalmente basado en la capitalización de mercado.          |
| **Name**                      | Nombre completo del token o criptomoneda.                                                                       |
| **Symbol**                    | Símbolo o abreviatura del token (por ejemplo, BTC para Bitcoin).                                               |
| **Price**                     | Precio actual del token en el mercado, expresado en la moneda correspondiente (por ejemplo, USD).              |
| **Volume_24h**               | Volumen total de transacciones del token en las últimas 24 horas.                                             |
| **Market_Cap**               | Capitalización de mercado del token, calculada como el precio del token multiplicado por el suministro circulante. |
| **Circulating_Supply**       | Cantidad de tokens que están actualmente en circulación y disponibles para el comercio.                        |
| **Total_Supply**             | Total de tokens que existen, incluyendo los que están en circulación y los que no.                             |
| **Max_Supply**               | Máximo número de tokens que se crearán, si es que hay un límite definido para el token.                       |
| **Percent_Change_1h**        | Cambio porcentual en el precio del token en la última hora.                                                    |
| **Percent_Change_24h**       | Cambio porcentual en el precio del token en las últimas 24 horas.                                             |
| **Percent_Change_7d**        | Cambio porcentual en el precio del token en los últimos 7 días.                                                |
| **Date_Added**               | Fecha en la que se añadió el token al mercado o a la base de datos.                                            |
| **Capture_Date**             | Fecha en la que se capturaron los datos de las criptomonedas.                                                 |

