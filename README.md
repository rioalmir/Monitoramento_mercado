# Monitoramento de Mercado em Tempo Real

## Descrição
Este projeto realiza o monitoramento de cotações em tempo real de ativos negociados na B3 (Bolsa de Valores do Brasil) utilizando Python. O código se conecta diretamente à B3, coleta dados de cotações ao vivo e oferece ferramentas para monitorar, visualizar e processar essas informações.

## Funcionalidades

* Conexão com a B3: Coleta de cotações em tempo real de ações, moedas, e outros ativos listados na Bolsa.
* Atualização contínua: As cotações são atualizadas automaticamente ao longo do dia de negociação.
* Visualização de dados: Gráficos de desempenho de ativos em tempo real.
* Alertas customizados: Notificações quando um ativo atinge um valor predeterminado ou sofre uma variação significativa.

## Tecnologias Utilizadas

* Python: Linguagem utilizada para realizar a coleta e análise dos dados.
* Websockets: Para conexão em tempo real com os serviços de dados da B3.
* Pandas: Para manipulação de dados financeiros.
* Matplotlib/Seaborn: Para visualização gráfica das cotações.

## Pré-requisitos

* Python 3.8+
* Biblioteca websockets para conexão com a B3.
* Biblioteca pandas para tratamento dos dados.
* Biblioteca matplotlib ou seaborn para gráficos.
