# Dash_Invest
Código que faz Raspagem de dados e elabora Dash de Investimento no google sheets

<a href = 'https://docs.google.com/spreadsheets/d/1IQ1x7cYGtm9gxZbsfdT3CjX465h1mHFIVi6AAOYBF_k/edit?usp=sharing'>Dash Invest Final</a>

# Resumo do Projeto

Este projeto realiza a raspagem e análise de dados de várias fontes financeiras, incluindo:

- **Ocean11**, **Invest10** e **Status Invest**: Raspagem de dados de sites de investimento para obter informações detalhadas sobre ações, fundos e indicadores financeiros.
- **API do Fundamentus**: Extração de dados fundamentais diretamente da API do site Fundamentus, facilitando o acesso a indicadores de empresas listadas na bolsa.
- **Yahoo Invest**: Uso do `yfinance` para obter cotações e históricos de preços de ações.

## Funcionalidades Principais

1. **Raspagem de Dados**: Coleta automática de informações dos sites mencionados, estruturando os dados para análise.
2. **Análise de Dados**: Processamento e formatação dos dados raspados para gerar insights sobre o mercado financeiro.
3. **Geração de Relatórios**: Criação de arquivos Excel contendo os dados analisados, prontos para exportação.
4. **Integração com Google Sheets**: Envio dos relatórios para o Google Sheets, onde um **dashboard automatizado** é gerado com gráficos que facilitam a visualização dos resultados.
5. **Automatização**: O código permite atualizações periódicas dos dados e gráficos de forma automatizada, mantendo o dashboard sempre atualizado.

## Tecnologias Utilizadas

- **Python**: Para raspagem de dados e análise.
- **Selenium & BeautifulSoup**: Para a raspagem dos sites.
- **yfinance**: Para obter dados do Yahoo Invest.


