# PySpark Sistema de Recomendação de Músicas

## Introdução
Este projeto implementa um sistema de recomendação de músicas utilizando PySpark.

## Tecnologias Utilizadas
- **PySpark**
- **PCA** (Análise de Componentes Principais)
- **KMeans** (Clusterização)
- **Spotipy API** (Integração com o Spotify)

## Metodologia
1. **Pré-processamento**: 
   - Limpeza e normalização dos dados para garantir a qualidade das informações utilizadas.
   
2. **Redução de Dimensionalidade**:
   - Aplicação de PCA para reduzir a dimensionalidade dos dados, facilitando a análise e processamento.
   
3. **Clusterização**:
   - Agrupamento de músicas similares utilizando o algoritmo KMeans.
   
4. **Recomendação**:
   - Cálculo da distância euclidiana entre as características musicais para identificar e recomendar músicas semelhantes.

## Spotipy
Para utilizar a biblioteca Spotipy, é necessário se cadastrar no [Spotify Developer](https://developer.spotify.com/dashboard/) para obter as credenciais de acesso.

## Resultados
O sistema recomenda músicas com base em características como energia, dança, acústica, e similaridade medida pela distância euclidiana.
