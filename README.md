# Analyze Covid19 infections
Analysis of the growth of cases of Covid-19 infection in Brazilian states - Data analysis (PT-BR)

## Objetivo
Se trata de um projeto de analise dos dados e insigths, sobre os relatórios de infectados por COVID19 nos estados do Brasil.

*Ciclo 1 - analise dos dados de 25/02/2020 ate 17/11/2020

*Ciclo 2 - analise dos dados de 25/02/2020 ate 22/11/2022 (em desenvolvimento)

## Resumo do desenvolvimento
Dados filtrados e coletados do projeto Brasil.IO, obtendo diversas informações divididas por estado como, quantidade acumulada de infectados, quantidade de mortes, população estimada, infectados por 100mil habitantes, mortes por 100mil habitantes.

Após a coleta dos dados, esta planilha e importada para o jupyter notebook onde os dados são tratados, como repetindo as mesmas medidas do dia anterior quando não houve relato (tratamento de NAs), verificando relação das variáveis de maneira global entre outros. 

Lentadas e verificadas hipóteses como ''Os estados mais populosos também tiveram as maiores taxas de infecção durante o período analisado.'' , ''A relação de óbitos e infectados e proporcional.''. 

Como um extra, inclui uma pequena ferramenta para análise de possíveis cenários utilizando o modelo matemático SIR de análise de infecções pandêmicas.

## Conclusão
Podemos observar padrões de infecção de acordo com densidade demográfica de cada estado, porem também e possível verificar que isso não e o único fator havendo causas não abordadas neste projeto como aderência ao uso de proteções a infecções e a qualidade da saúde pública.

E possível utilizar os gráficos contidos neste projeto como rápida verificação sobre a evolução dos casos tanto de contagio como de óbitos, por estado.

Para o próximo ciclo do projeto (ciclo 2) além de atualizar a base para um periodo maior da pandemia pretendo refatorar os gráficos para melhor visualização e possivelmente criar um dashboard interativo utilizando o software Power BI. 

