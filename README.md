The Tate Collection | Sotheby's
===================


## Repository Contents

##Sothebys & Tate Museum (in progress)

# Análise de Dados de Leilões da Sotheby's

Este projeto realiza uma análise detalhada dos dados de leilões de obras de arte da Sotheby's, utilizando dados como ano de criação, movimento artístico, condição da obra e preço. O objetivo é entender como esses fatores influenciam o valor das obras e identificar tendências de mercado.

## Estrutura do Projeto

Este repositório contém o código e a análise de um conjunto de dados de leilões de arte da Sotheby's, com o foco em entender os preços das obras e explorar características relacionadas a artistas, movimentos artísticos, e períodos de criação.

## Bibliotecas Usadas

- **Pandas**: Manipulação e análise de dados.
- **Matplotlib e Seaborn**: Visualização de dados.
- **Numpy**: Operações numéricas e manipulação de arrays.

## Jupyter Notebook

### Descrição do Processo de Análise

1. **Importação e Carregamento dos Dados**  
   O primeiro passo envolve a importação das bibliotecas necessárias e o carregamento do dataset, que contém informações como o preço das obras, artistas, e período de criação.

2. **Pré-processamento dos Dados**  
   O código realiza a limpeza e o tratamento de dados ausentes ou incorretos:
   - **Coluna 'price'**: Converte o preço para o tipo numérico.
   - **Coluna 'yearCreation'**: Trata valores não numéricos e converte para anos aproximados, além de lidar com valores nulos.
   - **Preenchimento de valores ausentes**: Substitui valores nulos por uma categoria padrão como 'Desconhecido' para as colunas de condição da obra e ano de criação.

3. **Análise Exploratória dos Dados**  
   Após o pré-processamento, são realizadas diversas análises exploratórias:
   - **Distribuição de preços**: Analisamos os preços das obras com gráficos de boxplot e histogramas.
   - **Preço médio por movimento artístico e período**: Calculamos e visualizamos o preço médio das obras com base no movimento artístico e no período de criação.
   - **Análise de vendas por ano**: Observamos o número de obras vendidas por ano e as tendências de mercado ao longo do tempo.
   - **Análise de artistas mais vendidos**: Identificamos os artistas que mais venderam obras e os que tiveram as obras mais caras.

4. **Visualização de Dados**  
   A visualização é feita com o uso de gráficos interativos e informativos:
   - **Boxplots** para análise de preços por período artístico.
   - **Gráficos de barras** para mostrar o número de obras vendidas por artista e o preço médio por movimento artístico.
   - **Gráficos de dispersão (scatter plots)** para analisar a relação entre o ano de criação e o preço das obras.

5. **Resultados**  
   Através das visualizações, conseguimos identificar tendências como:
   - O preço médio das obras por período artístico.
   - Artistas com obras mais caras desde 1990.
   - O aumento nas vendas de obras de artistas contemporâneos.

### Exemplos de Visualizações

1. **Boxplot**: Preço por Período Artístico
2. **Gráfico de Barras**: Preço Médio por Movimento Artístico
3. **Scatterplot**: Ano de Criação vs. Preço

## Contribuições

Contribuições são bem-vindas! Se você tem ideias para melhorar este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.


