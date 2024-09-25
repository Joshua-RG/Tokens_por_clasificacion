# Dataset Estructura - Información de Cryptomonedas por Clasificacion

Este dataset contiene información detallada sobre varias criptomonedas, incluyendo sus características generales, redes sociales en las que están presentes, y datos históricos relacionados con eventos de **Halving**. La estructura del dataset se detalla a continuación:

## Estructura del Dataset

### 1. **Ranking**
   - **Descripción**: El ranking global de la criptomoneda según su capitalización de mercado.
   - **Tipo de dato**: Entero

### 2. **Name**
   - **Descripción**: Nombre completo de la criptomoneda.
   - **Tipo de dato**: Texto

### 3. **Token**
   - **Descripción**: Abreviación o símbolo del token de la criptomoneda.
   - **Tipo de dato**: Texto

### 4. **Total Supply**
   - **Descripción**: Suministro total de la criptomoneda, es decir, el número total de monedas que existen.
   - **Tipo de dato**: Numérico

### 5. **Max Supply**
   - **Descripción**: El suministro máximo que puede ser creado. Si la criptomoneda no tiene un límite, puede estar vacío o marcado como infinito.
   - **Tipo de dato**: Numérico

### 6. **Social Networks**
   - **Descripción**: Las redes sociales en las que está presente la criptomoneda.
   - **Tipo de dato**: Lista de texto (separados por comas)

### 7. **Social Networks Count**
   - **Descripción**: El número de redes sociales en las que está presente la criptomoneda.
   - **Tipo de dato**: Entero

### 8. **Halving**
   - **Descripción**: Esta sección agrupa los datos históricos que se registran en cada evento de **Halving**. Para cada fecha de Halving, se han registrado los siguientes atributos:
     - **Price**: El precio de la criptomoneda en USD.
     - **Volume 24h**: El volumen negociado en las últimas 24 horas.
     - **Market Cap**: La capitalización de mercado de la criptomoneda.
     - **Percent Change 1h**: Cambio porcentual del precio en la última hora.
     - **Percent Change 24h**: Cambio porcentual del precio en las últimas 24 horas.
     - **Percent Change 7d**: Cambio porcentual del precio en los últimos 7 días.
     - **Circulating Supply**: El suministro circulante de la criptomoneda en el mercado.

   Cada uno de estos campos se repetirá por cada evento de Halving.
