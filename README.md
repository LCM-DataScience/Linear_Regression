🔭 Análise de criptomoedas com regressão linear simples e múltipla

- Como você usa a análise de regressão linear para prever movimentos no mercado financeiro?

 

Fiz uma análise de criptomoedas utilizando regressão linear simples e múltipla, com foco na relação entre a variação percentual diária de diferentes criptomoedas. A análise foi realizada com dados de: Bitcoin (BTC), Ethereum (ETH), Tether (USDT), Solana (SOL), USD Coin (USDC), Ripple (XRP) e Tron (TRX). Os dados foram coletados de janeiro de 2021 até julho de 2024.

 

⦿ Regressão Linear Simples:

Inicialmente, apliquei a regressão linear simples para analisar a relação entre BTC e ETH. Com a inclusão de outliers, o modelo revelou uma forte correlação positiva com um 'R²' de aproximadamente 0.66, indicando que cerca de 66% da variação em ETH pode ser explicada pela variação em BTC. Após a remoção dos outliers, o modelo apresentou uma leve diminuição no 'R²' para 0.53, mostrando outliers influenciam a relação entre essas duas criptomoedas.

 

⦿ Regressão Linear Múltipla:

Com as outras criptomoedas sendo preditoras para a variação do ETH, a regressão linear múltipla revelou que o BTC continua sendo o principal influenciador do preço do ETH, com coeficiente de 0.7299, seguido por SOL e TRX, que também tiveram coeficientes significativos. O modelo múltiplo atingiu um 'R²' de 0.715, demonstrando que 71.5% da variação do ETH pode ser explicada pelas outras criptomoedas incluídas no modelo.

 

⦿ Matriz de Correlação

Como complemento, criei uma matriz de correlação que mostra as relações entre as criptomoedas deste estudo. BTC e ETH apresentaram a maior correlação (0.81), confirmando os resultados da regressão. O USDC e o USDT mostraram pouca correlação com as outras criptomoedas, o que era esperado devido à sua natureza como stablecoins.
