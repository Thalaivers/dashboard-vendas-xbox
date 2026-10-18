# Dashboard de Vendas — Xbox Game Pass

## Sobre o projeto

Este projeto foi desenvolvido como parte dos desafios práticos de análise de dados com Excel da DIO.

O objetivo é transformar uma base de dados de assinaturas do Xbox Game Pass em informações visuais que facilitem a análise de vendas, receitas e adesão aos serviços adicionais.

O dashboard foi construído no Excel, com dados organizados em uma base estruturada e análises auxiliares para apoiar a visualização dos resultados.

## Objetivos do projeto

- Organizar os dados de assinaturas em uma base estruturada.
- Analisar os valores associados aos diferentes planos de assinatura.
- Comparar os resultados de acordo com a renovação automática.
- Analisar as vendas de serviços adicionais, como EA Play e Minecraft.
- Apresentar informações relevantes em um dashboard para facilitar a interpretação dos dados.

## Estrutura do arquivo

O arquivo Excel está dividido em quatro abas:

### 1. Assets

Reúne elementos de apoio visual do projeto, como a paleta de cores e referências utilizadas na identidade visual do dashboard.

### 2. Bases

Contém a base de dados utilizada nas análises, com informações como:

- Identificador do assinante;
- Nome;
- Plano contratado;
- Data de início da assinatura;
- Renovação automática;
- Preço da assinatura;
- Tipo de assinatura;
- Adesão e preços de adicionais do EA Play;
- Adesão e preços de adicionais do Minecraft;
- Valor de cupom;
- Valor total.

Essa base serve como fonte para a elaboração das análises e visualizações.

### 3. Cálculos

Reúne tabelas dinâmicas e resultados utilizados para responder às perguntas de negócio do projeto.

As análises estão relacionadas a:

- Faturamento das assinaturas;
- Comparação de valores por renovação automática;
- Vendas do adicional EA Play por plano;
- Vendas do adicional Minecraft por plano.

Essa aba funciona como uma etapa intermediária entre a base de dados e a apresentação visual dos resultados.

### 4. Dashboard

É a área destinada à apresentação visual dos indicadores e das análises de vendas do Xbox Game Pass.

A proposta é permitir que os resultados sejam consultados de forma organizada, facilitando a identificação de diferenças entre planos e serviços adicionais.

## Dados utilizados

Os dados estão armazenados na aba `Bases` do arquivo Excel e incluem informações sobre assinaturas, planos, preços, renovação automática e serviços adicionais.

As informações são utilizadas para agrupar registros, comparar categorias e calcular valores agregados.

A interpretação dos resultados depende dos registros e dos filtros aplicados às análises. Por isso, é importante verificar se os filtros selecionados correspondem às perguntas de negócio propostas.

## Perguntas de negócio

O projeto contempla quatro perguntas principais:

1. Qual é o faturamento total das assinaturas, considerando os registros agregados?
2. Como o faturamento se divide entre assinaturas com e sem renovação automática?
3. Qual é o total de vendas do adicional EA Play, separado por plano?
4. Qual é o total de vendas do adicional Minecraft, separado por plano?

As perguntas são exploradas na aba `Cálculos`, que reúne as tabelas dinâmicas utilizadas como apoio à análise e à construção do dashboard.

## Recursos do Excel utilizados

### Tabelas estruturadas

A base de dados está organizada em uma tabela, facilitando a identificação das colunas e a utilização dos registros nas análises.

### Tabelas dinâmicas

As tabelas dinâmicas permitem agrupar e resumir os dados por categorias, como plano contratado, tipo de assinatura e renovação automática.

Esse recurso facilita a comparação dos resultados sem a necessidade de realizar manualmente cada agrupamento.

### Filtros

Os filtros permitem delimitar o conjunto de registros considerado em uma análise, como o tipo de assinatura selecionado.

A escolha correta dos filtros é essencial para garantir que os resultados correspondam às perguntas de negócio.

### Dashboard

A área de apresentação visual reúne os resultados de forma organizada, permitindo consultar os indicadores e comparar diferentes aspectos das assinaturas.
