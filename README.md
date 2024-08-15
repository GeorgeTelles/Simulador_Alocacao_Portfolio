<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# Simulador de Alocação de Portfólio

Este projeto em Python visa fornecer uma ferramenta para a alocação e análise de portfólios de investimentos. Através deste simulador, é possível carregar dados históricos de ativos financeiros, calcular retornos, e visualizar o desempenho do portfólio ao longo do tempo. 

## Funcionalidades

- **Carregar Dados do Yahoo Finance**: Utiliza a biblioteca `yfinance` para obter dados financeiros históricos diretamente do Yahoo Finance.
- **Calcular Retorno Acumulado**: Determina o retorno acumulado dos ativos ao longo do tempo.
- **Determinar Peso de Cada Ativo**: Calcula o peso de cada ativo no portfólio com base na alocação desejada.
- **Determinar Capital a Ser Alocado**: Define o valor total a ser investido e aloca-o entre os ativos com base em seus pesos.
- **Simular Posição de Cada Ativo ao Longo do Tempo**: Simula a evolução dos ativos no portfólio ao longo do período selecionado.
- **Visualizar a Evolução do Portfólio**: Gera gráficos para visualizar a performance do portfólio ao longo do tempo.
- **Estatísticas do Portfólio**: Calcula e exibe estatísticas importantes do portfólio, como retorno médio, volatilidade, e outros indicadores financeiros.
- **Exportação dos Dados do Portfólio**: Permite exportar os dados do portfólio para análise adicional ou relatórios.

## Bibliotecas Utilizadas

- `pandas`: Para manipulação e análise de dados.
- `numpy`: Para cálculos numéricos.
- `yfinance`: Para acesso a dados financeiros do Yahoo Finance.
- `seaborn`: Para visualização de dados estatísticos.

