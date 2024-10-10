# Desafio-1-DNC---Power-BI
Desafio 1 - Prevendo resultados de um e-commerce com Power BI

Desafio de Power BI: Previsão de Faturamento para E-commerce
Este repositório contém o projeto de previsão de faturamento e análise de dados de um e-commerce, desenvolvido com Power BI. O desafio consiste em utilizar dados reais de vendas e clientes para criar um painel gerencial que permita prever os resultados de faturamento e gerar recomendações estratégicas para melhorar o desempenho da empresa.

Objetivos do Projeto
Neste desafio, foram abordados os seguintes objetivos:

Previsão de Faturamento: Desenvolver um modelo de regressão linear para prever o faturamento futuro com base em dados históricos.
Análise de Vendas: Construir um painel interativo com métricas essenciais como quantidade total de vendas, valor total de vendas, vendas por data e por categoria de produto.
Recomendações Estratégicas: Fornecer sugestões para alavancar os resultados da empresa, utilizando insights obtidos a partir da análise dos dados.
Storytelling e Visualização: Criar um layout visualmente atrativo e com storytelling eficaz para facilitar a exploração dos dados pelos analistas.
Estrutura do Projeto
Este projeto foi dividido em duas páginas principais no Power BI, proporcionando uma visão completa sobre as vendas e o comportamento dos clientes:

1. Página de Vendas
Métricas Gerais: Quantidade total e valor total de vendas.
Análise Temporal: Vendas por data (quantidade e valor).
Análise por Categoria: Vendas agrupadas por categorias de produtos.
Filtros Interativos: Filtros por canal de venda, bandeira de pagamento, estado e data de compra.

2. Página de Previsões
Modelo de Regressão Linear: Previsão de faturamento futuro com base em dados históricos.
Análise por Segmentos: Insights sobre comportamento de compra por faixa etária e renda dos clientes.
Recomendações Estratégicas: Sugestões de melhorias no modelo de vendas para maximizar o faturamento.

Fontes de Dados
O projeto foi desenvolvido utilizando duas fontes principais de dados:

1. Base de Compras (base_compras.csv)
Contém dados detalhados das transações de venda realizadas no e-commerce, com colunas como:

idcompra: Número de identificação da compra.
idcanalvenda: Canal de venda.
bandeira: Bandeira de pagamento utilizada.
data: Data da compra.
preço: Valor da compra.
preço_com_frete: Valor da compra incluindo o frete.
nome_departamento: Departamento ou categoria do produto.
estado: Estado onde a compra foi realizada.

2. Base de Clientes (base_clientes.csv)
Contém informações sobre os clientes do e-commerce:

cliente_log: Identificação do cliente.
idade: Idade do cliente.
uf_nascimento: Estado de nascimento do cliente.
renda: Renda estimada do cliente.

Ferramentas Utilizadas
Power BI Desktop: Para criação do painel gerencial, aplicação do modelo de regressão linear e visualizações interativas.
DAX: Para cálculo de métricas e manipulação de dados dentro do Power BI.

Como Acessar o Projeto
Baixe o arquivo Power BI (.pbix) disponível neste repositório.
Abra o arquivo no Power BI Desktop para explorar o painel completo.
Utilize os filtros interativos para analisar as vendas por diferentes períodos, categorias e perfis de clientes.

Conclusão
Este projeto demonstra a aplicação de técnicas de análise de dados e modelagem preditiva para auxiliar na tomada de decisões estratégicas em um e-commerce. As visualizações interativas e as previsões fornecem uma visão clara do desempenho atual e do potencial futuro do negócio.

Licença
Este projeto está disponível sob a licença MIT. Fique à vontade para explorar, modificar e utilizar os insights deste repositório.
